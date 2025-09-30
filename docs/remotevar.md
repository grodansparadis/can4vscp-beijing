

A VSCP unit is describing it's configuration to the world with a
register model where each register is eight bit in width. This is often
inconvenient for a human user who is used to higher level types and this
is what *abstractions* are there for. They sit above registers and
specify types as strings, floats, integers and other such higher level
types.

## Pulse times

This is the pulse time for outputs expressed in seconds. It can be used to have an output turn on and off with a certain preset interval. The min. pulse time is 1 second and the max time is 65535 seconds which is about 18 hours. Set to zero (default) for no pulse time i.e. the output will be steady on/off.

To start a pulse sequence first write the pulse time to this register and then write to output status register to start the output sequence. The pulse train is terminated by writing on or off (1 or 0) to the output status register.
| Name        | Type      | Description                     |
| ----------- | --------- | ------------------------------- |
| Output pulse time register for channel 0 | short | Pulse time in seconds for channel 0 |
| Output pulse time register for channel 1 | short | Pulse time in seconds for channel 1 |
| Output pulse time register for channel 2 | short | Pulse time in seconds for channel 2 |
| Output pulse time register for channel 3 | short | Pulse time in seconds for channel 3 |
| Output pulse time register for channel 4 | short | Pulse time in seconds for channel 4 |
| Output pulse time register for channel 5 | short | Pulse time in seconds for channel 5 |
| Output pulse time register for channel 6 | short | Pulse time in seconds for channel 6 |
| Output pulse time register for channel 7 | short | Pulse time in seconds for channel 7 |  
| Output pulse time register for channel 8 | short | Pulse time in seconds for channel 8 |
| Output pulse time register for channel 9 | short | Pulse time in seconds for channel 9 |


## Protection times

This is the output protection times. A output will be inactivated if not written to before this time has elapsed. Set to zero to disable (default). The max time is 65535 seconds which is about 18 hours.

The registers can be as an example be used as a security feature to ensure that an output is deactivated after a preset time even if the controlling device failed to deactivate the output.
| Name        | Type      | Description                     |
| ----------- | --------- | ------------------------------- |
| Output protection time register for channel 0 | short | Protection time in seconds for channel 0 |
| Output protection time register for channel 1 | short | Protection time in seconds for channel 1 |
| Output protection time register for channel 2 | short | Protection time in seconds for channel 2 |
| Output protection time register for channel 3 | short | Protection time in seconds for channel 3 |
| Output protection time register for channel 4 | short | Protection time in seconds for channel 4 |
| Output protection time register for channel 5 | short | Protection time in seconds for channel 5 |
| Output protection time register for channel 6 | short | | Protection time in seconds for channel 6 |
| Output protection time register for channel 7 | short | Protection time in seconds for channel 7 |  
| Output protection time register for channel 8 | short | Protection time in seconds for channel 8 |
| Output protection time register for channel 9 | short | Protection time in seconds for channel 9 |

  
[filename](./bottom-copyright.md ':include')