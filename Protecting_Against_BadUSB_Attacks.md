###Protecting Against Bad USB Attacks

1)Proposal of a trust management scheme, namely TMSUI[1].
This allows the connection of USB devices only on certain protected terminals and 
only for specific amounts of time[1].

2)Introduction of architecture for fine grained provenance collection and tracking
on smart USB devices. This allows the use of pre approved USB drives only[1].

3)Incorporating the user into the line of defence. For example using software like
USBWall in order to enumerate devices on behalf of the operating system. The user
is asked whether the newly connected device should be removed from the system or 
if it is safe for further use[1].

4)Using a USB port blocker[2]
USB port blockers can be installed on crucial systems in a network that contains
sensitive files and come with a special key that unlocks and locks the device
once installed[2].

5)Using special devices to monitor typing speed[2]
BadUSB devices type at speeds that are practically impossible for humans to type at.
These programs detect these abnormal speeds and effectively blocks keyboard input[2].

6)Restricting access to elevated CommandPrompt[2]
The keystrokes for gaining access to CommandPrompt and running commands as an
administrator can esily be programed into a badUSB[2].

References:
1)Neuner, S., Voyiatzis, A.G., Fotopoulos, S., Mulliner, C., Weippl, E.R. (2018). USBlock:
Blocking USB-Based Keypress Injection Attacks. In: Kerschbaum, F., Paraboschi, S. (eds) Data
and Applications Security and Privacy XXXII. DBSec 2018. Lecture Notes in Computer Science(), 
vol 10980. Springer, Cham. https://doi.org/10.1007/978-3-319-95729-6_18

2)communications@manageengine.com ManageEngine, “BADUSB attack prevention,” What is BadUSB | How
to Protect Against BadUSB Attacks - ManageEngine Device Control Plus, Mar-2022. [Online]. Available: 
https://www.manageengine.com/device-control/badusb.html. [Accessed: Dec-2022]. 
