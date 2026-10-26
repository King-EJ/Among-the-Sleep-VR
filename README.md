# Among-the-Sleep-VR
Mod For Among the Sleep

<img width="448" height="442" alt="Adobe" src="https://github.com/user-attachments/assets/e9a790b9-a52c-473c-81b5-149531cf32e4" />

AMONG THE SLEEP VR  v0.1.4
==========================
VR mod for "Among the Sleep" (Unity 5.6.6f2, Mono, 32-bit, Direct3D 11) - BepInEx 5 (x86, included).
Own OpenXR bridge (atsxr.dll) - works with Quest Link / Air Link, Virtual Desktop, SteamVR, WMR.

Install
-------
1. Unzip EVERYTHING in this zip into the game folder (next to the game's .exe):
2. -force-d3d11 -force-gfx-direct in lunch options (i didnt have to)
3. Start Quest Link / Virtual Desktop / SteamVR first (it must be the active OpenXR runtime), then the game.

What you get
------------
- You are the toddler: the house in full 3D, head tracked. Head look: where you look is where he looks, walks and
  grabs (the mouse look is replaced by your head). Right stick left / right turns (snap or smooth).
- Right stick click switches FIRST / THIRD person (third person = a camera behind him; distance / height / side in
  the VR settings). Hold the right stick click 1.2 s = re-centre the view.
- A flashlight in your left hand (the game has none): HOLD the left grip 1.7 s to switch it on / off (you feel a
  buzz). Range, beam width, brightness, colour and shadows are in the settings.
- The toddler's own hands follow your controllers ([Hands] in the config / VR settings: reach, angle, bone names).
- Grab / use / throw where your RIGHT controller points (short blue beam), not where you look ([Hands] HandInteract).
- The game's text (crosshair, hints, subtitles) floats in front of your eyes, see-through.
- Menus (main menu, pause, loading, artbook) stand on a screen in the room in front of you: point at it with the
  right controller (blue laser + dot) and pull the right trigger to click.
- The game's controller support doesn't work, so the VR controllers act as KEYBOARD + MOUSE (the game is kept in
  keyboard / mouse mode):

Controls (xbox controls are janky in this game so i use keyboard to quest 3 controllers)
--------
  Left stick ............. W A S D (walk) 
  
  Left stick click ....... Left Shift (sprint)
  
  Right trigger .......... left mouse (grab / use) 
  
  Left trigger ........... right mouse (throw)
  
  Right grip ............. E (lean right)  
  
  Left grip .............. Q   (hold 1.7 s = flashlight)
  
  A ...................... Space (jump / climb)
  
  B ...................... Left Ctrl (crawl)
  
  X ...................... F (teddy) 
  
  Y ...................... Tab (inventory)
  
  Y + X together ......... Esc (pause menu)
  
  Right stick down ....... R (rotate item)
  
  Right stick click ...... 1st / 3rd person 
  
  Hold right stick click . re-centre (do this at main menu to start the game at right height)
  
  Right stick left/right . turn
  
  Hold Y + left stick click 1 s ... VR settings
  
Every key can be changed in the config, [C

CHANGES
-------
v0.1.4
-  Third person: his arms stop following the controllers and play the game's own animation again
-  Third person head: his own head is shown (parts the game hides for the first-person view are shown again) and
-  The crosshair is removed ([Hands] HideCrosshair).
-  The game's interaction icon (grab / open / climb...) floats just left of your right hand
-  Hand beam: as long as the game's reach (or [Hands] BeamLength), stops on what it hits, turns green when there is
-  The toddler's hands follow your controllers (his arms bend to reach them). [Hands] ArmReach sets how far his hands
-  Grab / use / open / throw now aim with the right controller (first person), with a short beam showing where.
  A held object follows your right hand.
-  FIX: words upside down in play (fine in menus): the game's GUI camera text is now kept on the HUD layer instead
  of being drawn in 3D.
-  Fake flashlight in the left hand: hold the left grip 1.7 s.
-  VR settings menu in the headset (hold Y + left stick click).
