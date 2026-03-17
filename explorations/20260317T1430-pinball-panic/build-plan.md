# PINBALL PANIC — Build Plan

## Concept
Giant walk-up pinball machine. 4ft wide × 8ft long tilted playfield. Two player "flipper pit" stations at the bottom with real swinging paddles. Spring-loaded plunger launches whiffle balls down the field. Rubber-capped bumpers, ramp lanes, spinner gate, and scoring targets. Neon-on-black aesthetic with UV paint and LED accents.

## Modes
- **Cooperative:** Both flippers work together, combined score vs. target (500 / 1000 / 2000)
- **Competitive:** Each flipper has a scoring side — your misses cost you, not your partner

---

## Overall Dimensions

| Dimension | Size | Notes |
|-----------|------|-------|
| Playfield width | 48" (4 ft) | Two flippers side-by-side |
| Playfield length | 96" (8 ft) | Full pinball travel distance |
| Playfield depth (rail height) | 4" | Whiffle ball (2.75") + clearance |
| Tilt angle | ~10° from horizontal | Gentle enough for young kids, steep enough for ball movement |
| Peak height (top end) | ~42" off ground | Comfortable standing height for the plunger operator |
| Bottom height (flipper end) | ~26" off ground | Waist-height for kids at flipper stations |
| Total footprint with legs | 48"W × 110"D × 42"H | Includes leg splay and flipper pit clearance |

---

## Architecture

### 1. Playfield Surface
- **Material:** Single sheet of ¾" plywood, 4×8 ft (standard sheet, no cutting needed!)
- **Surface treatment:** Sand smooth, prime, paint matte black, then add neon lane markings and scoring zones with spray paint + UV-reactive paint
- **Edge rails:** 1×4 lumber strips along all four edges, screwed to plywood. Creates the 3.5" tall walls that keep balls in play
- **Modular attachment grid:** Pre-drill a 6" grid of ¼" holes across the playfield surface. All bumpers, targets, and ramps bolt into this grid. Allows layout changes year-to-year without new holes

### 2. Support Frame & Legs
- **Front legs (flipper end, ×2):** 2×4 lumber, 26" tall, attached with carriage bolts and wing nuts for tool-free assembly
- **Rear legs (plunger end, ×2):** 2×4 lumber, 42" tall, same bolt attachment
- **Cross bracing:** 1×4 diagonal braces between each leg pair (front-to-front, rear-to-rear) plus one long lateral brace along each side
- **Feet:** Rubber caps on all 4 legs to prevent sliding
- **Folding design:** All legs hinge-mount to the underside of the playfield. Fold flat for transport. Wing nut locks in play position
- **Side handles (×2):** Heavy-duty gate handles on each long edge of the playfield for two-person carry

### 3. Flipper System (×2)

The star of the show. Each flipper is a real swinging paddle that the player operates by hand.

- **Paddle:** 24" long × 4" wide piece of ¾" plywood, edges rounded and sanded. Painted neon (P1 = neon pink, P2 = neon green)
- **Hinge point:** Heavy-duty 3" door hinge mounted at the inner edge of each flipper pit, at the bottom of the playfield. Flipper pivots from the inside outward
- **Rubber bumper tip:** 2" rubber ball or furniture bumper epoxied to the striking end of the paddle. Gives satisfying bounce and protects the ball
- **Handle:** 8" wooden dowel (1" diameter) mounted vertically on the paddle, 6" from the hinge. Player grabs this and swings
- **Return spring:** Screen-door spring connecting the paddle to the edge rail. Pulls the flipper back to resting position after each swing
- **Stop bolt:** Carriage bolt in the playfield surface limits flipper swing to ~60° arc
- **Flipper pit:** The bottom 12" of the playfield between the two flippers is the "drain" — a gap in the bottom edge rail where missed balls fall into a collection tray below
- **Flipper spacing:** Flippers positioned to leave a 6" gap at center when at rest (the drain gap). Full swing closes the gap — skilled timing required

### 4. Launch System
- **Location:** Top-right corner of the playfield (when viewed from the flipper end)
- **Plunger:** Spring-loaded pinball plunger assembly (~$8 online). Mounted through the top edge rail
- **Launch lane:** 4" wide channel formed by a strip of 1×4 running parallel to the right edge rail, 4" inward. Ball drops into lane, plunger fires it down the playfield
- **Ball feed:** Gravity-fed PVC tube (3" diameter) mounted vertically at the top of the launch lane. Holds 5 balls stacked. Bottom ball drops into launch position automatically
- **Lane exit:** Bottom of the launch lane has a curved deflector that sends the ball across the top of the playfield and into the bumper zone

### 5. Bumper System

#### Pop Bumpers (×6)
- **Construction:** 3" diameter 3D-printed mushroom cap on a ¼" bolt. Bolt passes through the playfield grid hole. Under the playfield: rubber band wrapped around the bolt between two washers creates spring tension
- **Behavior:** Ball hits the cap, cap depresses, rubber band snaps it back — ball bounces away unpredictably
- **Bell option:** Mount a small jingle bell on the bolt below the playfield. Every hit = audible ring
- **Placement:** Clustered in the center-upper zone of the playfield in a triangular formation, plus 2 outliers near the edges

#### Static Bumpers / Posts (×8)
- **Construction:** ¾" wooden dowels, 3.5" tall, glued into playfield grid holes
- **Rubber sleeve:** Section of rubber tubing slipped over each post for bounce
- **Placement:** Scattered across the playfield to create ricochet paths and channel ball movement toward scoring zones

### 6. Ramps & Lanes

#### Loop Ramp (left side)
- **Construction:** Curved channel made from two strips of ¼" plywood (or thin hobby plywood), bent into a half-loop. 4" wide, walls 3" tall
- **Entry:** Open at bottom-left of playfield. Ball enters moving up, curves 180° and exits moving back down toward center
- **Scoring:** Microswitch or gravity-activated bell at the apex of the loop. 100 points
- **Material tip:** Soak thin plywood strips in water and clamp into curve form to dry. Or use 3D-printed channel sections

#### Jackpot Ramp (center)
- **Construction:** Straight ramp, 5" wide, angled up at 15° from the playfield surface. Made from ¼" plywood with 1" edge lips
- **Entry:** Bottom-center of the playfield, directly between the flippers. This is the "hero shot"
- **Exit:** Ramp rises to mid-field height and deposits ball onto an elevated rail that feeds back to the launch lane (ball return!)
- **Scoring:** Ball rolling past the top triggers a bell or drops through a sensor. 500 points. JACKPOT
- **Visual:** Paint this ramp screaming yellow with "JACKPOT" in neon pink letters

#### Spinner Gate (upper-left lane)
- **Construction:** Flat 3D-printed or sheet metal disc mounted on a horizontal axle between two posts. Ball passes through and spins the disc
- **Scoring:** 25 points per full rotation. Skilled shot = hard hit = multiple spins = big points

### 7. Star Targets (×3)
- **Construction:** 3D-printed star shape (4" diameter) mounted on a spring-loaded bolt (same as pop bumpers but flat-faced)
- **Behavior:** Ball hits the star, it depresses, springs back. Audible click or bell
- **Placement:** Upper-right cluster, stacked vertically with 6" spacing
- **Scoring:** 50 points each. Hit all 3 in one ball = 200 bonus (indicated by a "COMBO" sign)

### 8. Drain & Ball Return
- **Drain:** 6" gap in the bottom edge rail, centered between the two flippers. Missed balls fall through
- **Collection tray:** Shallow plywood box (48" wide × 12" deep × 4" tall) mounted under the flipper end of the playfield. Angled slightly so balls roll to center
- **Ball retrieval:** Open front on the collection tray. Operator grabs balls and reloads the feed tube at the top
- **Alternative:** If feeling ambitious, build a gravity-return channel along the underside of the playfield that feeds balls back to the top launch tube. Requires the playfield to have enough height clearance underneath

### 9. Scoring & Visual System
- **Manual scoring:** Volunteer scorekeeper with a whiteboard. Simple, reliable, carnival-proof
- **Bells:** Jingle bells on pop bumpers + larger cowbell on the jackpot ramp. Audible feedback is half the fun
- **LED strips:** Battery-powered adhesive LED strips along the edge rails. Neon pink and green, matching flipper colors
- **UV paint:** Scoring zones, lane markings, and "JACKPOT" text painted with UV-reactive paint. Add a battery-powered UV blacklight strip and the whole table GLOWS
- **Backdrop sign:** Painted plywood sign mounted vertically at the top end: "PINBALL PANIC" in dripping neon letters

---

## Materials List

### Lumber & Sheet
| Item | Qty | Est. Cost |
|------|-----|-----------|
| ¾" plywood sheet (4×8 ft — full sheet, no cut!) | 1 | $45 |
| 1×4 lumber (edge rails + bracing, 32 lin. ft) | 4 (8ft) | $24 |
| 2×4 lumber (legs, 20 lin. ft) | 3 (8ft) | $18 |
| ¼" plywood scraps (ramps, flippers) | 1 half-sheet | $15 |
| ¾" wooden dowels 36" (bumper posts) | 4 | $10 |
| 1" wooden dowel 36" (flipper handles) | 1 | $4 |

### Hardware
| Item | Qty | Est. Cost |
|------|-----|-----------|
| Pinball plunger assembly | 1 | $8 |
| 3" door hinges (flipper pivots) | 2 | $8 |
| Screen-door springs (flipper return) | 2 | $6 |
| Carriage bolts + wing nuts (legs, stops) | 16 set | $15 |
| ¼"-20 bolts 4" (bumper mounts) | 14 | $10 |
| Rubber bands (bumper springs) | 1 bag | $4 |
| Washers (bumper assemblies) | 1 box | $5 |
| Wood screws (assorted) | 1 box | $8 |
| Heavy-duty handles | 2 | $12 |
| Rubber feet caps | 4 | $6 |
| Hinges (folding legs) | 4 | $12 |
| 3" PVC pipe (ball feed tube, 4ft) | 1 | $6 |

### 3D Printed Parts
| Item | Qty | Est. Cost (filament) |
|------|-----|---------------------|
| Pop bumper mushroom caps | 6 | $3 |
| Star targets | 3 | $2 |
| Spinner gate disc + axle mount | 1 | $2 |
| Lane deflector (launch lane exit curve) | 1 | $1 |
| Ramp edge clips (hold ramp walls to playfield) | 8 | $2 |

### Game Pieces & Finish
| Item | Qty | Est. Cost |
|------|-----|-----------|
| Whiffle balls (standard size, neon colors) | 12 | $8 |
| Spray paint — matte black (playfield base) | 2 cans | $10 |
| Spray paint — neon pink, green, yellow | 3 cans | $15 |
| UV-reactive paint (scoring zones) | 2 bottles | $12 |
| Rubber furniture bumpers (flipper tips) | 2 | $4 |
| Rubber tubing (bumper post sleeves, 3ft) | 1 | $5 |
| Jingle bells (bumper bells) | 6 | $4 |
| Cowbell (jackpot bell) | 1 | $6 |
| Battery-powered LED strip (neon, 16ft) | 1 | $15 |
| Battery-powered UV blacklight strip | 1 | $12 |
| Adhesive vinyl letters ("PINBALL PANIC" sign) | 1 set | $8 |

### **Estimated Total: $350–420**

---

## Build Sequence

### Phase 1: Playfield & Frame (Day 1)
1. Sand the 4×8 plywood sheet smooth on one face (this is the playfield surface)
2. Drill the modular attachment grid: ¼" holes, 6" spacing, across the entire playfield surface. Use a template jig for consistency
3. Cut and attach 1×4 edge rails along all four sides with wood screws. Leave gaps for: launch lane (top-right, 4" gap), drain zone (bottom-center, 6" gap)
4. Cut 2×4 legs to length (2 × 26", 2 × 42"). Attach folding hinges to playfield underside
5. Install cross bracing between leg pairs
6. Attach rubber feet
7. Mount side handles
8. Test: Legs fold flat? Playfield sits stable at ~10° tilt? Wing nuts secure?

### Phase 2: Flippers & Launch (Day 2)
1. Cut two flipper paddles from ¾" plywood: 24" × 4", round all edges
2. Mount 3" hinges at the flipper positions (bottom of playfield, 6" from each side, inner edge)
3. Drill and install 1" dowel handles on each paddle
4. Install stop bolts limiting swing to 60°
5. Attach screen-door return springs (paddle to edge rail)
6. Epoxy rubber bumpers to flipper tips
7. Build launch lane: Cut 1×4 strip, mount parallel to right edge rail, 4" gap
8. Mount pinball plunger through top edge rail
9. Install 3" PVC ball feed tube vertically at launch lane top. Mount with pipe clamps
10. Shape and mount launch lane exit deflector (3D-printed curve)
11. Test: Drop a ball in. Plunge it. Does it travel the full field? Do the flippers swing freely and return? Does the drain work?

### Phase 3: Bumpers, Targets & Ramps (Day 3)
1. Print all 3D parts: 6 mushroom caps, 3 star targets, 1 spinner disc, 1 deflector, 8 ramp clips
2. Assemble pop bumpers: bolt + washer + rubber band + washer + mushroom cap. Thread jingle bell onto bolt below playfield
3. Install 6 pop bumpers in triangular cluster (upper-center zone) plus 2 outliers
4. Cut and install 8 wooden dowel static bumpers. Slip rubber tubing over each
5. Build loop ramp: Soak thin plywood strips, bend into half-loop form, clamp and dry. Assemble with ramp clips into playfield grid
6. Build jackpot ramp: Cut ¼" plywood base (5" × 24"), add 1" edge lips, mount at 15° angle at bottom-center. Install cowbell trigger at top
7. Mount spinner gate: Axle between two dowel posts in upper-left lane
8. Mount star targets in upper-right cluster
9. Test: Roll balls across every zone. Do bumpers bounce? Does the loop ramp flow? Does the jackpot ramp return to launch lane? Are there any dead spots where balls get stuck?

### Phase 4: Paint, Lights & Polish (Day 4)
1. Remove all playfield elements (they bolt out — that's the beauty of the modular grid)
2. Paint entire playfield surface matte black (2 coats)
3. Mask and paint lane markings: neon pink flipper zones, neon green scoring zones, neon yellow jackpot ramp
4. Paint UV-reactive accents on scoring zones and "JACKPOT" text
5. Paint flippers: P1 neon pink, P2 neon green
6. Reassemble all playfield elements
7. Install LED strip along edge rails
8. Install UV blacklight strip along top edge (aimed down at playfield)
9. Build and paint backdrop sign: "PINBALL PANIC" on scrap plywood, mount vertically at top end
10. Full playtest: 5 balls, both flippers, score every zone. Tune bumper tension. Adjust tilt angle if balls move too fast/slow. Verify no ball-trapping dead spots
11. Pack it up: fold legs, bundle ramp pieces, bag hardware. Verify two-person carry works

---

## Transport & Setup
- **Breakdown time:** ~15 minutes (wing nuts, fold legs, remove sign)
- **Pieces:** Playfield (4×8, legs folded underneath), backdrop sign, collection tray, PVC ball tube, bag of balls, bag of spare parts
- **Vehicle:** Fits in a pickup truck bed or SUV with seats down (4×8 sheet is the long pole)
- **Setup time:** ~20 minutes (unfold legs, bolt, insert ball tube, place collection tray, power on LEDs)
- **Power:** Battery-powered LEDs and UV strips. No electrical outlet needed!

---

## Safety Notes
- Whiffle balls only — no hard balls, no projectile risk
- Flipper swing is limited by stop bolts — no pinch hazard beyond the 60° arc
- Rubber bumper tips on flippers — even an accidental hand hit is cushioned
- Collection tray is enclosed underneath — no balls rolling underfoot
- Gentle 10° tilt — balls move at walking speed, nothing violent
- Edge rails contain all balls — nothing leaves the playfield
- Smooth, sanded, painted surfaces — no splinters

---

## Open Questions
- [ ] Festival date — drives timeline
- [ ] Power available? (LEDs and UV are battery, but if power exists, can upgrade to plug-in LED controller for effects)
- [ ] Signage / booth branding beyond the backdrop sign
- [ ] Prize structure (tickets per points?)
- [ ] Should we add a plexiglass "backbox" display at the top end showing the score? (cool but adds complexity)
- [ ] Sound system? A small bluetooth speaker playing pinball sound effects would be incredible atmosphere
