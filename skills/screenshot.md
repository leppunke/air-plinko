# Screenshot Skill

## Setup
- Playwright npm package: `npm install playwright`
- Pre-installed Chromium binary at `/root/.cache/ms-playwright/chromium-1194/chrome-linux/chrome`
- The npm-bundled chromium can't be downloaded (network-restricted), so always use the pre-installed binary via `executablePath`

## Screenshot Script

```js
const { chromium } = require('playwright');

async function screenshot(htmlPath, outputPath, width = 900, height = 800) {
  const browser = await chromium.launch({
    executablePath: '/root/.cache/ms-playwright/chromium-1194/chrome-linux/chrome'
  });
  const page = await browser.newPage({ viewport: { width, height } });
  await page.goto(`file://${htmlPath}`);
  await page.waitForTimeout(1000);
  await page.screenshot({ path: outputPath, fullPage: true });
  await browser.close();
}
```

## Key Notes
- Use `fullPage: true` to capture the entire scrollable content
- Set viewport width to control layout (900px works well for the Air Plinko diagrams)
- The 1-second wait ensures canvas rendering completes
- Always use absolute `file://` paths for local HTML files
