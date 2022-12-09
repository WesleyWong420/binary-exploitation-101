# Binary Exploitation 101
**[Intro to Binary Exploitation (Pwn) - Practical Buffer Overflow Challenges](https://www.youtube.com/playlist?list=PLHUKi1UlEgOIc07Rfk2Jgb5fZbxDPec94)**

## Setup
**NOTE:** For most of the challenges, set the owner/permissions of the flag + binary (after compiling) to:

<pre>$ gcc vuln.c -o vuln -fno-stack-protector -z execstack -no-pie -m32
$ sudo chown root:root flag.txt
$ sudo chmod 600 flag.txt

$ sudo chown root:root challenge_binary
$ sudo chmod 4655 challenge_binary</pre>

## Additional Resource
**[Deusx64](https://deusx64.ai)**<br>
**[Exploit Education](https://exploit.education)**<br>
**[Pwn.College](https://pwn.college)**<br>
**[ROPEmporium](https://ropemporium.com)**<br>
**[How2Heap](https://github.com/shellphish/how2heap)**<br>
**[NightMare](https://guyinatuxedo.github.io)**<br>
**[Ir0nstone](https://ir0nstone.gitbook.io/notes/types/stack)**<br>
**[PinkDraconian](https://www.youtube.com/playlist?list=PLeSXUd883dhjmKkVXSRgI1nJEZUDzgLf\_)**<br>
**[LiveOverflow](https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)**<br>
**[More](https://github.com/Crypto-Cat/CTF#readme)**
