<!-- TITLE: Laser Cutter -->
<!-- SUBTITLE: Quick start guide and training overview -->



<div style="float: right; max-width: 25em;">

<img style="width: 100%;" src="https://www.beyondtools.com/wptools/wp-content/uploads/RS80-7050.png" />

| | |
| -- | -- |
| **Type** | Laser Cutter |
| **Status** | 🔴&nbsp; <span style="font-weight:bold;color:red;">Offline</span><br>*Training process under development* |
| **Manager #1** | [\<TBD>](mailto:email@student.uwa.edu.au) |
| **Manager #2** | [\<TBD>](mailto:email@student.uwa.edu.au) |
| <hr> | <hr> |
| **Location** | G.01K (Makers Lab, FAZ) |
| **Make / Model** | Modified [Redsail](http://www.redsail.com.au/Redsail_Laser_Cutters.html) X700 *rebadged as an* RS80 7050 |
| **Supplier** | [Beyond Tools](//beyondtools.com/product/cnc-laser-cutting-machine-rs80-7050-by-redsail/) |
| **Documents (PDF/GDoc)** | • [SOP](//docs.google.com/document/d/1YoRvHlioBr_0Iga0kByxP9_In5HDSBRIulyijE1l5Bw/edit?usp=sharing)</br> • [Quick Start Guide](//docs.google.com/document/d/1meukINwlzOAqyci1PQPCT0D7ioIP87fsYjfJgwfa0_Y/edit?usp=sharing) </br> • [Training Guide](//docs.google.com/document/d/1wNsw9FtoIbOrICtQusdzMs7pVwdKutmpY-jtj8qQE8I/edit?usp=sharing) </br> • [Instruction Manual](//drive.google.com/file/d/1LQYpvsl0jAAz1jYCYtkzrAsm2a_jzwZw/view?usp=sharing) </br> • [Risk Assessment(s)](//drive.google.com/open?id=1WhWc7pQ6lxRxsKRGI6sjkD9aNqvNLvn7) |

</div>

Our laser cutter provides a working area of just under 500x700mm. It is very useful for rapidly fabricating flat parts from sheet material such as acrylic (≤9mm thick), MDF (≤9mm thick), plywood (≤9mm thick), and *some* papers and textiles. Please be aware that whilst possible on some much larger machines, our laser cutter **cannot cut any metal materials.** Attempts at cutting metal may damage the optics due to reflection of the laser beam.

It is generally considered a safe machine when used properly, however there are a few hazards that users must be aware of at all times. To avoid fire and potential damage to the machine or yourself, precautions must be taken before any cutting starts (see [Quick Start](#quick-start) below, and the [Operators Manual](/equipment/laser/manual) for more information).

If you are a member of the UWA Makers and want to be trained on how to use the laser cutter, please carefully read this page and the *New Operators* section of the Operation Manual at minimum. You will then need to complete the instructions listed under the [Getting Access](#getting-access) section below, before you can come in for an induction with one of the Equipment Managers (listed above on mobile devices, or in the sidebar to the right for desktop users).

| Content |
| -- |
| [Quick Start](#quick-start) <br/> [Important Notes](#important-notes) <br/> [Getting Access](#getting-access) <hr/> [Operators Manual](/equipment/laser/manual) <br/> [Trainers Guide](/equipment/laser/training) <br/> [Managers Handbook](/equipment/laser/handbook)|

As all members who are inducted into the Makers Lab will know, **no one is allowed to use any tool that they have not been officially trained to use.** This is the same for the laser cutter, and **anyone found to be breaching this will immediately be suspended from accessing the makerspace.**

<br style="clear:both" />

# Quick Start
Whilst there are some nuances and advanced techniques to learn (you must read the *New Operators* section before attending your induction session!), you will get reliable results every time if you follow these 15 steps in order. **Use the SOP and the abridged Quick Start Guide located near the machine to ensure each step is completed in order every time you operate the machine.**

<div align="center">

| | | |
| - | - | - |
| 1. Upload files to USB drive <br> 2. Complete pre-checks <span style="color: red;">(extractor!)</span> <br> 3. Turn on the laser cutter <br> 4. Clean and clear the machine <br> 5. Insert material | 6. Set the focal height <span style="color: red;">(over material!)</span> <br> 7. Set the XY origin (0,0) <br> 8. Turn on the laptop <br> 9. Load design into AutoLaser <br> 10. Set your work layers correctly | 11. Perform a test fit (Border View) <br> 12. Start the cut/etch <br> 13. Wait for fumes <br> 14. Remove material <br> 15. Shutdown the equipment |

</div>

If you need clarification on any of the printed prompts, come back to this page or read the [Operators Manual](/equipment/laser/manual) for more guidance. Alternatively, ask another trained operator for help when you aren't 100% sure how to proceed.

> ⚠️ &nbsp;**Trained operators only**
> This information is provided for informational purposes only. It must not be used in place of proper training. Follow the process outlined below under [Getting Access](#getting-access) to become a trained operator.
{.is-warning}

<br>

### Before You Cut

<img style="float: left; max-width: 10em; margin-right: 2em;" src="https://winaero.com/blog/wp-content/uploads/2017/12/usb-flash-drive-icon-256-big.png" />

**1. Create your design**
* Use a program such as [Fusion 360](https://www.autodesk.com/products/fusion-360/blog/tip-tuesday-making-it-real-exporting-dxf-and-stl-from-fusion-360/), [Solidworks](http://help.solidworks.com/2016/english/solidworks/sldworks/t_drawings_dwg_dxf_export.htm), [Illustrator](https://helpx.adobe.com/au/illustrator/using/exporting-artwork.html), or [Inkscape](http://www.bigbluesaw.com/big-blue-saw-blog/general-updates/big-blue-saws-dxf-export-for-inkscape.html) to create a suitable file (prefer dxf, but svg is possible to use) to cut or engrave.
* If you are designing a part that you need cut to super tight tolerances, you will need to account for the kerf (thickness) of the laser beam in your designs. The kerf is typically 0.2mm wide (0.1mm radius) for most materials, but you may need to test this yourself.
* Alternatively, you can use a raster image such as a .jpg or .bmp if you want to engrave a photo.
* Once you have the right file(s) to use, upload them to a USB flash drive and bring it with you to the laser cutter.

<br style="clear:both" />

### Startup Procedure

<img style="float: right; max-width: 10em; margin-left: 2em;" src="https://agroairdynamics.com/wp-content/uploads/2017/08/agro-air-dynamic-barn-fan-icon-200px.png" />

**2. Complete pre-checks before turning on**
* <span style="color: blue; text-decoration: underline;">Make sure the *very first* thing you turn on is the extractor</span>
* Turn the extractor on by pressing the button on the wall for about 3 seconds until the orange light comes on
* Ensure that the water level of the chiller (beige box besides the laser cutter with lots of tubes) is in the <span style="color: green;">green region</span>

<br style="clear:both" />

> ⚠️ &nbsp;**What if the water level isn't in the green region?**
> If the chiller does not have enough coolant, DO NOT PROCEED, and notify an Equipment Manager
{.is-warning}

<img style="float: left; max-width: 10em; margin-right: 2em;" src="https://vignette.wikia.nocookie.net/loadout/images/c/ce/Key-icon.png/revision/latest?cb=20140310144654" />

**3. Turn on the laser cutter**
* On the right side of the machine is the console (with the LCD screen), and above that are the power controls
* At the power controls, turn the <span style="color: red;">Emergency Stop</span> button clockwise until it pops up
* Turn the key to a horizontal poisition, if it isn't already. The machine should now be on.
* Press `ESC` (*escape*) key on the console twice to reset the machine state after the "System Init" message

<br style="clear:both" />

> ℹ️ &nbsp;**Can the laser hurt me?**
> There are safety interlocks on the doors preventing the CO2 laser tube from firing when the enclosure is open, and it is safe to load your materials when the door is open. If you are still concerned, you may switch the "LASER SWITCH" to the "0" position to disable the laser tube. You will need to make sure it is turned on before you cut though.
{.is-info}

### Load the Material

<img style="float: right; max-width: 10em; margin-left: 2em;" src="http://aux.iconspalace.com/uploads/clear-icon-256-1544859171.png" />

**4. Clear the machine**
* Move the head out of the way if needed using the `▲`, `▼`, `◄`, and `►` keys (*arrows*)
* Lower or raise the bed if needed using the `Ⓤ-` and `Ⓤ+` keys (these markings are on the digit keys)
* Ensure the cutting bed is free of any debris
* Use a brush to wipe any dust away from the internal vent, which is located to the left of the cutting bed

<br style="clear:both" />
<img style="float: left; max-width: 10em; margin-right: 2em;" src="http://themebuilders.net/wp-content/uploads/2016/06/ThemeBuilders-Icon-Wood.png" />

**5. Insert your workpiece**
* Again, move the head and bed if needed. Be careful not to knock the head when loading material.
* Place your material on the honeycomb grid, making sure it is laying flat and square
* If you are a novice operator, only use materials supplied by the Makers for the laser cutter. Otherwise consult the Operators Manual and the approved/banned materials lists below to determine what material you can use
* The maximum workpiece size possible when using the honeycomb grid is 680x480mm, so use sheets this big or smaller (600 x 450 x 3mm MDF is commonly available)

<br style="clear:both" />

### Setup the Origin Points

<img style="float: right; max-width: 10em; margin-left: 2em;" src="http://pluspng.com/img-png/png-focus-focus-270.png" />

**6. Set the focal length (zero the z-height)**
* Move the head over the material using the *arrow* keys ( `▲`, `▼`, `◄`, and `►`)
* On the console, press `⊙` (period) then `⏎` (enter) to start the automated process to zero the Z height
* You can press `ESC` to exit a dialog (i.e., such as at the confirmation screen seen after pressing `⊙`)

<br style="clear:both" />

> ⚠️ &nbsp;**WARNING**
> NEVER press the ⊙ (period) button unless the foot under the cutting head is clearly and completely over the material. Setting the focus with the plastic foot over the mesh, or only partially over the material can seriously damage the head.
{.is-warning}

<img style="float: left; max-width: 10em; margin-right: 2em;" src="https://static.thenounproject.com/png/405077-200.png" />

**7. Set the XY origin (0,0)**
* Make sure you have set the focal length (Step 6) before attempting this step
* Use the *arrow keys* to move the red dot to the top right of where your cut should be made
* If the head is moving too fast or slow, you can press the `👆` key between the arrows to change the speed
* Once in the correct spot, press the button labeled "*origin*"
* If you move the head, the machine will remember where the origin is when it starts cutting

<br style="clear:both" />

> ℹ️ &nbsp;**Calculating the origin point**
> When you import your design into the software, it draws an invisible box around your digital design. The origin point is the top right of this digital boundry. You tell the machine where this point (the *origin*) should physically be located by using the above process. Keep in mind, it finds the absolute extremities of what you load into the software to determine the boundry points, so watch out for stray lines and artifacts in the software.
{.is-info}

### Running the Software

<img style="float: right; max-width: 10em; margin-left: 2em;" src="https://images.vexels.com/media/users/3/128132/isolated/preview/fa3b9aad78a9db81459bd03294a0f985-flat-laptop-icon-design-by-vexels.png" />

**8. Turn on the computer**
* Turn on the laptop
* Make sure the USB connecting the laptop to the laser is plugged in
* Login using the password provided at your induction
* Open up AutoLaser and close any other unused designs

<br style="clear:both" />
<img style="float: left; max-width: 10em; margin-right: 2em;" src="https://png.icons8.com/color/1600/construction-carpenter-ruler.png" />

**9. Open your design in AutoLaser**
* Connect the USB flash drive containing your design to the laptop
* Click "File", then "Import", select your design, then click the Open button to import your design
* Choose "Automatic" when asked about "Import File Units"
* Where you place the design on the virtual bed does not affect where the origin point will be located (it is only a reference for sizing). See "Calculating the origin point" under step 7 for more information

<br style="clear:both" />

> ℹ️ &nbsp;**Confirming the size is correct**
> You will likely need to scale the design to the correct size if you import a file from the internet, or when using a design from a graphics program such as Illustrator. Do this by clicking a shape of a known size, and seeing if it is correct using the dimension tools in the top bar of AutoLaser. Once you know the scale it is off by (needs to be a percentage), select the entire design and use the resize tool.
{.is-info}

**10. Configure your work layers**


### Making the Cut

**11. Perform a test fit**
* Select the correct COM port from the sidebar on the right (usually COM6, and never COM3)
* If COM3 is the only option, ensure the laser cutter is both turned on and connected via USB. Then press the "*Search*" button
* Press the "*Border View*" button at the bottom left of the sidebar, and then click "*Okay*" at the next dialog
* The head will now move around the border of where the machine will make the cut
* Watch it move, and realign your material or origin point (redo *Step 7* if needed) until it you confirm it will fit and cut where expected

<br style="clear:both" />
<img style="float: right; max-width: 10em; margin-left: 2em;" src="https://ambro.co.uk/wp-content/uploads/2017/03/Laser-icon.png" />

**12. Start the cut**
* Ensure the "LASER SWITCH" is set to the "1" (on) position
* **Close the lid** and press start from within AutoLaser
* Type a meaningful name into the dialog (suggested format "PROJECTNAME_MATERIALTYPE_XXmm") and click "OK"
* The machine will start the cut now. **Do not leave the machine** until it is finished, watch the cut, and be ready to act in case something goes wrong

<br style="clear:both" />

### Shutdown Procedure

<img style="float: left; max-width: 10em; margin-right: 2em;" src="https://png2.kisspng.com/20180226/bfe/kisspng-clock-timer-icon-cartoon-drawing-time-5a949f36924226.3611656415196895265991.png" />

**13. [MDF Only] Wait 2-minutes before opening the lid**
* MDF contains formaldehyde which is released as a gas when burned (such as in a laser cutter)
* It is essential for your own safety that you allow all of the fumes to be adequetely extracted
* Use the timer provided to ensure you keep the lid closed and the extractor running for a MINIMUM of 2 minutes after any cutting has finished
* You can open the door next to the laser cutter to allow fresh air into the room, make sure you close it once finished.

<br style="clear:both" />
<img style="float: right; max-width: 10em; margin-left: 2em;" src="http://icons.iconarchive.com/icons/cornmanthe3rd/metronome/256/System-recycling-bin-icon.png" />

**14. Remove your workpiece and any mess**
* Open the lid once safe to do so
* Move the head out of the way if not already (use the *arrow* keys), and lower the bed slightly (`Ⓤ-` and `Ⓤ+`) if removing large pieces
* Remove your workpieces in a safe manner
* Ensure the bed is clean and ready for the next operator, and close the lid once finished
* Place any usable scrap material into the scrap bin for other operators (snap off any unusable parts)

<br style="clear:both" />
<img style="float: left; max-width: 10em; margin-right: 2em;" src="https://img.icons8.com/color/1600/emergency-stop-button.png" />

**15. Shut down the equipment**
* Save your file on the laptop if required, and close AutoLaser
* Remove your USB drive from the laptop
* Shut down the laptop
* Press the <span style="color: red;">Emergency Stop</span> button and turn the key to a vertical position at the power control panel
* Turn the extraction off at the wall by holding the button until the orange light goes off

<br style="clear:both" />

# Important Notes
Cutting the wrong material in the laser cutter can be dangerous to the machine, or the operator. Only approved materials should be cut, and banned materials should never be placed in, or even around the laser cutter. Cutting an unknown material risks bodily harm and damage to equipment/facilities. <!--"Incidents involving equipment such as the laser cutter may result in the faculty withdrawing their support for the UWA Makers which would be bad for everyone." temp removed out of concern people may not report these-->

### Approved Materials

Only Equipment Managers may add materials to this list after sufficient research and testing. Also, a chart with suitable cutting powers (%) and rates (mm/s) for approved materials should be located near the laser cutter. Please let an Equipment Manager know if the cutting power/speed guide is missing, or if you would like to request a material be added to the approved list.

| Material | Cut? | Etch? | Warnings / Notes |
| -- | :-: | :-: | -- |
| <span class="is-material-success">Acrylic (Plexiglas, Lucite, PMMA)</span> | ≤9mm | ✅ | Cuts well, leaves a smooth polished edge. Higher powers can leave smoke/scorch marks along edges. It is the second most popular material used after MDF, but is more expensive by comparison. Only use plastic from a [laser cutting focused supplier](http://www.cdclaser.com.au/). **Never use plastic from Bunnings (see Polycarbonate in the list below) as it will damage the machine.** |
| <span class="is-material-success">Natural Cloths (cotton, felt, hemp)</span> | 1 sheet at a time | ❌ | NO plastic coated or impregnated cloth! **Must be 100% cotton or similar.** |
| <span class="is-material-success">Delrin</span> | \<todo> | ✅ | From MakeICT: *"Comes in a number of shore strengths (hardness), the harder tends to work better. Great for gears!"* |
| <span class="is-material-success">Glass</span> | ❌ | ✅ | Has a sandblasted look. **SEE REFLECTIVE SURFACES FROM BANNED MATERIALS LIST.** |
| <span class="is-material-success">Hardwoods (i.e, Jarrah)</span> | Thichness depends on type of wood | ✅ | Avoid oily/resinous woods as they will likely catch fire. It is typical that only thinner hardwood sheets will cut. You will need to test to find the right power/speed combination. |
| <span class="is-material-success">MDF, engineered woods</span> | ≤9mm | ✅ | May experience a higher amount of charring when cut. This is the most common material used in the machine due to it's price, and we suggest you prototype with MDF first before cutting out of something like acrylic. **You must leave the lid down with the extractor running for 2 minutes after a cut is finished** so that the dangerous fumes can be removed. |
| <span class="is-material-success">Melamine</span> | Laminated wood only | ❌ | Melamine sheets by themselves have not been tested (assume unsafe for now), however it is safe to cut melamine laminated MDF/plywood (as used by the *'7 Deadly Sins'* printers for example). |
| <span class="is-material-success">Paper, card stock, cardboard</span> | Can cut most thicknesses | ❌ | Cuts well and makes awesome stencils, but can catch fire easily. Only cut if you are comfortable stopping a small fire if needed, and **never look away while cutting.** Light materials may need to be held down. **SEE CORRUGATED CARD ON BANNED MATERIALS LIST** |
| <span class="is-material-success">Pine</span> | ≤12mm | ✅ | Can't buy wide sheets of pine like you can MDF/Plywood, but it can be purchased in lengths at decent widths. Useful if you want to make something that can be stained, or you need something thicker than can be cut with MDF and hardwoods. |
| <span class="is-material-success">Plywood, composite woods</span> | ≤9mm | ✅ | Contain glue, and may not cut as well as solid wood. Possible to stain to look presentable, but stained pine is typically nicer when raw/stained. |
| <hr> | <hr> | <hr> | <hr> |
| <span class="is-material-success">Anodised Aluminium</span> | ❌ | ✅ | Vaporises the anodised layer away |
| <span class="is-material-success">Bare Metals</span> | ❌ | ✅ | Requires a coat of [CerMark™](https://lstgroup.com.au/cermark/) or similar |
| <span class="is-material-success">Brass</span> | ❌ | ✅ | Requires a coat of [CerMark™](https://lstgroup.com.au/cermark/) or similar |
| <span class="is-material-success">Coated Metals</span> | ❌ | ✅ | Vaporises the coating away. **SEE REFLECTIVE SURFACES FROM BANNED MATERIALS LIST.** |
| <span class="is-material-success">Painted Metals</span> | ❌ | ✅ | Vaporises the paint away (possible to use for PCB manufacturing) |
| <span class="is-material-success">Stainless Steel</span> | ❌ | ✅ | Requires a coat of [CerMark™](https://lstgroup.com.au/cermark/) or similar |
| <span class="is-material-success">Titanium</span> | ❌ | ✅ | Requires a coat of [CerMark™](https://lstgroup.com.au/cermark/) or similar |

### Banned Materials

These materials should **never** be processed in the laser cutter. This list is not exhaustive, and it is best for operators to assume anything not on the approved list is prohibited.

| Material | Common Names | Hazard | Warnings / Notes |
| -- | -- | -- | -- |
| <span class="is-material-warning">Acrylonitrile Butadiene Styrene</span> | ABS | Dangerous fumes | Emits [Hydrogen Cyanide (HCN) gas](https://en.wikipedia.org/wiki/Hydrogen_cyanide) and tends to melt, leaving a gooey mess on the honeycomb. |
| <span class="is-material-warning">Body Parts</span> | Recipients of a Darwin Award, Bond-like Hero's | First degree burns, exposure to laser | **Seriously! Don't even suggest as a joke.** |
| <span class="is-material-warning">Chlorinated Plastics (polyvinylchloride)</span> | PVC / Vinyl / Pleather / Artificial Leather | Dangerous fumes | **Don't ever cut this material** as it emits pure chlorine gas when cut. This will ruin the optics, cause the metal of the machine to corrode, and ruin the motion control system. Bubbles yellow, smokes alot, STINKS!!!!! |
| <span class="is-material-warning">Corrugated Cardboard</span> | *N/A* | Fire risk | Due to the nature of the cardboard, it is possible for [fire to spread inside the material](https://www.youtube.com/watch?v=veWjTiO44XQ) before the operator sees it. If absoluitely needed, talk to an equipment manager. |
| <span class="is-material-warning">Fiberglass</span> | *Also* Coated Carbon Fibre | Dangerous fumes | It's a mix of two materials that can't be cut. Glass (etch, no cut) and epoxy resin (noxious fumes). Thin carbon fiber mat can be cut, with some fraying - but not when coated |
| <span class="is-material-warning">Galvanized Metal</span> | *N/A* | Dangerous fumes | Zinc fumes are poisonous. Galvanized metal should never be super heated (so don't weld on it either) |
| <span class="is-material-warning">Leather</span> | *N/A* | *See Chlorinated Plastics* | Read the full *Operators Manual* if you need to cut leather, and talk to an Equipment Manager. You will also need proof it is actually leather you are wanting to cut or engrave.  |
| <span class="is-material-warning">Metal</span> | *N/A* | Won't cut | [Power needed for LASER to cut metal](https://en.wikipedia.org/wiki/Laser_cutting#Power_consumption). You can etch some metals though (see the approved list) |
| <span class="is-material-warning">Polyethylene (PE)</span> | HDPE, PET, PETG (eg Milk bottles), Foamcore |  |
| <span class="is-material-warning">Polyurethane (PUR)</span> | Foamcore |  |
| <span class="is-material-warning">Polystyrene</span> | Foamcore |  |  |
| <span class="is-material-warning">Polypropylene</span> | Coreflute |  |  |
| <span class="is-material-warning">Polycarbonate</span> | Suntuf / Lexan / CD's, DVDs, Blu-rays, etc are also made of this | Poor cutting ability, fire risk | Polycarbonate is often found as flat, sheet material. The window of the laser cutter is made of Polycarbonate because polycarbonate strongly absorbs infrared radiation! This is the frequency of light the laser cutter uses to cut materials, so it is very ineffective at cutting polycarbonate. Polycarbonate is a poor choice for laser cutting. **Most acrylic from Bunnings is polycarbonate, which is why plastics from Bunnings are banned.** |
| <span class="is-material-warning">Pressure Treated Wood</span> | Marine plywood | Dangerous fumes | Should never be burned -- not in your fireplace, and definitely not in our LASER. Always ensure you are using non-pressure treated wood in the laser cutter |
| <span class="is-material-warning">Reflective Surfaces</span> | Mirrors, anything chrome plated | Machine damage, won't cut | Mirror surfaces can reflect the laser beam, damaging the cutter's interior components. Some mirrored materials can be placed reflective-side down and cut. |
| <span class="is-material-warning">Unidentified Materials</span> | *"This pretty scrap material I found"* | **???** | If you don't know what it is, don't put it in the laser cutter. This also applies if you aren't certain what type of plastic you have (remember you need an MSDS to bring it in the Makers Lab). |
| <span class="is-material-warning">Victuals</span> | Food | Mess, bad smell | Here is [proof of how messy it really gets](https://www.youtube.com/watch?v=pr1YRP6rWdc). Don't try this in our laser cutter, but please send us a video though if you do it in your own laser cutter! |

<!--

| <span class="is-material-warning">Cork</span> |  |  |
| <span class="is-material-warning">Rubber</span> |  |  |
| <span class="is-material-warning">Latex</span> |  |  |

^ Why were these ever banned?  -->

**Attribution:** *Many of these banned materials and descriptions are based on the [MakeICT Wiki](http://makeict.org/wiki/Laser_Cutter) entry for their laser. We've also confirmed them with a handful of controlled tests, user errors, and verification from other sources (i.e., other makerspaces and safety regulators)*

<script>
var styles = {
  width: "100%",
	height: "100%",
	background: "#009900",
	color: "white",
	padding: "0.2em 0.4em",
	margin: "0",
	display: "block"
};
$(".is-material-success").css(styles);
$( ".is-material-success" ).parent().css( "padding", "0" );

styles.background = "#cc3333";
$(".is-material-warning").css(styles);
$( ".is-material-warning" ).parent().css( "padding", "0" );
</script>

# Getting Access

<br/>

**There are five main steps a prospective operator of the laser cutter must complete before they are granted access to the machine. They are:**

1. Complete the [Lab Access](/safety/lab-access) and [Basic Tools Training](/safety/basic-tool-training) pathway
2. Complete the [UWA laser safety training on LMS](/safety/laser-awareness-training) and download the PDF
3. Login to the UWA Makers' [Access Portal](https://access.uwamakers.com) using your Pheme details, and:
		* Complete the pre-reading (this page and the *New Operators* section of the [Operators Manual](/equipment/laser/manual))
		* Complete the online laser safety quiz located under the "*Training*" Tile in the Access Portal
4. Book and attend a demonstration session with one of the Equipment Managers (you can [email them directly](mailto:laser@makeuwa.com), or jump in `#lasercutter` on [Slack](//makeuwa.slack.com))
5. Once an equipment manager has deemed you as a safe and competent user, they will sign you off using the same method as when you were signed off for lab access.

<br>

> ⚠️ &nbsp;**After Hours Usage**
> Although you may now have "unsupervised access" to the laser cutter, remember you can not use the laser cutter alone after hours (between 6pm to 8am the next day). We also highly suggest you find another trained operator to watch over your first cuts until you are 100% confident.
{.is-warning}

> ℹ️ &nbsp;**Accessing the Laser Room**
> Once you have completed these steps, you will be deemed a trained operator and will be granted unsupvised access to the laser cutter. If you have not previously had the opportunity to complete the training required for RFID access to the Restricted Area (FAZ) in the UWA Makers Lab, you can now do so.
{.is-info}


<br/><br/><br/><br/>
