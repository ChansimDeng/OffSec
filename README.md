# PythonPenTest
Python Code for IT Security Tests

This is python code we have collected from many other people, or written ourselves. The scripture from CEH, ECSA, LPT, OSCP, Linux Foundation and Microsoft courses. Credit is always given but if we have missed you out, please email us at admin@arcadeusops.com and we will rectify the error.
We do not offer support for these scripts so if you have an issue running these scripts then work it out yourself or use Dr. Google to get an answer,

REMEMBER: Stay ethical. Don't be a knob. ALWAYS get written permission before attacking a target.


## So, You Want to be a Rock Star?
## Follow instructions, it`s very easy! From the OSCP course!!

```bash
$ git clone https://github.com/jivoi/pentest.git ./offsecfw && cd offsecfw
$ mix_ping_sweep.py 192.168.56.1-254 ./results
$ mix_port_scan.sh -t ./results/targets.txt -p all
$ mix_recon.py ./results/targets.txt
```