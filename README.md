# Bejeweled
This is for converting 3.3.5 Bejeweled to 1.12.1 API.

Credit to Xennma for contributing a number of initial changes to get it started.

This addon is to play Bejeweled, it can auto play upon Death, and when you Fly. It's very nice for those periods in the game where you have to wait and has built in achievements.

It also has a means of comparing high scores with other players who have the same Addon.

![Bejewled](https://github.com/user-attachments/assets/326d9cb3-b207-433b-b658-359047b0885f)

Changes so far by Xennma.

"This PR makes the following initial changes in the backporting process:

The entire Bejeweled.lua file has been formatted so an actual person can read it to some extent.

Lua 5.1 length operator (#) has been replaced with Lua 5.0's getn function

SetFormattedText from WoW 2.3 API has been replaced with SetText(string.format()) calls from WoW 1.0 API.

References to icons only added in 3.0 have been adjusted to point at an addon specific location

Referenced 3.0 assets have been added to this new location (Interface\AddOns\Bejeweled\Icons\)

The TOC has been edited to indicate it's a 1.12 versioned addon

Plenty of additional changes still need to be made, such as changing event functions to use the global (this, arg1-arg10) variables instead of event defined ones which was only added in later clients, but these should help make it easier for someone to perform them."
