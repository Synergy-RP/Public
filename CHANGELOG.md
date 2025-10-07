# Synergy Roleplay Changelog
This is the official changelog of the Synergy Roleplay FiveM server where all additions, changes and removals from the server's core features are listed. This changelog dates from 06/09/2025 onwards. This changelog is updated each time an update is released so be sure to check this after each update to see what's changed.

---

## [1.2.0] - `Core Feature Overhaul, Optimisation & New Content`
> 8th of October, 2025

__This major update focuses on refining and upgrading many of the server's core systems, introducing new gameplay mechanics, adding performance improvements, and refreshing content across the board. We've streamlined police tools, expanded criminal activities, and continued our commitment to a smooth, engaging experience.__

---

### New Features & Content
- **Fleeca Heist Overhaul:** Fully configured the **Fleeca Bank** heist with support for **custom minigames**.
- **Pinkslips:** Fully set up the **pinkslips** system for vehicle ownership.
- **House Robberies:** Configured and balanced **house robberies**.
- **Pawnshop:** Set up the **pawnshop** resource.
- **New Meth Resource:** Introduced a dedicated **Meth resource**.
- **New Weapon:** Added the **Technical 9** weapon.
- **New Vehicles:** Added the **Dubsta G**, **Bati 801C**, **BRT600**, and **Shinobi 25**.
- **New Items:** Added a **radar receipt item** and a **new remote explosive item**.
- **Blueprints:** Added **loads of blueprints** to the economy.
- **Show IDs:** Added a **show IDs resource** accessible via the Home key.
- **Bobcat:** Added a **crate item** specifically for the Bobcat location.
- **Chat:** Enabled the **`/me`** command for improved roleplay.

---

### UI / HUD
- **Custom Map:** Added a **custom minimap/map** resource for a fresh look.
- **HUD Theme:** Created a **default HUD theme** for a more cohesive server aesthetic.

---

### Law Enforcement (LEO)
- **Police Radial Menu:** Added a **working radialmenu for police** for streamlined interactions.
- **Vehicle Fleet:** Updated **all police vehicles to polemergency**.
- **Police Script:** Updated the **police script** resource.
- **Stash Coords:** Updated **stash coords for PD**.
- **Fixes:** Fixed the **PD dealership** and fixed **MDT hanging when getting player vehicles**.
- **Blips:** Removed blips for all stations apart from **SSPD/MRPD**.
- **Removals:** Removed the **new police rebla** from the fleet.

---

### Criminal Activities & Jobs
- **Fleeca Payouts:** Configured and balanced **payouts** for the Fleeca Bank heist.
- **Boosting Tweaks:** Tweaked boosting, added **required items**, and updated the resource with **better pagination and optimisation**.
- **Robberies:** Disabled **strikes in robbery**.
- **Skills:** Made **skill checks for searching easier**.
- **Tweak:** Tweaked **bobcat** balance.
- **Removals:** Removed the **legion store robbery** and the **legion store** MLO.

---

### Inventory & Weapons
- **Inventory Weight:** Reduced the overall **inventory weight limit to 100kg**.
- **Weapon Weight:** Reduced the **weight of weapons**.
- **Stash Size:** Increased **stash size in properties**.
- **ID Card:** Updated **qbx idcard** resource.
- **ID Card Settings:** Updated **id card auto close settings**.
- **Weapon Sling:** Applied **weapon sling adjustments**.
- **Weapon Models:** Removed **unused weapon models** and **broken weapon models**.
- **Visual Fix:** Fixed the **beanbag shotgun model green textures**.

---

### Optimisation & Backend
- **Database:** Now using **node22 on oxmysql** for better database performance.
- **Audio:** Removed **xsound** and **interact-sound** as we now use **native audio**, streamlining resources.
- **Server Artifacts:** Updated **server artifacts** for performance and stability.
- **Fivecache:** Set up **fivecache properly** for better data management.
- **Voice:** Updated the **pma voice** resource.
- **Locations:** Moved all **location files externally** for easier management.
- **Menu Map:** Compressed images in the menu map (reduced 8MB file size).
- **API Keys:** Added **fivemanage API keys** for the in-game phone.

---

### Bug Fixes & Adjustments
- **Script Fix:** Fixed a **script crash when playerdata is nil**.
- **Finance Fix:** Fixed **finance value not updating till second payment**.
- **Gameplay Fix:** Prevented carrying a player while dead.
- **Bat Damage:** Reduced **damage from bat** attacks.
- **Tyres:** Increased **tyre jump pop threshold** to make jumping safer.
- **Racing:** Updated **racing resource** and applied **racing tweaks**.
- **Boss Menu:** Updated the **bossmenu / multijob resource**.
- **Admin Menu:** Updated the **admin menu**.
- **Chat:** Fixed an issue with **chat**.
- **Commands:** Updated `commands.lua`.
- **Vehicle Spawns:** Enabled **server setter for vehicle spawns**.
- **Scoring:** Removed the **scoreboard**.
- **Blips:** Disabled **train blips**.
- **Old Content Removal:** Removed the **legion mlo** and **vangies clothing store**.

---

## [1.1.0] - `Balancing economy, Optimisation, Vehicle Tweaks`
> 17th September 2025

### Vehicles
- Updated handling and damage for all Gabz vehicles  
- Updated handling and damage for Onx police pack  
- Fixed Dorado handling  
- Removed unused EMS pack  

### Weapons
- Added new M4 model  
- Added new MP5 model  

### Jobs & Economy
- Added new civilian jobs: Electrician, Go Postal, Trash Collector  
- Configured and balanced all three jobs for economy stability  
- Added custom Go Postal outfit  
- Added items for crafting  
- Adjusted paycheck timings for balance  
- Added J’s to multi-job system  

### Gameplay & Scripts
- Configured medical script  
- Prevented carrying players when downed  
- Refactored hurt effect  
- Made bike tyres more resistant to popping  
- Changed radar speed detection in dispatch from KMH to MPH  
- Configured TAM police  
- Fixed casino ped locations  
- Fixed casino chip name + converted all casino interactions to use chips  
- Fixed slots bug where players got stuck without money  
- Increased parachute use time  
- Added outfit bag item  
- Implemented optimised first-person carfighting  
- Tweak: 10 codes for dispatch  
- Tweaked boosting UI  
- Added more items to the lucky wheel  
- Added 24h cooldown for lucky wheel (including a Panto prize 🎉)  

### Optimisation
- Removed unused libraries  
- Replaced heavy thread with more efficient loopless logic  
- Updated 919admin for improved performance  
- Updated radialmenu to use correct events  
- Slightly reduced population density  

### Miscellaneous
- Added new dealership categories for LEO vehicles

---

## [1.01.0] - `Ranks, Jobs, MDT, Optimisations & More`
> 7th of September, 2025

__This update continues our commitment to balance, performance and immersive roleplay. We’ve introduced new jobs, systems and optimisations while refining existing features to make the overall experience smoother and more engaging.__

### Added
- Added Deputy Assistant Chief Rank.
- Added Taxi Job.
- Added more minigames.
- Added racing tablet image.
- Added Police items.
- Added missing images for Benelli and MP7.
- Added XT Prison.
- Added medical items + images.
- Added Police vehicles to `vehicles.lua`.
- Added Police BF400.
- Added all 11,000+ clothing images, fully named and organised.

### Changed / Fixed
- Fixed Multijob / Bossmenu.
- Updated storage units and properties resource.
- Fixed correct pathing for file caching.
- Removed unused manifest data.
- Removed warehouse robberies until `sd-lib` is dropped.
- Updated phone to use correct banking exports.
- Replaced weapon names with lore friendly counterparts.
- Changed Bossmenu location for the LSPD.
- Fixed PD armory missing slots.
- Fixed player robbing.
- Disabled `/tablet` for racing.
- Balanced medical revival prices.
- Tweaked Dispatch blips.
- Fixed error with bridge for TAM Police.
- Added Dispatch integration with TAM Police.
- Removed unused location in medical script.
- Removed unnecessary chat suggestions for optimisation.
- Merged stream resources for faster loading.
- Rewrote MDT logic to take screenshots using Fivemanage (not Discord).
- Voice script now starts before Radio.
- Whitelisted offroad bikes for better traction.
- Tweaked offroad bike handling.
- Fixed radio connection issues.
- Fixed collision issues between Legion and MRPD.
- More logging on Admin Menu.
- More logging on Inventory.
- More logging on Racing.

### Tweaks
- Optimised Binoculars.
- Tweaked tyre popping behaviour.
- Adjusted boosting balance slightly.
- Properties now work with Phone.
- MDT now works with Properties.
- MDT now works with Garages.
- MDT fully functional.

---

## [1.00.0] - `Vehicle Balancing tweaks, Performance Improvements + Small Features`
> 6th of September, 2025

_This update brings with it a few tweaks to some new cars we've been playing around with, with the goal to provide a variety of cars that handle in a unique way unlike any other server whilst not being completely unrealistic to their real life counterparts._

_We pride ourselves on our optimisation with the goal of providing a roleplaying experience anyone can enjoy. We've made a lot of improvements and major gains since our server first launched - with much more to come - towards better frame rates. _

### Added
- Added New car: Dinka Jester MK4 (plenty of customisation 👀).
- Added New car: Karin S95.
- Added New south side Auto Shop MLO: `J's Auto Repairs`.
- Added New racing system `nx.racing` with a variety of custom race tracks split into 3 differant catagories. `Motorcycles, Non-Supercar/Motorcycles & Supercars`
- Added New Dispatch system for Law Enforcement & Medical Services.
- Added New Police system for Law Enforcement.
- Added New SWAT clothing items
- Added 2 New lore friendly wheel packs addoing over 100+ new wheels to put on your vehicles listed under `Muscle & Lowrider catagories`.
- Added New fuel system.
- Added New PDM MLO.
- Added AMZN Admin.

### Changed / Fixed
- Fixed locals in gang affiliated areas attacking the player on sight.
- Optimised the HUD for better performance.
- Optimised the Scoreboard for better performance.
- Removed unused/heavy assets for better performance.
- Reoptimised all clothing for better perfomance.
- Removed old cars from `vehicles.lua` & added new ones to it
- Removed old Benny's MLO
- Clothing resource updated
- Removed old wheel pack
- Removed unused images
- Tweaked tyre popping to be slightly more lenient on jumps before popping your vehicles tyres.
- Optimised Vehicle Mileage.
- Improved backend logging for exploit/abuse protection.
- Tweaked handling on some new vehicles and base cars for balancing purposes.
