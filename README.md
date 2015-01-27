##Lenovo Y580 OSX Installer w/ Clover
**[Yosemite thread](http://www.tonymacx86.com/yosemite-laptop-support/144245-yosemite-10-10-x-lenovo-y580.html#post889883)**

**Maintainer: Jessers123**
  

[![Paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8E4TFKGXLHJLU)
  

OS X support: Yosemite+


###C h a n g e l o g   

**Version 0.9.5 (27 January 2015)**

* DSDT patching fixed
* Bluetooth patching added

**Version 0.9 (25 January 2015)**

* Initial release


###C r e d i t s:

This is based on the **HP ProBook Installer Clover edition** that is currently maintained by **pokenguyen**.  Huge thanks!    
[HP ProBook Installer Clover Edition on Bitbucket](https://bitbucket.org/dhnguyenit/hp-probook-installer-clover-edition)

**Clover Bootloader** is courtesy of the **Clover Team**.  
[The Clover support thread](http://www.projectosx.com/forum/index.php?showtopic=2562)  

The **VoodooPS2Controller** fork is courtesy of **RehabMan**.
[The VoodooPS2Controller support thread](http://www.tonymacx86.com/hp-probook/75649-new-voodoops2controller-keyboard-trackpad.html)  

The SSDT generator script is courtesy of **RevoGirl** and **PikeRAlpha**.  
[The SSDT generator support thread](http://www.tonymacx86.com/ssdt/86906-ssdt-generation-script-ivybridge-pm.html)  

**MaciASL** is courtesy of **SJ_UnderWater** forked by **RehabMan**.  
[The MaciASL support thread](http://www.tonymacx86.com/dsdt/83565-native-dsdt-aml-ide-compiler-maciasl-open-beta.html)  

**GenericUSBXHCI.kext** is courtesy of **Zenith432** and **RehabMan**.  
**RealtekRTL8111.kext** is courtesy of **Mieze** and **RehabMan**.  
[The main support thread](http://www.tonymacx86.com/hp-probook/93732-new-kexts-proposed-probook-installer-v6-1-a.html)  
[The original GenericUSBXHCI.kext support thread](http://www.insanelymac.com/forum/topic/286860-genericusbxhci-usb-30-driver-for-os-x-with-source/)  
[The original RealtekRTL8111.kext support thread](http://www.insanelymac.com/forum/topic/287161-new-driver-for-realtek-rtl8111/)  

The AHCI patch, **patch-hda.pl** and **patch-hda-codecs.pl** are courtesy of **bcc9**.  
[The AHCI patch support thread](http://www.insanelymac.com/forum/topic/280062-waiting-for-root-device-when-kernel-cache-used-only-with-some-disks-fix/)  
[The AppleHDA patch support thread](http://www.insanelymac.com/forum/topic/284004-script-to-patch-applehda-binary-for-osx107108/)  

**Kext Wizard** is courtesy of **janek202**.   
[The Kext Wizard support thread](http://www.insanelymac.com/forum/topic/253395-kext-wizard-easy-to-use-kext-installer-and-more/)  

**FakeSMC** is courtesy of **RehabMan**, **kozlek**, **netkas**, **slice** and **navi**.  
[The main support thread](http://www.tonymacx86.com/hp-probook/)  
[The original support thread](http://www.insanelymac.com/forum/topic/275429-hwsensors/)  

**Trim Enabler** is courtesy of **Cindori**.  
[The Trim Enabler support forums](http://www.groths.org/forums/)  

**AICPMPatch.pl** is courtesy of **el coniglio** with modifications by **RehabMan**.  
[The original support thread](http://olarila.com/forum/viewtopic.php?f=9&t=1003&sid=d6df188c360c6a74d9b788ae9568df84)   

The unified **AppleIntelFramebufferCapri.kext** patch is courtesy of **kpkp**.  
[The original support thread](http://www.tonymacx86.com/hp-probook/99533-testers-ivy-probooks-needed.html)    

**EAPDFix.kext** is courtesy of **EMlyDinEsH**    
[The EAPDFix support forum](http://forum.osxlatitude.com/index.php?/topic/3084-eapdjack-sense-fix-no-audiojack-sense-issue-after-sleep/)

**ALXEthernet.kext** is courtsey of **Shailua**   
[The ALXEthernet support thread](http://www.insanelymac.com/forum/topic/284119-experimental-atheros-ar813132515261627172-driver-for-107108/)

**ACPIPoller.kext** and the fan reset driver for Clover are courtesy of **RehabMan**.  
The **patchmatic** utility by **RehabMan** is based of the **MaciASL** source code and uses **RegexKitLite** by **John Engelhart**.  
The **DSDT generator/patcher** is courtesy of **RehabMan**, **BigDonkey** and **philip_petev**.  
The **EDID generator** is courtesy of **philip_petev**.  
The 3rd party AHCI kext is courtesy of **MacMan**.  
The colour profiles are courtesy of **metacollin** and several other sources.  
The **display_color.py** script is courtesy of **Daniel Fairhead (danthedeckie)**.  

###Special thanks to:

**pokenguyen** - The current maintainer of the HP ProBook Installer Clover edition.
**BlueKing** - the original creator of HP ProBook Installer.  
**Tegezee** - the second maintainer of HP ProBook Installer.  
**philippetev** - the current maintainer of HP ProBook Installer.  
**RehabMan** - For helping everyone nicely in the forum threads and providing handy tools and kexts. 
###and all the other users of the Lenovo Y580 forum.


**RegexKitLite** Copyright © 2008-2010, **John Engelhart**  
All rights reserved.  
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:  
Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.  
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.  
Neither the name of the Zang Industries nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.  
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.