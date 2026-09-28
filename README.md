# GalneoScreen Infrared Remote for Wende interaktiv Whiteboards

An infrared (IR) remote-control file for GalneoScreen setups using Wende interaktiv whiteboards. It contains power-on and power-off commands in the `.ir` format.

## Commands

| Button | Protocol | Address | Command |
| --- | --- | --- | --- |
| Power on | NEC | `38 00 00 00` | `1C 00 00 00` |
| Power off | RC5 | `00 00 00 00` | `0C 00 00 00` |

## Use

Load [`galneo.ir`](galneo.ir) into an infrared remote-control device or application that supports the Flipper Zero `.ir` file format, then send the power command to the whiteboard.

This project is for anyone looking for a GalneoScreen or Wende interaktiv whiteboard infrared remote, IR power control, or NEC and RC5 remote commands. The file contains only the two commands listed above.
