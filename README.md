This repository contains my personally constructed voice packs for use with the [Sonic '06 Randomiser Suite](https://github.com/Knuxfan24/Sonic-06-Randomiser-Suite).

# How Voice Packs Work
Most of the special handling of Voice Packs is done through the Randomiser itself. The actual packs themselves are standard ZIP files (my ones are created through 7-Zip's context menu in Windows Explorer) and should be structed as followed:

- Zip File
  - A folder with the **SAME NAME** as the ZIP file.
    - All your custom XMA files.
	- An MST called messageTable.mst that contains the subtitle entries.
	
The sound placeholder entries in your messageTable.mst file should have the same names as the XMAs they are trying to reference, as the sounds get added to voice_all_e.sbk by their name, which is what thes placeholder value is looking for.