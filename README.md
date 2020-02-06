# CPS-Project-Proposal

## Design Vision
By the end of the semester, I would like to develop a web VR environment with digital instruments that can be interacted with using the Oculus Quest controllers. The minimum design would be to have single objects that trigger sound when touched by virtual hands. Ideally I would like to add more interactivity to the digital instruments, such as manipulation of the sound using the joystick or other buttons on the controllers, as well as the ability to walk around the environment and hear changes in the volume of instruments depending on how close the user is to each instrument.

In addition, it would be interesting to have a musical back-track that could be manipulated or played on top of using the digital instruments.

I would like to make this VR experience accessible via the web so that it can be accessed by anyone with a phone and cardboard headset, or a all-in-one VR headset such as the Oculus or Vive.

## Components
- Oculus Quest
- Oculus Controllers
- Oculus Browser
- Web app, hosted on GitHub or Glitch

## System
Data:
- Instruments - 3D object files
- Sounds
- Backing-track

Render:
- VR environment is created
- Instruments are rendered in VR environment

Simulation:
- Possibly have visuals that are generated according to sounds

Events:
- Instrument interactions trigger sounds
     - Strum strings
     - Hit drum
     - Tap keys

## Difficulties
- Adding interactivity using the Oculus Quest controllers.
     - If I don't first understand how long this will take, this could end up taking too much time.
- Creating synthesized sounds if I decide to do that instead of simply playing audio tracks.
     - If it looks like I'll be able to research this, I will incorporate it. Otherwise they will simply trigger audio files.
     
## Timeline
February 4 - March 5
- Research and prototype placing objects in VR space, changing the VR environment, adding interactivity using the Oculus Quest controllers or hand-tracking.

March 5 - End
- Implement by creating the final environment, instrumental objects, and interactivity.
