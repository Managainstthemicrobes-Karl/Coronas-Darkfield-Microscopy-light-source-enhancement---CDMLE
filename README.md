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

- Using modern LED lighting technology to achieve greater optical resolution and clarity for darkfield microscopy without sample disfiguration from heat.
- Broad-spectrum LEDs combined with re-worked optical path and re-focusing to accommodate the new light-source position.
- Designs that eliminate the need for large distances and refocusing thanks to massive heatsinking and cooling.
- Recognition that 100 W LED systems can fit near the original illuminator lens but yield less optimal light shaping than the 300 W system.

The microscope currently achieves close to **30,000 lumens at 300 W**, adapting a microscope to use extremely high light power specifically for darkfield and low-light conditions.

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
- 160 mm collimating or refocusing lens (positions LED at correct focal distance)  
- Chromed light-guide tube/skirt to reduce stray light and increase darkfield contrast  
- A cabinet or mount to house the modified microscope  

---

## Modification Notes  

- Not all microscopes can be modified safely; high-heat systems can melt cheaper optics or body materials.  
- The example here uses a **Leica DM2000** lab-grade light microscope.  
- Remove the bottom housing plate, filament lamp system, and any optics or diffusers except the illuminator glass (the last optic visible below the condenser).  
- Insert the 160 mm lens a few centimetres below the illuminator glass and secure it (high-temp glue or metal holding plate).  
- Ensure the LED COB face is approximately **160 mm from the lens**.  
- Attach the chromed tube skirt from a heat-proof clamp next to the LED COB and direct light up to the 160 mm lens.  
- Leave heat-escape gaps below and above the skirt; failure to do so will destroy the LED or may cause fire/explosion.  

---

## Safety Warnings  

⚠️ **High-power LEDs and heatsinks can be hazardous.**  

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
> I do not authorize any **institution, authority or organizations** to restrict the use or distribution of the CDMLE (Coronas Darkfield Microscopy Light-Source Enhancement).
>
> The concept and imagery results have also been posted elsewhere over the last year. The system was initially tested over seven months ago and has been used almost daily since. Current date: September 17th 2025.

See the [LICENSE](LICENSE) file for the full legal text.

---

## Credit & Terminology  

Please use the abbreviation **CDMLE** when referring to this modification.  
This helps ensure proper attribution and a consistent name for its use worldwide.

---

This file documents the essential concept and ties the basic information into a relevant context. Further data and files shall be added over time and i look forward to community mods or forks in the future.
