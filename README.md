# Minicom - Memento
<i>Memento for Minicom, the best way to initialize serial connections on Linux !</i>
__________

### Prerequisite : 

If by default Minicom isn't installed, you can do it via these commands :

```
apt install minicom -y
```
<i>For Debian distributions or</i>
```
yum install minicom -y
```
<i>For RedHat ones</i>w

Of course, to use Minicom you will need an equipment with a serial port like a switch or a router for example. This connection is possible only if you have a serial wire (depends of the equipment and it's brand).

## I - Presentation

So, what is Minicom ? It's a useful package to handle a serial connection on Linux systems between your device and another equipment. It's (most of the time) a direct connection, so the wire is plugged without any intermediate. Minicom is free and open source, and runs under most linux distributions. Finally, it handles the well-known stanrdards like RS-232, RS-485 or RS-422. 

>As I said before, most of the time serial connections need a wire to join directly the PC and the device. But alternatives exist like the Moxa 6150. This kind of equipment permits to join the device via an ethernet connection. So, you don't have do be physically in front of the device especially for reloading it and in this case, Minicom is useless. It only needs a terminal to initialize a telnet/ssh connection.

## II - Minicom configuration

## III - Initialize a serial connection