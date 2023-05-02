

**RELEASE Ver. 1.20 - May 2nd, 2023**

* Compatibility update for Retail 10.1 launch.

* Lua error would occur when in some raid groups. Didn't break anything, but the Lua error was there, which is annoying, so this is resolved now.


**RELEASE Ver. 1.19 - April 29th, 2023**

* Slightly updated the version check with GRM.


**RELEASE Ver. 1.18 - April 17th, 2023**

* Fixed Lua error that could occur when joining a guild, whilst in party with someone from the guild you are joining... the first trigger of the "GuildData" would not yet be available as you would still be configuring the guild the first time. Now it will wait until data is ready.

* Fixed it so the "Trade distance icon" now properly shows on all the new frame formats, inlcuding party/raid frames. Previously it was only showing on the GRM and the old "O" social window, but not the new raid/party frames beyond the first button.

***QUALITY OF LIFE***

* If the Group Info module does not matchup with the latest GRM addon, because it is outdated, you will now be notified after login.

**RELEASE Ver. 1.17**

* Fixed some Lua errors that were occurring.

* Compatibility with 10.0.7 in Retail

**RELEASE Ver. 1.16**

* Fixed a lua error that could occur when mousing over a player right when they drop group.

**RELEASE Ver. 1.15**

* Fixed an issue where a lua error would occur preventing addon module from loading if using a custom UI, like ElvUI or Shadowed Frames, etc...

* Added an option to easily disable the mouseover tooltip so you will ONLY see the popout window.

* Added compatibility to the new raid frames in Dragonflight.

**RELEASE Ver. 1.14**

* Compatibility for 10.0.5 Retail

**RELEASE Ver. 1.13**

* Compatibility for 3.4.1 Wrath Classic

**RELEASE Ver. 1.11**

* Compatibility for 10.0.2 and DRAGONFLIGHT released!

**RELEASE Ver. 1.10**

* Compatibility Release for 9.1 - update all codebases.

**RELEASE Ver. 1.09**

* Compatibility Release for WOW Classic TBC + WOW Classic Era, and creation of universal codebase for all versions of addon thanks to multi .toc capabilities now

**RELEASE Ver. 1.08**

* Compatibility Release for 9.0.5

* Fixed a bug with the background template throwiing a Lua error on the colorpicker window.

**RELEASE Ver. 1.06**

* Compatibility release with pre-SL week 9.0.2 launch

**RELEASE Ver. 1.04**

* The button will now save to 2 different zones, depending on if you are in a Raid, or a party(group). It makes sense to have a position for parties and a position for raids. It will auto swap the positioning if you go from a party to a raid and so on.


**RELEASE Ver. 1.03**
* 9.0 Release compatibility!

**RELEASE Ver. 1.02**

* Fixed a spacing issue where a certain line can overlap the end.


**RELEASE Ver. 1.01**

***Bug Fixes***

* The button should now properly hide when closing the windows.

* Fixed an issue where if the players names were moved around they would still be updated at their old positions for the colored interact distance icon.

* Potentially resolves the issue where some larger names were bleeding over the edge of the mouseover. I will need confirmation on this one but I found a place where the width of the text could in some cases be as much as font 10 wifth wider than the frame.


***Quality of Life***

* No more of this bouncing around on where it is pinned. To increase functionality the button is now completely movable and you can customize where you want to set it. I have made this a per-character location as I know some people run different addons depending on the alt. Just hold CTRL-SHIFT to drag it.

* The player's own name will be included in the list now. This is due to the somewhat confusing aspect of saying group size is say 20, but only showing 19. To prevent any confusion.

* Compatibility with various UI addons for the interact distance notifier. The following are the addons with built-in compatibility now:

- ElvUI

- TUKUI

- Spartan UI

- Shadowed Unit Frames

- Z-Perl

- Grid

- Luna Unit Frames (Classic)