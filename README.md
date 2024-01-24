# Boxart-Bezels
Bezels for Powkiddy RGB30

4:3 bezels for Retroarch based on games boxart. I recommend to use sharp-bilinear-2x-prescale shader to avoid uneven pixels in 4:3 systems, it add a little blurines but it's worth it.

# Preview

![preview](https://github.com/Vidnez/Boxart-Bezels/assets/82564218/2b73233a-5322-4ebe-9e83-cb2d8f247697)

# General Instructions (Applying the overlay)

Open 'Quick Menu' on Retroarch (Select + X buttons) > On-Screen Overlay > Overlay Preset > Choose the .cfg file for the system in use. 

# Aligning the overlay for 4:3 systems (not handhelds).

Settings ->

  - Video ->
    
    - Scaling ->
      
      * Integer Scale: OFF
      * Aspect Ratio: Custom
      * X Position: 0
      * Y Position: 50
      * Width: 720
      * Height: 540

# For GB, GBC, GBA, GG, NGP, NGPC (handhelds)

Settings ->

  - Video ->

    - Scaling ->

      - Integer Scale: ON
      - Aspect Ratio: Core provided


# For Wonderswan, Wonderswan Color and Atari Lynx

Settings ->

 - Video ->

   - Scaling ->

     - Integer Scale: OFF
     - Aspect Ratio: Core provided
    
# Saving changes

To save the changes after all the adjustments you need to go to 'Quick menu' > Overrides > Save Content Directory overrides. 

  *This step is per system.

