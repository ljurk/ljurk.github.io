# fh2 configuration

- All outputs of the fh2 itself are on Midi-channel 1
- All outputs of the first expansion are on Midi-channel 2

## voices

| Voice | Midi-Channel | Midi-Note | Attack | Decay | Sustain | Release | Base-Output | Outputs |
| ----- | ------------ | --------- | ------ | ----- | ------- | ------- | ----------- | ------- |
| 1 | 1 | 0-127 | 1 | 2 | 3 | 4 | 1 | CV;Gate;Velocity;Envelope |
| 2 | 2 | 1 | 1 | 2 | 3 | 4 | 1/1 | Gate;Envelope |
| 3 | 2 | 2 | 5 | 6 | 7 | 8 | 1/3 | Gate;Envelope |
| 4 | 2 | 3 | 9 | 10 | 11 | 12 | 1/5 | Gate;Envelope |
| 5 | 2 | 4 | 13 | 14 | 15 | 16 | 1/7 | Gate;Envelope |

# direct outputs

| Output | Midi-Channel | Midi-CC |
| ------ | ------------ | ------- |
| 5 | 1 | 5 |
| 6 | 1 | 6 |
| 7 | 1 | 7 |
| 8 | 1 | 8 |
