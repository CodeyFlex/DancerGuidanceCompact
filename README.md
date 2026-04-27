Fork of Talox DancerGuidance system, they did most of the work on this system, I just made some small changes and sharing them for anyone who would like them :D

New features:

- "No dances" state.
- Compact design to only keep the counter, and add visibility to the number with the button box for contrast around the number.
- Number becomes visible again despite turning display off and on.
- Bolder font

- OverHeadNumber options for dance count customization.
  - 0 = White
  - 1 - Dances Needed = Green
  - Dances Needed - Dances No Longer Needed = Orange
  - Dances No Longer Needed - Max Dances = Red
  - Max Dances = No Dances Text (Red)
  - Incrementing the counter after reaching "No Dances" state resets the counter.

 <img width="491" height="460" alt="image" src="https://github.com/user-attachments/assets/0e76be5e-4270-40c4-906e-6d39f884fa0c" />

- Offset (Counters position from the player it belongs to): XYZ values (Y increased to 0.6 in this image)
- Click Delay (Seconds in between each dance counter increment): "Number" seconds. (Decreased to 0.1 seconds in this image)
- Keep Alive (How long dance count is persisted): "Number" hours. (Decreased to 3 hours in this image)

<video src="https://github.com/user-attachments/assets/6c091397-97ab-4eee-b08b-82812854dcc0" autoplay loop muted playsinline width="100%"></video>

<video src="https://github.com/user-attachments/assets/00cfe19a-f8e1-4115-86ce-721494abbe0c" autoplay loop muted playsinline width="100%"></video>

-----------------* Original Text from Talox *-----------------

This repo was made at the request of multiple people, and with the release of Persistence, this was made a lot easier to put together. The people at El Diablo (ZAPZARAP and Iferia) helped a great deal with the integration side of things. 

# How to use

1. Add it to the [VCC](https://arne-van-der-lei.github.io/DancerGuidance/)
2. Add the package to your world project
3. Add both the enable button prefab to the scene and place it on a location where your dancers can access it
4. Add the Overhead number to the scene and change any parameters on the udon script to your liking

# How to request a feature

You can poke me on discord here: [discord](https://discord.gg/bJKDe6eEVx)
