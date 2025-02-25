# **Guides**

This page holds a few Guides to cover specific features not normally possible with Minolta cameras. Please see the respective section for the original source(s) of the information.

### **Disclaimer** 

*Some of these guides deal with DIY modifications, and software/firmware updates of cameras. **These can damage equipment permanently without being careful and following instructions**! 

*This information is offered on the assumption that you already have some experience fixing cameras and are confident in your abilities to not cause further damage to your gear. As such, the authors of the links and the Minoltapedia are not responsible for any damages, injury, or expenses in repairs caused by following advice linked below unprepared.*

As a side note, I strongly recommend reading and taking the Learn Camera repairs' [Camera Repair Course](https://learncamerarepair.com/productlist.php?category=1) offered **before attempting any repairs** if you are not familiar with fixing cameras or lenses.

## Camera Guides

***

### **How to Date-Check A Minolta Camera**

Placeholder - Open the Baseplate and you will see a Number and Letter Code.

The Number represents the last year of a certain decade, i.e. '6' could be 1966, '76, '86... So you'll need to know the Series' production ranges to narrow it down.

| ***Series*** | SR, >1962* | SRT | XK/XM/X1** | XE | XD |  XG | X-700 | X-500 | X-300*** | X-300s/370n*** |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| ***Year Range*** | 1958-1971 | 1966-1981 | 1972-1984 | 1974-1977 | 1977-1981 | 1977-1984 | 1981-2001 | 1983~1985 | 1984~2006 | 1990-2006 |

\*\* The XK has an additional number code - 1 = Made for Japan, 2 = Made for EU, 3 = Made for US. It's redundant though as the model name also tells you this.

\*\*\* The X-300 and X-300s were licensed to Seagull in China in 2005, where they continue to be made today under the Seagull DF300 name. It is unclear if they continue the date-code system beyond then.

The Letter represents the month it was produced. 
  
| ***Letter*** | A | B | C | D | E | F | G | H | I | J | K | L |
|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
|***\# of Month*** | 1 | 2| 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| ***Month*** | January | February | March | April | May | June | July | August | September | October | November | December |


\* The SR series was a first for Minolta, and didn't follow the date-code system in the same way until the early 60's. 

*Placeholder* Cite Hachi, RokkorFiles

> Under the base cover, there is a stamp in the case metal. That is the base code. Under the mount cowl, the is a stamp in the metal of the mount/mirror housing. That is the mount code. 
> 
> Base Code/Mount Code.
> 
> SR-2(1) - None/None
> 
> SR-2(2a) - SR2/None
> 
> SR-2(2b), SR-1(1) - SR2/SRB
> 
> SR-3(1a), SR-1(2a) - SRC/SRC
> 
> SR-3(1b), SR-1(2b) - SRC./SRC
> 
> SR-3(2a), SR-1(3) - SRD/SRC
> 
> SR-1(4a) - SRD/SRC (Minolta added the meter mount to the SR-1(3)

***

### **How to Upgrade a Minolta Alpha/Dynax/Maxxum 9 Camera to a 9Ti**

You may have heard of the Alpha 9's lens compatibility limitation with newer SSM/SAM lenses already - [MHohner explains it better than I could](https://www.mhohner.de/sony-minolta/faq.php#newlensoldcamera) - this *isn't* about upgrading it to be lens compatible. The last opportunity for that was in [2015](https://www.dyxum.com/dforum/dynax-9-ssm-upgrade-available-out-of-stock-2015_topic45829_page1.html) and that has since expired. If your Alpha/Dynax/Maxxum 9 has Custom Function 20-4, it has the SSM/SAM upgrade. If it doesn't now, it never will.

This covers a *different* upgrade, which gives your Alpha/Dynax/Maxxum 9 four extra Custom Functions like that of the Alpha/Dynax/Maxxum 9 Ti (Titanium);

- **Custom Function 14-2**: Allows changing the duration of the AF Area display.
- **Custom Function 18-3**: Program shift Aperture/Shutter Priority, which is possible with the front dial, while exposure compensation can be adjusted with the rear dial.
- **Custom Function 22 (-1/-2)**: The option to turn On/Off the AF Illuminator
- **Custom Function 23 (-1/-2)**: The option to lock the Front/Rear Control Dials when the exposure meter is inactive, in order to circumvent any accidental movement by brushing against or transporting the camera.

This information was originally discovered and provided by Matthias Paul on the [Mi-Fo Minolta Forums (DE)](https://www.so-fo.de/t28555f164-Zusaetzliche-Funktionen-fuer-die-Minolta-Dynax.html#msg270729), translated into English by Rolf on [Dyxum Forums (EN)](https://www.dyxum.com/dforum/belated-christmas-gift-for-dynax-maxxum-alpha-9_topic71107_page1.html), and French by Slipsale on [AlphaDxD Forums (FR)](https://www.alphadxd.fr/viewtopic.php?f=118&t=54935).

**DISCLAIMER** - Follow the instructions *EXACTLY* as directed, all the way until the end. This process opens up a diagnostics mode within your camera, and pressing other buttons while in this mode can have unexpected and undocumented consequences. **This diagnostic mode risks bricking the camera**. The only way to fix the camera if this happens would be a Minolta Service Center, which doesn't exist any more.

- **Read the Disclaimer above, again.**
- Turn on your Alpha/Dynax/Maxxum 9
- Ensure there is no film in the camera, then close and lock the film back.
- Ensure no lens is attached to the camera, and put the body cap on the camera.
- Open the Battery Door, but keep the batteries inside the compartment.
- Wait 5 seconds.
- Push the Manual-Rewind Button, and hold it (under right-hand side control panel door).
- Close and Lock the Battery Door, still holding the Manual-Rewind Button.
- Once the Battery Door is closed, release the Manual-Rewind Button.
- **Read the Disclaimer above, again.**
- **DO NOT PRESS ANY BUTTONS EXCEPT AS DIRECTED AT THIS POINT**. 
    - *The Diagnostics Mode has been activated, all the LCDs should be lit up, including the red AF marks and the green background light.*
- Push the 'AEL' Button and hold it
    - *The display on the top of the camera should display a '0'.* 
- Hold the 'AEL' Button for a further 5 seconds.
    - *The display on the top should change to a '1'*
- Release the 'AEL' Button if it changes to '1', or after 10 seconds if nothing happens.
    - *If it stays at '0', i.e. nothing happens, continue the steps*
- Open the Battery Door.
- Put the camera on Lock.
- Close the Battery Door.
- Turn the camera on.

After this, your Alpha/Dynax/Maxxum 9 should now have the extra Custom Functions '**CUSt 22**' and '**CUSt 23**'. If not, then it didn't work. You can keep attempting the process until it works*, and if it did work, you can repeat these steps to remove the extra functions and features.

**Note**: The Custom Function upgrade can not be done on early-model Alpha/Dynax/Maxxum 9's because they used older circuit boards that didn't have these features built-in. It won't negatively affect the camera by attempting these steps, the upgrade just won't ever work. Later serial number models and all Alpha/Dynax/Maxxum 9's that received the SSM/SAM upgrade can get this upgrade, however.

***
### Internal (Reddit Guides)

#### [u/DeadlySwan: How to Disassemble an Alpha/Dynax/Maxxum 9xi](https://www.reddit.com/r/minolta/comments/udg6fe/how_to_disassemble_a_maxxumdynax_9xi/)

u/DeadlySwan has written up an excellent short piece on how to disassemble the panels off one of the AF Minolta bodies, with step-by-step images to accompany it. This is particularly important as there is no other guide online, so it's also been [archived](https://web.archive.org/web/0/https://www.reddit.com/r/minolta/comments/udg6fe/how_to_disassemble_a_maxxumdynax_9xi/) in case it is ever lost.

#### [u/neotil1: Aperture Base Assembly and Door Latch Repairs of an Alpha/Dynax/Maxxum 7](https://www.reddit.com/r/minolta/comments/uo72ts/minolta_dynaxmaxxumalpha_7_aperture_base_assembly/)

u/neotil1 replaces a single plastic gear on with a brass one. Sounds easy until you realise the gear is on the motor-shaft which requires an almost complete teardown. This is followed up a by a simpler fix for a broken door latch, engineered for reliability and strength. This isn't written as a strict guide, but as supporting information. If you do have questions though, the author is happy to help!

This has been followed up by **an experimental method** proposed below by u/ChrisPVille;

#### [u/ChrisPVille Alpha/Dynax/Maxum 7, 15 Minute Aperture Drive Repair](https://www.reddit.com/r/minolta/comments/1fa3fh5/a7_aperture_drive_repair_in_15_minutes_not_15/)

u/ChristPVille has kindly provided an updated, **albeit experimental method** to repair and replace the Aperture Drive Assembly Gear on the Maxxum 7 without having to teardown the entire camera. The complete writeup and Guide is on [Dyxum](https://www.dyxum.com/dforum/dynax-alpha-7-aperture-repair-easy-mode_topic144604.html). It does require some 'destructive maintenance' that *can risk breaking the camera internals* in the process, but it's far easier to tackle the common failure point of this camera with this method. There is a curing process for the glue used that takes 24 hours, but the delicate replacement operation can be complete in as little as 15-20 minutes.

The author wants to re-iterate that this is an **experimental repair**. Long term results on the longevity of the repair are not known at this time, so only practice this method if you already own the camera with a broken gear shaft.

***
## Lens Guides
***

### **How to modify an MC Rokkor 55mm f/1.7 to have a ½ stop at f/2**

If you've ever owned an early MC 50mm lens, you'd note that the apertures follow and click-stop in this order; f/1.7, 2.8, 4, 5.6... but f/1.7 to 2.8 is a big jump. What if you want just f/2? Discovered by u/JohnCClarke, [Minoltista on Flickr](https://web.archive.org/web/20230611211635/https://www.flickr.com/photos/24512777@N06/albums/72157658520840172/with/21180930038/) briefly details a modification of the MC Rokkor 55mm to add this half-stop to the lens.

Click the link above for a visual demonstration of the mod, as well as the steps to follow.

***

### **How to modify an MD Zoom 35-70mm f/3.5 to have a variable ~f/2.8**

[Debuggerus on Flickr](https://www.flickr.com/groups/14411702@N00/discuss/72157622735081016/) noticed that their 35-70mm lens didn't open the aperture blades all the way between 35-60mm focal lengths, so they decided to take it apart and figure out why.

The 'fixed' f/3.5 Zoom lens we all know and love actually has aperture stoppers built in to keep it restricted to a fixed aperture throughout all focal lengths. In reality, the 35-70mm f/3.5 is *actually* a variable 35-70mm f/2.8~3.5 lens!

There doesn't appear to be any loss of quality by 'widening' the lens, so [here's the 2 screws you need to remove to do it](https://www.flickr.com/groups/14411702@N00/discuss/72157622735081016/)! The process is also fully reversible, just reinstall the stoppers.

***

### **How to use a Minolta/Konica-Minolta/Sony AF camera with Manual Focus Lenses (Remove Shutter Lock)**

Manual Focus lenses were on their way out almost as soon as the first Auto-Focus camera was released. That didn't stop people attempting to use them on AF cameras, however ([see the FFAQ](https://www.reddit.com/r/MinoltaGang/about/wiki/index/minoltopedia/ffaq/#wiki_can_i_adapt_minolta_.28sr.2Fmc.2Fmd.29_lenses_to_minolta_and_sony_a-mount.3F)). Minolta put a Shutter Lock safety feature in their AF lineup to prevent shutters being released without lenses attached by default. It can be over-ridden though, courtesy of [Konica Minolta Support](https://www.konicaminoltasupport.com/index.php?id=4569&tx_faqmanager_pi1%5Bquestion%5D=869&tx_faqmanager_pi1%5Bproduct%5D=77&tx_faqmanager_pi1%5Bproducttype%5D=14&tx_faqmanager_pi1%5Bcategory%5D=1) (by u/BigFujica690 who found it), and [MHohner](https://www.mhohner.de/sony-minolta/faq.php#lenscheck).

**Note** - Minolta gave different model names for their Alpha, Dynax, and Maxxum AutoFocus series. The first column has the 'most well known' name for each model, as well as the alternative names or model variations that have the same Preparation Steps. If you can't find yours, try Ctrl-F with your model number.

*You can use your Alpha/Dynax/Maxxum with a telescope, microscope, or lens without an electronic connection by pressing a combination of camera controls while switching the Camera ON. Consult the table below for the proper sequence for your camera.*

|                                 Model Name(s)                                  |                  Alternative Model Name(s) (Alpha / Dynax / Maxxum)                  | Preparation Step(s) Required                                                                                                                                                                                                                                                                |
| :----------------------------------------------------------------------------: | :----------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|                                5000, 7000, 9000                                |                               α-"" / ""AF / Maxxum ""                                | No preparation needed                                                                                                                                                                                                                                                                       |
|                           3000i, 5000i, 7000i, 8000i                           |              α-3700i, α-5700i, α-7700i, α-8700i / Dynax "" / Maxxum ""               | No preparation needed                                                                                                                                                                                                                                                                       |
|                                 2xi, 3xi, SPxi                                 |                         α-"", α-3xiP / Dynax "" / Maxxum ""                          | *Use of T-mount lenses, microscopes, and telescopes is not possible.*                                                                                                                                                                                                                       |
|                                      5xi                                       |                         α-"", α-5xiP / Dynax "" / Maxxum ""                          | Press and hold SPOT and FUNC. buttons and switch from LOCK to ON.                                                                                                                                                                                                                           |
|                                    7xi, 9xi                                    |                         α-"", α-7xiP / Dynax "" / Maxxum ""                          | Press and hold AEL and FUNC. buttons and move power switch from LOCK to ON.                                                                                                                                                                                                                 |
|                                     300si                                      | α-101si / Dynax "" / Maxxum "", Maxxum 350si Panorama Date, Panorama Elite, RZ 330si | Press and hold FLASH and DRIVE/SELFTIMER buttons and move power switch for LOCK to ON. (Off appears in LCD panel)                                                                                                                                                                           |
|                                 (Maxxum) 400si                                 |     α-303si / Dynax 500si / Maxxum 450si Panorama Date, Panorama Elite, RZ 430si     | Press and hold Drive Mode and AV buttons and move power switch from LOCK to ON.                                                                                                                                                                                                             |
|                                 (Maxxum) 500si                                 |           α-303si Super / Dynax 500si Super / Maxxum 500si Super, RZ 530si           | Press and hold Drive Mode and SPOT buttons and move power switch from LOCK to ON.                                                                                                                                                                                                           |
|                                 600si Classic                                  |                 α-507si / Dynax "" / Maxxum "",  650si Panorama Date                 | Press and hold the LENS RELEASE button and FILM SPEED button and move the power switch from LOCK to ON. (OFF appears in LCD panel)                                                                                                                                                          |
|                                     700si                                      |                            α-707si / Dynax "" / Maxxum ""                            | Press and hold SPOT and CARD buttons and move power switch from LOCK to ON.                                                                                                                                                                                                                 |
|                                     800si                                      |                            α-807si / Dynax "" / Maxxum ""                            | Press and hold SUBJECT PROGRAM and AEL buttons and move power switch from LOCK to ON. (OFF appears in LCD panel)                                                                                                                                                                            |
|                               505si, 505si Super                               |                  α-Sweet / Dynax "" / Maxxum HTsi, HTsi Plus, XTsi                   | Press and hold the Selftimer-Drive Mode button and Spot/AE button while sliding the Main Switch to "ON." (OFF appears in LCD panel)                                                                                                                                                         |
|                                     404si                                      |                          α-Sweet S / Dynax "" / Maxxum STsi                          | Move the function Dial to Multiple Exposure. Press and hold the Program Reset and Selftimer-Drive Mode button while sliding the Main Switch to "ON." (OFF appears in LCD panel)                                                                                                             |
|                                     303si                                      |                           α-360si / Dynax "" / Maxxum QTsi                           | Press and hold the Selftimer-Drive Mode button and Subject Program button while sliding the Main Switch to "ON." ("OF" appears in LCD panel)                                                                                                                                                |
|                                4, 5, 7, 9, 9Ti                                 |  α-"", 3, α-Sweet II L, α-Sweet II, 7 Limited / Dynax "", 3, 7 Limited / Maxxum ""   | Custom Function. [See camera’s instruction manual](https://www.butkus.org/chinon/minolta.htm#:~:text=Minolta%20Maxxum%205%20%2F-,dynax%205,-Minolta%20Maxxum%20300si).                                                                                                                      |
|                                   (Maxxum) 3                                   |                                 Dynax 3L / Maxxum GT                                 | Press and hold SUBJECT PROGRAM and Drive Mode buttons and move power switch to ON (OFF appears in LCD panel)                                                                                                                                                                                |
|                                 (Dynax) 30, 40                                 |                                   α-50 / Maxxum 50                                   | Press and hold Drive Mode and move Function dial from OFF to any mode.                                                                                                                                                                                                                      |
|                                   (Dynax) 60                                   |                                   α-70 / Maxxum 70                                   | Custom Function. [See camera's instruction manual](https://www.butkus.org/chinon/minolta/minolta_dynax_60/minolta_dynax_60.htm).                                                                                                                                                            |
|                                Vectis S-1 (APS)                                |                                          -                                           | Press ON/OFF to turn camera ON. Open door that covers hidden buttons. Press the Drive Mode button (farthest on the left) and the MODE button together. "ON" will appear in the LCD panel. Press the "SEL" button (second from right in hidden buttons). "OFF" Will appear in the LCD panel. |
|                                     RD-175                                     |                                    Agfa Actioncam                                    | Press and hold SELFTIMER and AV buttons and move power switch from LOCK to ON. ("ON" appears in LCD panel)                                                                                                                                                                                  |
|                             Konica Minolta 5D, 7D                              |                 α-Sweet Digital, α-7 Digital /  Dynax "" / Maxxum ""                 | Custom Function. [See camera’s instruction manual](https://www.konicaminoltasupport.com/index.php?id=3044&L=102).                                                                                                                                                                           |
|      Sony DSLR's α-100, 560, 580, 700, 850 & 900 (fw 2.00), SLT's, ILCA's      |                                          -                                           | Custom Function. [See camera's instruction manual](https://www.sony.co.uk/electronics/support/interchangeable-lens-cameras-a-mount-body/manuals).                                                                                                                                           |
| Sony DSLR's α-200, 230, 300, 330, 350, 380, 450, 500, 550, 850 & 900 (fw 1.00) |                                          -                                           | Only De-activated when using Manual (M) mode. In the other modes, it's always active.                                                                                                                                                                                                       |

***