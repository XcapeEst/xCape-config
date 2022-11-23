# xCape's TF2 config

### **Heads up!**
*This config is* ***VERY*** *personalized and competitive-oriented, there are probably a lot of settings and changes you need to adjust to or change yourself inside the config file!*

*I suggest using this config along with my hud, cHUD!*

I'm going to try adding as many explanations to each command as I can to give users the ability to create configs to their taste much easier!
You can edit the xcape-config.cfg however much you want to; but keep in mind that you can't change settings from the in-game menu.

Also, if you wish to help me, you can suggest edits anytime, if you run into issues, let me know.
You can also help me write blurbs. Any help is warmly welcomed!

I'm updating this config quite often with new commands and info, so if you want to be up to date, watch and give me a star!

## Changes

- Adds crosshairs that change their style depending on whether you are using primary, secondary or melee weapons!

- Adds a few killsounds which you can choose from. These hit and killsounds have comments in the metadata, which describe the sound origin.

- Removes domination sounds.

- Removes damage particles.

- Removes explosion particles.

- Removes pyroland.

- Uses Madness Combat death killsound.

- Default viewmodel FOV is set to 110 inside the class_default.cfg to reset it after the medigun sets it to 180.

- Class config changes
  - Spy
    - Binds
      - R - Use last disguise (uses a sound cue)
      - V - Undisguise (uses a sound cue)
  - Medic
    - For medic, I'm using a competitive script to easily switch between load-outs or to respawn with my uber intact.
  
	  This is optional, if you don't touch the F1-F3 keys, you'll be fine playing as medic.

	  Set your load-outs like this:  

		  A: Medigun default
		  B: Kritz default
		  C: Medigun with DIFFERENT hat\misc\non-strange compared to A
		  D: Kritz with DIFFERENT hat\misc\non-strange compared to B
    - The mediguns and their beam are invisible
    - Binds
  	  - R - Fake uber (also sends *>> FAKED CHARGE <<* message in team chat)
  	  - E - Call for medic (also shows nearby teammates medic bubbles through the wall)
	  - F - Swap vaccinator resistance
  	  - F1 - Respawn with the same medigun
  	  - F2 - Swap between kritz and uber (if configured correctly as shown below) 
  	  - F3 - Respawn with the same loadout (backup used when the connection to the loadout servers is lost)
  	  - Mouse2 - Use ubercharge (also drops the flag and sends *>> CHARGE USED <<* message in team chat)