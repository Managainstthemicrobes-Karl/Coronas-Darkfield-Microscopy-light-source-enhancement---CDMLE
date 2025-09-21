# Coronas Darkfield Microscopy Light-Source Enhancement — CDMLE  

**Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)**  

A novel enhancement for darkfield microscopy. It enhances the use of darkfield microscopy for viewing detail in cells, nanostructures, and plasmonic particles from approximately 20 nm upward.

*(See image files for demonstration of optical results.)*

---

## Overview  

This repository documents a public, time-stamped disclosure of a high-intensity LED light-source modification for laboratory microscopes.  
By publishing here, the concept is made publicly available to prevent corporate or organizational patenting while ensuring free use worldwide with attribution.

---

## Background  

Traditional filament and gas-lamp illumination methods restrict the use of high-power light sources due to massive heat dissipation.  
There has also been, in my view, a discouragement of darkfield microscopy in medical and biological fields for non-technical reasons.  

This modification overcomes those restrictions.  
It allows previously misunderstood structures and materials to be seen with far more eye-opening detail.  
For example, structures embedded in red blood cells can now reveal optical features such as structural colour, segmentation or compartmentalization, and plasmonic effects below 188 nm — details not clearly resolved by darkfield microscopy alone.

---

## Design Concept  

The protection under CC BY 4.0 specifically covers:

- Using modern broad-spectrum LED lighting technology to achieve greater optical resolution and clarity for darkfield microscopy imaging without disfiguration of the sample from the heat of traditional high-power sources.
- Broad-spectrum LEDs combined with re-worked optical path and re-focusing to accommodate the new light-source position.
- Alterable design that eliminates the need for large distances and complex refocusing thanks to massive heatsinking and cooling, but essentially allowing any microscope to be upgraded to light power suitable for the tempreture requirements set by the design quality.
- Recognition that 100 W LED systems can fit near the original illuminator lens but yield less optimal light shaping than the 300 W system due to surface area and COB elements.

The microscope currently achieves close to **30,000 lumens at 300 W**, adapting a microscope to use extremely high light power specifically for darkfield and low-light conditions. A generic based mod kit could easily be fabricated to attach to various microscope models of branded quality. Simply fitted in to one meatal case or standing unit where the mounts holes are pre-measured and drilled to fit each product with appropriate lens system in to the one box. I was requested to build several but did not have the time around then. The upgrade is so incredibly worthy that I only wish I had time to gain some funding for its simple inception to the world. 

My biggest hope is that this enhancement is used far and wide both in the scientific and ameteure fields. 

If anyone would like to DONATE KO-FI please visit: **https://ko-fi.com/kcresearch#**

---

## Basic Parts List  

*(See diagram files for layout.)*

- 100–300 W CRI97+ broad-spectrum LED (AliExpress or special order)  
- Large heatsink (300 W IGBT heatsink used here)  
- Minimum of two large high-RPM fans for 200–300 W systems  
  - One extracts air from the cabinet at the top-back panel  
  - The other is mounted on the IGBT heatsink  
- Optional small high-speed fan blowing over LED surface for longevity  
- Thermal paste  
- Suitable switch-mode power supply (matching LED voltage/current)  
- Adjustable current-control regulator with display (must tolerate LED load + overhead)  
- 160 mm collimating or refocusing lens (positions LED at correct focal distance). (160mm for Leica DM series microscopes only, distance of optical path varies by scope and optic spacing).
- Chromed light-guide tube/skirt to reduce stray light and increase darkfield contrast.   
- A cabinet or mount to house the modified microscope

  There are now 500Watt LEDS available as of very recently. BUT, these will give off extreme heat and often are not reliable in such high tempreture ranges without impractical design additions to account for all the heat. Worst of all the light overwhelms the sample background with scattered light and contrast can be lost significantly. The foot print of this COB LED at 300Watts is larger than I would prefer but is much smaller than most others of the same output power and the larger COB LEDS are definately far too large a surface area for maintaining quality imaging yet. The gain between a 100Watt LED and a 300Watt is not linear. Between 150Watts and 300Watts there is far less notable gain in improvement.
---

## Modification Notes  
(Not all microscopes can be modified safely; high-heat systems can melt cheaper optics or body materials).
(check the focal lengths and distances if using other brand scopes and models. This affects the refocusing lens requirement. For DM2000 160mm mwas distance required).
DON'T USE A CHEAP CAMERA AND EXPECT GREAT RESULTS! AVOID SMALL NOISY SENSORS! AVOID CHEAP CHINESE LOW QUALITY OPTIC MICROSCOPES IF LOOKING FOR TOP PERFORMANCE.

- The example here uses a **Leica DM2000** lab-grade light microscope.
 
- Remove the bottom housing plate, filament lamp system, and any optics or diffusers except the illuminator glass (the last optic visible below the condenser).  
- Insert the 160 mm lens a few centimetres below the illuminator glass and secure it (high-temp glue or metal holding plate).  
- Ensure the LED COB face is approximately **160 mm from the lens**.  
- Attach the chromed tube skirt from a heat-proof clamp next to the LED COB and direct light up to the 160 mm lens.  
- Leave heat-escape gaps below and above the skirt; failure to do so will destroy the LED or may cause fire/explosion.

- PLEASE NOTE! This was a rush idea in order to fulfil research requirements in practical use, the scope calculations and measurements may not be fully optimized, if mentioned at all. The concept is so simple that tailoring the lenses to your microscope specification should be a fairly easy task.
- IMPROVEMENTS! There will likely be folks who have more time than I do right now to play around.

  Results are what counts and in my case I manaaged to obtain imaging that was far above the quality of anything ive seen or could find evidence of in any peer review paper or place online. While searching for other designs out there I managed to find nothing. According to ChatGPT and other LLM's they could not find any patents or documentation regarding this particular form of microscope modification using this much light power. It seems a 300Watt COB LED is roughly 10x more powerful than most high-end lab-grade darkfield microscopes, the larger of which often use 150w and rarely sometimes 250watt arc lamps. Obviously LED Watts to gas and filament Watts do not give a comparable light output by watts alone, LEDS are far more efficient and give directed light in a forward direction rather than radially. 

---

## Safety Warnings  

⚠ **High-power LEDs and heatsinks can be hazardous.**  

- Use a thermal sensor of reasonable accuracy attached with thermal paste near the top surface of the IGBT heatsink close to the COB LED.  
- Connect the sensor to a **cut-off relay** for the COB LED and all other electrical systems in case of fire or thermal overload.  
- This can also ensure that the LED is protected from ambient temperature increases.  
- Fans can be intelligently controlled by the same system using a low-cost microprocessor and simple code with the right hardware.  

---

## see the MISC DATA page for useful data including thermal calulation approximations and more.

---

## License  

This work is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.  
You are free to use, modify, and distribute this work as long as you credit **Karl Coronas** as the inventor where applicable and the use of the concept name **CDMLE**.  

> **No patent rights are claimed. This disclosure is intended to act as prior art and to prevent others from patenting the same invention.**  
> I do not permit **any institution or organizations of ANY kind** to restrict the use or distribution of the CDMLE concept.
>
> The concept and imagery results have also been posted elsewhere over the last year. The system was initially tested over seven months ago and has been used almost daily since. Current date now: September 17th 2025.

See the [LICENSE](LICENSE) file for the full legal text.

---

## Credit & Terminology  

Please use the abbreviation **CDMLE** when referring to this modification.  
This helps ensure proper attribution and a consistent name for its use worldwide.

---

This file documents the essential concept and ties the basic information into a relevant context. see other files and look out for later additions.
