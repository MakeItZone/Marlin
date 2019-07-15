# Custom LCD FW

Keep a copy locally.

Sourced from: <https://jgaurorawiki.com/a5/lcd-firmware>

Details from above:

<div class="page group">
                                                            <!-- wikipage start -->
                    <!-- TOC START -->
<div id="dw__toc" class="dw__toc">
<h3 class="toggle closed" style="cursor: pointer;"><strong><span>+</span></strong>Table of Contents</h3>
<div aria-expanded="false" style="display: none;">

<ul class="toc" style="display: none;">
<li class="level1"><div class="li"><a href="#a5-a3s-mks-tft28-lcd-firmware">A5 &amp; A3S MKS-TFT28 LCD firmware</a></div></li>
<li class="level1"><div class="li"><a href="#download-lcd-firmware">Download LCD Firmware</a></div>
<ul class="toc">
<li class="clear">
<ul class="toc">
<li class="level3"><div class="li"><a href="#a5">A5</a></div></li>
<li class="level3"><div class="li"><a href="#a3s">A3S</a></div></li>
<li class="level3"><div class="li"><a href="#how-to-flash">How to Flash</a></div></li>
<li class="level3"><div class="li"><a href="#troubleshooting">Troubleshooting</a></div></li>
</ul>
</li>
<li class="level2"><div class="li"><a href="#further-info-on-mks-tft28-lcd-module">Further Info on MKS-TFT28 LCD module</a></div></li>
</ul></li>
</ul>
</div>
</div>
<!-- TOC END -->

<h1 class="sectionedit1" id="a5-a3s-mks-tft28-lcd-firmware">A5 &amp; A3S MKS-TFT28 LCD firmware</h1>
<div class="level1">

<p>
The A5 and A3S printers have separate main motherboard and LCD modules, and each has their own separate <a href="/a5/firmware" class="wikilink1" title="a5:firmware">firmware</a>. The firmware on the LCD module can be upgraded quite easily. The firmware files must be placed on an SD card, which must be inserted into the hidden slot inside the printer, located on the back side of the LCD module. When the LCD is powered up, it will begin the firmware update automatically.
</p>

<p>
JGAurora do not supply any source code for the LCD module, as they are using a proprietary 3rd party product LCD module made by MakerBase (MKS-TFT28 v1.3). However, the firmware configuration is set by a text file, making it easy to change some of the settings. However, the raw <em class="u">unconfigured</em> LCD firmware is available from the LCD module manufacturer “MakerBase” at <a href="https://github.com/makerbase-mks" class="urlextern" title="https://github.com/makerbase-mks">Github</a>.
</p>

<p>
The custom community LCD firmware is the same as the original JGAurora LCD firmware, with some changes to the configuration. These changes add the “<a href="/a5/babystepping" class="wikilink1" title="a5:babystepping">babystepping</a>” control feature to the LCD module - for more infomation on this feature see <a href="/a5/babystepping" class="wikilink1" title="a5:babystepping">this article on babystepping with the A5</a>. Please note, this feature requires that you have <a href="/a5/firmware" class="wikilink1" title="a5:firmware">upgraded the main motherboard firmware to the community firmware</a>. Thanks to Karl Johnson for the hard work adding baby stepping and other features to the LCD firmware configuration. 
</p>

</div>

<h1 class="sectionedit2" id="download-lcd-firmware">Download LCD Firmware</h1>
<div class="level1">

</div>

<h3 class="sectionedit3" id="a5">A5</h3>
<div class="level3">

<p>
Official Factory LCD Firmware: <a href="https://www.dropbox.com/sh/nwjksul4eulsp95/AAA8y-xkX94OBYXSsjqcptQTa?dl=0" class="urlextern" title="https://www.dropbox.com/sh/nwjksul4eulsp95/AAA8y-xkX94OBYXSsjqcptQTa?dl=0"> A5</a>
</p>

<p>
<strong>Custom Community LCD Firmware: </strong>
</p>
<ul>
<li class="level1"><div class="li"> <a href="https://www.dropbox.com/s/64ogugm1l92ed9c/JG%20A5%20Custom%20LCD%20Firmware%20-%20v3.03.zip?dl=0" class="urlextern" title="https://www.dropbox.com/s/64ogugm1l92ed9c/JG%20A5%20Custom%20LCD%20Firmware%20-%20v3.03.zip?dl=0">V3.03 Custom A5 LCD Firmware (December 2018)</a></div>
</li>
<li class="level1"><div class="li"> <a href="https://www.dropbox.com/s/6wjjd2a7n5ue9yq/JGAurora%20A5%20Custom%20LCD%20firmware%20-%20030718%20Version%20B.zip?dl=0" class="urlextern" title="https://www.dropbox.com/s/6wjjd2a7n5ue9yq/JGAurora%20A5%20Custom%20LCD%20firmware%20-%20030718%20Version%20B.zip?dl=0">V3.01 Custom A5 LCD Firmware (July 2018)</a></div>
</li>
<li class="level1"><div class="li"> <a href="https://www.dropbox.com/s/ccreium22rki3cq/JGAurora%20A5%20Custom%20LCD%20firmware%20-%2020180111.zip?dl=0" class="urlextern" title="https://www.dropbox.com/s/ccreium22rki3cq/JGAurora%20A5%20Custom%20LCD%20firmware%20-%2020180111.zip?dl=0">Old custom A5 LCD firmware here.</a></div>
</li>
</ul>

</div>

<h3 class="sectionedit4" id="a3s">A3S</h3>
<div class="level3">

<p>
Official Factory LCD Firmware: <a href="https://www.dropbox.com/sh/ek7qbnj09xgyi0k/AAALvBVsxNOtY6VrCay6nPtqa?dl=0" class="urlextern" title="https://www.dropbox.com/sh/ek7qbnj09xgyi0k/AAALvBVsxNOtY6VrCay6nPtqa?dl=0">A3S</a>
</p>

<p>
<strong>Custom Community LCD Firmware: </strong>
</p>
<ul>
<li class="level1"><div class="li"> <a href="https://www.dropbox.com/s/9h5hu9jo4acd1tl/JGAurora%20A3S%20Custom%20LCD%20firmware%20-%2020180111%20Version%20B.zip?dl=0" class="urlextern" title="https://www.dropbox.com/s/9h5hu9jo4acd1tl/JGAurora%20A3S%20Custom%20LCD%20firmware%20-%2020180111%20Version%20B.zip?dl=0">Custom A3S LCD Firmware V3.01</a> - Aug 2018: I've updated the homing positions for the A3S custom LCD firmware, in order to make levelling the bed easier. </div>
</li>
<li class="level1"><div class="li"> <a href="https://www.dropbox.com/s/b5z9rjla7fktya1/JG%20A3S%20Custom%20LCD%20firmware%20-%20v3.03.zip?dl=0" class="urlextern" title="https://www.dropbox.com/s/b5z9rjla7fktya1/JG%20A3S%20Custom%20LCD%20firmware%20-%20v3.03.zip?dl=0">Custom A3S LCD Firmware V3.03</a> - Dec 2018: Updated firmware for the A3S LCD module. <a href="https://jgauroraforum.com/discussion/comment/2541" class="urlextern" title="https://jgauroraforum.com/discussion/comment/2541">Discussion</a></div>
</li>
</ul>

</div>

<h3 class="sectionedit5" id="how-to-flash">How to Flash</h3>
<div class="level3">

<p>
The process for upgrading the firmware on the MKS LCD module (MKS-TFT28 v1.3):
</p>
<ol>
<li class="level1"><div class="li"> Copy the firmware files to the root directory on an SD card. This should include the firmware “.bin” file, the folder of icon “bmp_XXX.bin” files, and the configuration “.txt” file.</div>
</li>
<li class="level1"><div class="li"> Turn the printer off</div>
</li>
<li class="level1"><div class="li"> Insert the SD Card into the hidden slot inside the printer, on the back side of the LCD module. You may have to unplug the USB cable that goes to the screen in order to access it.</div>
</li>
<li class="level1"><div class="li"> Turn the printer on</div>
</li>
<li class="level1"><div class="li"> The firmware update will start automatically.</div>
</li>
<li class="level1"><div class="li"> Once the firmware update is complete, the printer will start.</div>
</li>
<li class="level1"><div class="li"> Turn the printer off</div>
</li>
<li class="level1"><div class="li"> Remove the SD card</div>
</li>
<li class="level1"><div class="li"> The files on the SD card will have been renamed, so if you leave the SD card inside and turn the printer on, it will not flash a second time.</div>
</li>
<li class="level1"><div class="li"> Dont forget to plug the internal USB cable in again, if you disconnected it.</div>
</li>
<li class="level1"><div class="li"> After flashing, the LCD may be set to look for files on the SD card only. You need to use the settings menu in the LCD to change this back to USB, otherwise your printer will not see any files when you plug in your USB!</div>
</li>
</ol>

</div>

<h3 class="sectionedit6" id="troubleshooting">Troubleshooting</h3>
<div class="level3">
<ul>
<li class="level1"><div class="li"> If you performed the flash and now the MKS LCD is only flashing “BOOTING” and beeping repeatedly - try flashing again with a different SD card.</div>
</li>
<li class="level1"><div class="li"> If you only see white squares on the LCD, see <a href="https://jgaurorawiki.com/a5/lcd-problem" class="urlextern" title="https://jgaurorawiki.com/a5/lcd-problem">this page</a>.</div>
</li>
<li class="level1"><div class="li"> If you plug in a USB and you don't see any files, check the LCD settings page. There is an option for the LCD to look for files on SD card or on USB sticks. Also check you have plugged in the internal USB cable!</div>
</li>
</ul>

</div>

<h2 class="sectionedit7" id="further-info-on-mks-tft28-lcd-module">Further Info on MKS-TFT28 LCD module</h2>
<div class="level2">

<p>
The following links may be helpful to people interested in making their own changes to the functions and icons of the LCD module.
</p>
<ul>
<li class="level1"><div class="li"> <a href="https://jgauroraforum.com/discussion/76/lcd-firmware-explanation#latest" class="urlextern" title="https://jgauroraforum.com/discussion/76/lcd-firmware-explanation#latest">JGAurora Forum discussion on customising MKS LCD buttons</a></div>
</li>
<li class="level1"><div class="li"> <a href="http://marlinfw.org/docs/gcode/G000-G001.html" class="urlextern" title="http://marlinfw.org/docs/gcode/G000-G001.html">Detail on other GCode commands and their functions</a></div>
</li>
<li class="level1"><div class="li"> <a href="https://jgauroraforum.com/discussion/28/mks-lcd-flashing-firmware-modifications-and-logo-icon-customisation" class="urlextern" title="https://jgauroraforum.com/discussion/28/mks-lcd-flashing-firmware-modifications-and-logo-icon-customisation">Customising LCD icons</a></div>
</li>
<li class="level1"><div class="li"> Various Official MKS-TFT28 LCD Module PDF documentation: <a href="https://www.dropbox.com/s/ztsxgta4idoz47q/MKS-TFT28-32-datasheet.pdf?dl=0" class="urlextern" title="https://www.dropbox.com/s/ztsxgta4idoz47q/MKS-TFT28-32-datasheet.pdf?dl=0">1</a>, <a href="https://www.dropbox.com/s/x63f1yo1qoxyyiz/MKS-TFT32-DataSheet.pdf?dl=0" class="urlextern" title="https://www.dropbox.com/s/x63f1yo1qoxyyiz/MKS-TFT32-DataSheet.pdf?dl=0">2</a>, <a href="https://www.dropbox.com/s/wgud3vaxoh88k5n/MKS-TFT-photo-of-description.pdf?dl=0" class="urlextern" title="https://www.dropbox.com/s/wgud3vaxoh88k5n/MKS-TFT-photo-of-description.pdf?dl=0">3</a></div>
</li>
<li class="level1"><div class="li"> <a href="https://jgauroraforum.com/discussion/comment/891" class="urlextern" title="https://jgauroraforum.com/discussion/comment/891">Error in documentation: custom button 2 was removed!!</a></div>
</li>
</ul>

</div>

                    <!-- wikipage stop -->
                                    </div>