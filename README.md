# Video tutorial series to go with the "Binary Exploitation 101 Course" AKA "Practical Buffer Overflow Exploitation"
**[Intro to Binary Exploitation (Pwn) - Practical Buffer Overflow Challenges (for beginners) 😺](https://www.youtube.com/watch?v=wa3sMSdLyHw&list=PLHUKi1UlEgOIc07Rfk2Jgb5fZbxDPec94)**

# Note: For most of these challenges, you will want to set owner/permissions of the flag + binary (after compiling):

<pre>gcc vuln.c -o vuln -fno-stack-protector -z execstack -no-pie -m32

sudo chown root:root flag.txt
sudo chmod 600 flag.txt

sudo chown root:root challenge_binary
sudo chmod 4655 challenge_binary</pre>

# Additional resources for learning Pwn
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