<span align="center">
<h1>AMD Vanilla OpenCore Bootloader</h1>
</span>

Kernel binary patches to enable almost native AMD CPU support on macOS.

### Features
- Enables macOS to run on AMD CPUs on the fly.
- Enables iMessage, Siri, FaceTime, Continuity etc.
- Stable compared to custom XNU kernel.

### Disadvantages
- No 32-bit support (OPEMU) in 10.14 and lower

### Supported Nativ for
| Product | Codename| Example |
|--------|---------|----------|
| CPU | ZEN | R5 1500
| GPU | Polaris| RX 580 4GB

### Supported macOS versions
- High Sierra 10.13.x
- Mojave 10.14.x
- Catalina 10.15.x (used current)

### Instructions
- Download gibmacOS and Download with -R Catalina 10.15.4
- Create USB Installer with gibmacOS and select OpenCore
- Download for my repo and paste in the EFI/OC and follow the docs


### Special Notes
- These patches require OpenCore 0.5.7 and above. 
- For support creating OpenCore config read the docs[this](https://desktop.dortania.ml/).

### Credits
- [AlGrey](https://github.com/AlGreyy) for the idea and creating the patches.
- [XLNC](https://github.com/XLNCs) for maintaining patches to various macOS versions.
- Sinetek, Andy Vandijck, spakk, Bronya, Tora Chi Yo, Shaneee and many others for sharing their AMD/XNU kernel knowledge
- [0xD81CF](https://github.com/0xD81CF), [doesprintfwork](https://github.com/doesprintfwork) and [erikjara](https://github.com/erikjara) for readme translations.
- [Shaneee](https://github.com/AMD-OSX/AMD_Vanilla) For CPU Patch :)