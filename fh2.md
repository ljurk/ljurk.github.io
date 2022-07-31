# fh2 configuration

- All outputs of the fh2 itself are on Midi-channel 1
- All outputs of the first expansion are on Midi-channel 2

## voices

| Voice | Midi-Channel | Midi-Note | Attack | Decay | Sustain | Release | Base-Output | Outputs                   |
| ----- | ------------ | --------- | ------ | ----- | ------- | ------- | ----------- | -------                   |
| 1     | 1            | 0-127     | 1      | 2     | 3       | 4       | 1           | CV;Gate;Velocity;Envelope |
| 2     | 2            | 36        | 1      | 2     | 3       | 4       | 1/1         | Gate;Envelope             |
| 3     | 2            | 37        | 5      | 6     | 7       | 8       | 1/3         | Gate;Envelope             |
| 4     | 2            | 38        | 9      | 10    | 11      | 12      | 1/5         | Gate;Envelope             |
| 5     | 2            | 39        | 13     | 14    | 15      | 16      | 1/7         | Gate;Envelope             |

# LFOs

Outputs:

- 5
- 6
- 7
- 8

The Output Number corresponds to the midi-channel (Output 5 = midi-channel 5). The CC-Values on each channel are the same:

| Parameter      | CC |
| ---------      | -- |
| Direct Control | 1  |
| Base           | 2  |
| Multiplier     | 3  |
| LFO Level      | 4  |
| Sine           | 5  |
| Square         | 6  |
| PW             | 7  |
| Triangle       | 8  |
| Saw            | 9  |
| Random         | 10 |
| Noise          | 11 |
| Phase          | 12 |
| Fade           | 13 |
| Smoothing      | 14 |
