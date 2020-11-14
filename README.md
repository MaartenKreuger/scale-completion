# scale-completion
Spectrum Scale bash command line completion

written for Scale version 5.0.4+, will mostly work for older versions too.

this project contains one completion file for each gpfs command, and one general functions file. 
Where possible options are filled in with valid responses or GPFS objects

All files should be copied to the /etc/bash_completion.d folder:
git clone https://github.com/MaartenKreuger/scale-completion
cp scale-completion/* /etc/bash_completion.d
