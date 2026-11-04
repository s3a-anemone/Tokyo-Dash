# Tokyo Dash

A browser-based JDM-inspired arcade racer set on neon-lit Tokyo streets, with shrines, pagodas, torii gates, lanterns, and cherry blossoms.

## Run it

**Quick start on Windows:** double-click `play.bat`. It starts the local Python server if Python is installed; otherwise, it opens the game directly in your browser.

Or install Python 3 and run `python server.py` from this folder. The game opens at `http://127.0.0.1:8000/`.

The browser game has no build step, external packages, or image downloads. You can also open `index.html` directly.

## Desktop controls

The layout is designed for desktop keyboard play and intentionally does not provide a mobile layout or touch controls.

- **Up Arrow** or **W**: accelerate
- **Down Arrow** or **S**: brake
- **Left / Right Arrow** or **A / D**: steer
- **Space**: use nitro
- **E**: activate the selected, purchased shop power-up during a race
- **P** or **Esc**: pause and resume
- **Enter**: start or restart

The car starts stopped; releasing the accelerator lets it coast down.
Each run begins with a 3–2–1–GO countdown.

## Game modes

- The opening menu shows your current car, paint, cosmetic, and yen balance; it includes direct Garage access and the three mode choices.
- **Casual:** relaxed traffic, five health points, and a visible finish stripe at the end of its 1,500-meter randomized route.
- **Limitless:** endless randomized roads through Tokyo, mountain-pass, coast, and bamboo-run scenery, with sharper bends, more pronounced road-width changes, rising traffic, and three health points.
- **Time Trials:** choose Rainy Harbor, Fuji Switchback, or Bamboo GP, then race on wide, traffic-free roads with no lives. Higher top speed and a stronger nitro burst make this mode about carrying speed and beating the clock. Medal targets are competitive: Harbor and Bamboo GP are 34/38/44 seconds for gold/silver/bronze; Fuji Switchback is 41/47/54 seconds. Each track saves your best time locally.

Collect yen (**¥10 per coin**) and grab nitro, timed invincibility, a jump that vaults over hazards, a coin magnet, and repair kits. Casual and Limitless routes include oil spills, cones, striped road barriers, tire stacks, and potholes, each with its own collision effect; jump or shield through them. Active timed power-ups show a countdown and duration bar. Spend saved yen in the **Garage Shop** to unlock and equip four car bodies, nine paint finishes, and four visible drift/underglow effects. Its Cars, Paints, FX, and Items tabs include distinct pixel-car previews and purchasable single-use power-ups: Golden Nitro (12 seconds of faster speed without nitro fuel drain), Phase Shield, Hop Charge, Yen Magnet, Score Surge (double points), and Repair Kit. Buy or equip an item in the Items tab, then press **E** during a race to activate it. Item stocks, wallet, purchases, equipped choices, career totals, traffic setting, best scores, and time-trial records save locally on the current device; no account or cloud sync is used. The shop also has a Save Progress button and a Debug button that adds ¥100 per press. Nitro recharges faster and has a visible in-game meter; it cuts out as soon as it empties, and holding boost cannot restart it until you release the key. Cars accelerate faster and have higher top speeds; braking while steering at speed initiates a stronger drift. Endless modes save their best scores.

Set **Traffic Density** to Light, Standard, or Heavy in the side panel; the choice saves locally and can be changed during a run. It also sets the run's score multiplier: Light **0.5×**, Standard **1.0×**, and Heavy **1.5×**. The active multiplier appears below the score and applies to driving points and pickups/obstacle bonuses. Time Trials use **1.0×** because they have no traffic. Use the **Home** button in the header (or click the Tokyo Dash logo) to return to the mode and track menu.

The desktop-focused game fills the available screen with crisp, low-resolution 8-bit-style sprites and a limited arcade palette. Its rear-follow drone camera stays level through bends; the player's car only steers when you press a steering key, with the whole car sprite staying together as it angles to reveal its side. Player steering at speed creates fishtails, tire smoke, and blocky skid marks; pressing brake while steering sharply increases the slide. Road curves do not steer the car for you. The slightly flattened road perspective shows a longer stretch ahead while keeping turns visible; the road surface is clean of lane and transverse stripe markings. Casual and Limitless routes vary in width, with more dramatic road-size changes in Limitless, guard markers, and a minimap preview. Time Trial roads are wider and have no traffic or roadside obstacles. A checkered finish stripe marks the end of Casual runs. Layered mountain scenery, cherry trees, bamboo, pines, and coastal palms fill out the changing biomes. Road-edge clearance accounts for the player's car width. Crashes trigger a shake, speed loss, and square sparks and debris. Traffic and pickups share the same world speed and perspective.
