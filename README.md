##Lenovo Y580 OSX Installer w/ Clover
###**[Downloads](https://github.com/MegaCookie/Lenovo-Y580-OSX-Installer-Clover/releases)**  

**Maintainer: MegaCookie (Jessers123)**  
**[Lenovo Y580 El Capitan support thread](http://www.tonymacx86.com/el-capitan-laptop-guides/175993-guide-lenovo-y580-el-capitan-10-11-using-clover-uefi.html)**  
**[Lenovo Y580 Yosemite support thread](http://www.tonymacx86.com/yosemite-laptop-support/144245-yosemite-10-10-x-lenovo-y580.html#post889883)**

[![Paypal](https://jessevandervelden.nl/donate.png)](https://www.paypal.me/JessevanderVelden)


OS X support: El Capitan, Yosemite

###C h a n g e l o g   

**Version 1.5.3 (April 15, 2016)**  
* Fixed Trackpad issues and updated Voodoops2controller.kext

**Version 1.5.2 (April 17, 2016)**

* Finally DSDT patching is working without problems!
* Updated MaciASL (and some binaries used for DSDT/ SSDT Patching)
* Updated Clover Configurator
* Added the new Windows logo in the default Clover theme
* Removed XtraFinder (still can be found [here](https://www.trankynam.com/xtrafinder/))
* Removed HWMonitor (still can be found [here](http://hwsensors.com/))


**Version 1.5.1 (April 16, 2016)**

* Fixed DSDT patching problems
* Updated Clover to r3484
* Use of AtherosE2200Ethernet.kext instead of ALXEthernet.kext

**Version 1.5 (3 April 2016)**

* Fixed audio in 10.11.4 (DummyHDA.kext)
* Updated Clover to r3389
* Updated BrcmPatchRam.kext
* Updated ACPIBatteryManager.kext
* Updated Voodoops2controller.kext

**Version 1.4 (28 November 2015)**

* Fixed Sleep problems

**Version 1.3.1 (22 October 2015)**

* Some Clover.config Generate fixes
* Bluetooth fixes

**Version 1.3 (18 October 2015) - 10.11 update**

* Clover.config Generate is now 10.11 ready!
* Some brightness DSDT fixes
* Clover update to 3277
* Updated BrcmPatchRam
* Updated ACPIBacklight.kext
* Updated ACPIBatteryManager.kext
* Updated VoodooPS2Controller.kext
* Removed GenericUSBXHCI.kext for 10.11

**Version 1.2 (29 August 2015)**

* Some small DSDT fixes (try them by pressing F4 in the Clover Menu, then patch DSDT again)
* Clover update to 3261
* Updated SSDT Prgen to 15.9
* Updated BrcmPatchRam + BrcmBluetoothInjector
* Updated ACPIBacklight.kext
* Updated XtraFinder & Clover Configurator
* Updated Clover config.plist generating with HDMI fixes and some 10.11 stuff.
* OMT: HDMI Audio finally works too!


**Version 1.1 (5 July 2015)**

* Updated FakeSMC.kext, VoodooPS2Controller.kext, BrcmPatchRam.kext (with the new BrcmBluetoothInjector.kext)
* Clover updated to r3242
* Updated Clover Configurator & XtraFinder
* Added some boot arguments for USB fixes (and 10.11)
* Fixed Board serial bug when generating Clover's Config.plist (iMessage finally working)
* Sound patching in Clover's config.plist & common kexts isn't a choice anymore, it will be patched automatically
* Changed second stage patch for supporting new OS X versions when generating Clover's config.plist
* Some early 10.11 support

**Version 1.0 (11 April 2015)**

* Support for 10.10.3 by removing Second Stage Patch when generating Clover config.plist

**Version 0.9.9.0 (22 March 2015)**

* Updated and fixed SSDTPRGen.sh (v15.6)
* Updated FakeSMC.kext
* Clover 3192 -> 3193

**Version 0.9.8.2 (15 March 2015)**

* Fixed adding Clover's ACPI folders
* Updated Clover to r3193 & Clover Configurator to 4.22.5

**Version 0.9.8.1 (28 February 2015)**

* Added modified BrcmPatchRAM.kext courtsey of the-darkvoid
* Change the Bluetooth injector names within Y580ARPT.kext (Cosmetic change only)

**Version 0.9.8.0 (27 February 2015)**

* New Bluetooth patch on the fly by using a slightly modified ProBookARPT.kext.  
 Patching won't be needed again after an OS X update!
* Updated Clover to r3167 and Clover Configurator
* Enabled USB fixes again within Clover's config.plist

**Version 0.9.7.1 (1 February 2015)**

* Updated Bluetooth Patch with additional id's

**Version 0.9.7 (1 February 2015)**

* Fixed Sound (AppleHDA) patching
* Updated Clover to r3142
* Updated Clover config.plist generate (10.10.2 fixes)
* Updated Extra Tools

**Version 0.9.5 (27 January 2015)**

* DSDT patching fixed
* Bluetooth patching added

**Version 0.9 (25 January 2015)**

* Initial release

###C r e d i t s

This is based on the **HP ProBook Installer Clover edition** that is currently maintained by **pokenguyen - nguyenmac (dhnguyenit)**.  Huge thanks!    
[HP ProBook Installer Clover Edition on Bitbucket](https://bitbucket.org/dhnguyenit/hp-probook-installer-clover-edition)

**Clover Bootloader** is courtesy of the **Clover Team**.  
[The Clover support thread](http://www.insanelymac.com/forum/topic/284656-clover-general-discussion/)  
[Clover on SourceForge](https://sourceforge.net/projects/cloverefiboot)

The **VoodooPS2Controller** fork is courtesy of **RehabMan**.  
[The VoodooPS2Controller support thread](http://www.tonymacx86.com/hp-probook/75649-new-voodoops2controller-keyboard-trackpad.html)  
[VoodooPS2Controller on Github](https://github.com/RehabMan/OS-X-Voodoo-PS2-Controller)  

The **SSDT generator script** is courtesy of **RevoGirl †** and currently maintend by **PikeRAlpha**.  
[The SSDT generator support thread](http://www.tonymacx86.com/ssdt/86906-ssdt-generation-script-ivybridge-pm.html)  
[SSDT PRGen on Github](https://github.com/Piker-Alpha/ssdtPRGen.sh)

**MaciASL/ patchmatic** is courtesy of **SJ_UnderWater** forked by **RehabMan**.  
[The MaciASL support thread](http://www.tonymacx86.com/dsdt/83565-native-dsdt-aml-ide-compiler-maciasl-open-beta.html)  
[MaciASL (RehabMan) on Github](https://github.com/RehabMan/OS-X-MaciASL-patchmatic)     

**iasl binary** is courtesy of **Intel** with changes by **RehabMan**  
[iasl (RehabMan) on Github](https://github.com/RehabMan/Intel-iasl)

**GenericUSBXHCI.kext** is courtesy of **Zenith432** and **RehabMan**.  
[The main support thread](http://www.tonymacx86.com/hp-probook/93732-new-kexts-proposed-probook-installer-v6-1-a.html)  
[The original GenericUSBXHCI.kext support thread](http://www.insanelymac.com/forum/topic/286860-genericusbxhci-usb-30-driver-for-os-x-with-source/)

**ACPIBacklight** is courtesy of **hotKoffy** and modified by **RehabMan**  
[ACPIBacklight modified by RehabMan on Github](https://github.com/RehabMan/OS-X-ACPI-Backlight)

**ACPIBatteryManager** is modified by **RehabMan**  
[ACPIBatteryManager modified by RehabMan on Github](https://github.com/RehabMan/OS-X-ACPI-Battery-Driver)

The **AHCI patch**, **patch-hda.pl** and **patch-hda-codecs.pl** are courtesy of **bcc9**.  
[The AHCI patch support thread](http://www.insanelymac.com/forum/topic/280062-waiting-for-root-device-when-kernel-cache-used-only-with-some-disks-fix/)  
[The AppleHDA patch support thread](http://www.insanelymac.com/forum/topic/284004-script-to-patch-applehda-binary-for-osx107108/)  

**Kext Wizard** is courtesy of **janek202**.   
[The Kext Wizard support thread](http://www.insanelymac.com/forum/topic/253395-kext-wizard-easy-to-use-kext-installer-and-more/)  

**Clover Configurator** is courtesy of **mackie100**  
[Clover Configurator website](http://mackie100projects.altervista.org/clover-configurator/)  

**FakeSMC** is courtesy of **RehabMan**, **kozlek**, **netkas**, **slice** and **navi**.  
[The main support thread](http://www.tonymacx86.com/hp-probook/)  
[The original support thread](http://www.insanelymac.com/forum/topic/275429-hwsensors/)  
[RehabMan's FakeSMC on Github](https://github.com/RehabMan/OS-X-FakeSMC-kozlek)  

**Trim Enabler** is courtesy of **Cindori**.  
[The Trim Enabler support forums](http://www.groths.org/forums/)  

**AICPMPatch.pl** is courtesy of **el coniglio** with modifications by **RehabMan**.  
[The original support thread](http://olarila.com/forum/viewtopic.php?f=9&t=1003&sid=d6df188c360c6a74d9b788ae9568df84)   

The unified **AppleIntelFramebufferCapri.kext** patch is courtesy of **kpkp**.  
[The original support thread](http://www.tonymacx86.com/hp-probook/99533-testers-ivy-probooks-needed.html)    

**EAPDFix.kext** is courtesy of **EMlyDinEsH**    
[The EAPDFix support forum](http://forum.osxlatitude.com/index.php?/topic/3084-eapdjack-sense-fix-no-audiojack-sense-issue-after-sleep/)

**AtherosE2200Ethernet.kext** is courtsey of **Mieze**  
[The AtherosE2200Ethernet support thread](http://www.insanelymac.com/forum/topic/300056-solution-for-qualcomm-atheros-ar816x-ar817x-and-killer-e220x/)  
[AtherosE2200Ethernet on Github](https://github.com/Dolnor/OSX-ALXEthernet)

**BrcmPatchRAM.kext** is courtsey of **the-darkvoid** and forked by **Rehabman**  
[BrcmPatchRam on Github](https://github.com/the-darkvoid/BrcmPatchRAM)  
[Rehabman's fork on Github](https://github.com/RehabMan/OS-X-BrcmPatchRAM)

**ACPIPoller.kext** and the fan reset driver for Clover are courtesy of **RehabMan**.  
The **patchmatic** utility by **RehabMan** is based of the **MaciASL** source code and uses **RegexKitLite** by **John Engelhart**.  
The **DSDT generator/patcher** is courtesy of **RehabMan**, **BigDonkey** and **philip_petev**.  
The **EDID generator** is courtesy of **philip_petev**.  
The **3rd party AHCI kext** is courtesy of **MacMan**.  
The **colour profiles** are courtesy of **metacollin** and several other sources.  
The **display_color.py** script is courtesy of **Daniel Fairhead (danthedeckie)**.  
The **[Patching AppleHDA](http://www.insanelymac.com/forum/topic/298027-guide-aio-guides-for-hackintosh/page-2#entry2030060) on the fly with Clover** is implemented by the idea of **pokenguyen**  
**Y580ARPT.kext** is the slightly edited **ProBookARPT.kext** is the work of **nguyenmac** and modified by **MegaCookie (Jessers123)** which is based on works, courtesy of **toleda** and **RehabMan**.

###Special thanks to:

**pokenguyen** - The current maintainer of the HP ProBook Installer Clover edition and for his ARPT.kext idea.  
**BlueKing** - the original creator of HP ProBook Installer.  
**Tegezee** - the second maintainer of HP ProBook Installer.  
**philippetev** - the current maintainer of HP ProBook Installer.  
**RehabMan** - For helping everyone nicely in the forum threads and providing handy tools and kexts.
###and all the users of the Lenovo Y580 forum.


**RegexKitLite** Copyright © 2008-2010, **John Engelhart**  
All rights reserved.  
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:  
Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.  
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.  
Neither the name of the Zang Industries nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.  
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
