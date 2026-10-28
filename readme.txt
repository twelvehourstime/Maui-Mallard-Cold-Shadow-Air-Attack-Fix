Fix:
The game ignored an attacks pressed on the exact moment Maui reaches the top of a jump. On that one tick the game switches to "falling" and skips its attack check. This fix patches the game in memory so the attack check still runs on that tick. 

Steam Version:
How to install:
Drag both winmm.dll & winmm_ogg.dll into the root of the coldshdw.exe folder.

Details:
winmm.dll contains the fix
winmm_ogg.dll is the original dll renamed, this is still required as winmm.dll calls this .dll file for its audio wrapping.
To uninstall, delete `winmm.dll` and rename `winmm_ogg.dll` back to `winmm.dll`.

Windows 95 / 98 Version:
Overwrite the COLDSHDW.EXE file with the one provided.
