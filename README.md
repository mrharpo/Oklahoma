# Oklahoma
Production files for El Camino High School's Oklahoma, Spring 2022

*sounds not included, but are available from freesound.org under a CC license*

Plaintext cue list included with [Oklahoma-cues.csv](../blob/main/Oklahoma-cues.csv)

## QLab
- Preshow and intermission soundscapes
  - preshow: birds
  - intermission: crickets
- gunshots
- Mute control
  - Allan and Heath GLD
  - using MIDI `NOTE_ON` events
- Lighting control
  - ETC Eos Ion Xe
  - OSC
- automatic timers
  - for act 1, intermission, act 2
  - using empty MIDI timecode cues
    - pause to hold final value until reset
    - reset with stop or panic
  - preview values in QLab Timecode tab
