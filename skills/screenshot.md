# Screenshot Skill

## What's Available
- Playwright is globally installed at `/opt/node22/lib/node_modules/playwright`
- Chromium binary at `/root/.cache/ms-playwright/chromium-1194/chrome-linux/chrome`
- No `npm install` needed — just require from the global path

## Screenshot Script

```js
const { chromium } = require('/opt/node22/lib/node_modules/playwright');

async function screenshot(htmlPath, outputPath, width = 900, height = 800) {
  const browser = await chromium.launch({
    executablePath: '/root/.cache/ms-playwright/chromium-1194/chrome-linux/chrome'
  });
  const page = await browser.newPage({ viewport: { width, height } });
  await page.goto(`file://${htmlPath}`);
  await page.waitForTimeout(500);
  await page.screenshot({ path: outputPath, fullPage: true });
  await browser.close();
}
```

## Key Notes
- Use `fullPage: true` to capture the entire scrollable content
- Set viewport width to control layout (900px works well for diagrams)
- Always use absolute `file://` paths for local HTML files
- Don't install anything — sniff for what's already on the system first
