# DanceDongle - A USB to FTDI to RS-485 + Next for the Disco Dance Floor

A simple little PCB with two main components, an FTDI USB to ttl-232 converter and
a ttl-232 to RS-485 converter, and the RJ-45 connector for the DiscoDanceFloor project.

## Connected channels

### FTDI PWREN - 485 Read Enable
Enabled the 485 receiver when the FTDI is on

### FTDI TXDEN - 485 Drive Enable
Enable the 485 transmitter whenever bytes are sent

### FTDI RTS(out) - RJ-45 Next
Use RTS to assert (hold low) the Next line

### FTDI CTS(in)  - RJ-45 Next
Use CTS to detect asserted line

### FTDI DSR/DCD - RJ-45 Detect
If a slave is connected to the RJ-45, it will pull these lines low.
