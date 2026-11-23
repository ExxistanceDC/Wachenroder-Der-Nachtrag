

# Wachenröder: Der Nachtrag

Not gonna write a huge fancy ReadMe for this one, but I'll at least tee up the patch:

Wachenröder: Der Nachtrag ("addendum") is an additive patch for the recent Wachenroder translation that fixes a bunch of issues. I don't have time at the moment to find and work with a translator to deliver a revision of the text, but I can at least bring my graphic design skills to improving some things with the current translation patch. 

With these changes, the game should feel as if Sega themselves localized it.

## Table of Contents
1. [Features](#Features)
1. [Screenshots](#Screenshots)
1. [Patching Instructions](#Patching-Instructions)
1. [Reporting Issues](#Reporting-Issues)
1. [Release Changelog](#Release-Changelog)

## Features

**Fonts**
- Redraw of primary font at 8 x 12 using a Georgia base, and dialogue re-wrapped to fit. New font also applies to: narration scenes, extras galleries, save/load screens, and more
- Item and part descriptions use a new small font with proper descenders
- Proportional font applied to: status screen/HUD/battle menu/battle banter scenes
- Centering and alignment fixes throughout
- Minor script polish throughout, like smoother phrasing and fewer repeated words. Example: "I want power...power to escape..." -> "I need power...power to escape...", "A bird takes wing, spreading its dark wings..." -> A bird takes flight, spreading its dark wings..."

**Graphics**
- Clean plated and removed JP from chapter title and location cards, leaving only background and German text
- Actually translated and redrew the end credits (matched with MobyGames)
- Translated and redrew Save Warning screens

**Bugs**
- Fixed original game bug on the save/load screen where months 10–12 would show as "0:", "0; or "0<"

**Enhancements**
- Extra galleries (Movie/Art/Voice) are now unlocked from the start, no need to beat the game (just don't spoil yourself)

## Screenshots 
<img width="800" alt="02_dialogue" src="https://github.com/user-attachments/assets/aca36c3d-a2ab-4089-8c9f-1b23402539c4" />
<img width="800" alt="01_location_card" src="https://github.com/user-attachments/assets/5daf98a9-df5e-4aac-98b9-4c3e5fa93c7f" />
<img width="800" alt="04_turn_info" src="https://github.com/user-attachments/assets/8ca00b30-e01f-4154-a37b-65f3b65d638d" />
<img width="800" alt="05_system_menu" src="https://github.com/user-attachments/assets/12ede981-f56d-428f-bac0-976944c4687d" />
<img width="800" alt="03_battle_card" src="https://github.com/user-attachments/assets/c2920ce0-4e82-438e-ac7a-e3461881bb41" />
<img width="800" alt="06_vogel" src="https://github.com/user-attachments/assets/47d0f97e-cfca-48d6-abaf-ecef19d616f6" />
<img width="800" alt="07_chapter_remembrance" src="https://github.com/user-attachments/assets/c9fc542a-593d-4893-a91b-784252303afd" />
<img width="800" alt="09_credits_cast" src="https://github.com/user-attachments/assets/56e695df-2b08-45db-89bf-d45eed934d91" />
<img width="800" alt="08_credits_staff" src="https://github.com/user-attachments/assets/078ef1b2-3227-4a42-b67a-eadbeb6333ad" />

## **Patching Instructions**

The patch is shipped as an XDelta patch. 

### XDelta Instructions ###

1. Grab an XDelta patching utility like <a href='https://www.romhacking.net/utilities/704/'>Delta Patcher</a>
2. Unzip patch bundle
3. Open **'DeltaPatcher.exe'**
4. For the Original File, locate Track 01 of the patched Wachenröder disc, aka: <kbd>Wachenroder-English-t147-Track1.bin</kbd>
5. Locate the <kbd>Wachenroder_der_Nachtrag_v1.0.xdelta</kbd> patch.
6. Click **'Apply Patch'**
7. If successful, Track 01 will be replaced with the addendum's patched track.

**--> Important! <--**
- Tested with release <kbd>Wachenroder-English-t147</kbd>
- Tested in Ymir and on real hardware with Satiator.

## Reporting Issues

If you find an issue, please [submit a new issue here](https://github.com/ExxistanceDC/Wachenroder-Addendum/issues/new).

## Release Changelog

- **Version 1.0 (11/23/2026)**
  - Initial release
