Listen up everybody!
This EFI configuration was NOT made by me, I actually took this from aleixsr and just configured it from my specific build and updated some kexts to work with macOS Sonoma (latest tested: 14.3.1).
On his repository also thanks everyone involved so I'll link to his repository as well:
https://github.com/aleixsr/MSI-Prestige-15-A10SC-Hackintosh

I've made this repository as a backup for myself honestly, but I do hope that it will help!

 - Remember to generate your SMBIOS info with GenSMBIOS, if you don't know what I'm talking about, check Dortiana's OpenCore Guide.

Known problems:
- No dGPU, Nvidia 1650 Max-Q is not supported by macOS and never will.
- Fingerprint sensor not working, it's not TouchID so it will never work.
- Realtek Card Reader, I've added the kext but nothing, maybe I've messed up something...
- There are some random kernel panics at boot, it doesn't happen always and I can't pinpoint what's causing it... If you find out please keep me updated!

Known problems with Sonoma specifically: iServices don't work with AirportItlwm, no problems with itlwm. 

I will update this README to make it more "beautiful", but for more info check aleixsr's repo, at least for now!
