<h1>Build Guide</h1>
<p>Here's my suggested build guide for the Pink and White noise generator. It would be a good idea to read through the build guide from top to bottom <i>before</i> you start building. Just sayin'. 
  If you have questions or get stuck somewhere, email me: <i>knifeinthetoaster (at) gmail (dot) com.</i></p>
<p><b>Note</b>: This build guide assumes you have a 125B Hammond-style enclosure.</p>
<h2>Tools:</h2>
<p>You'll need the following tools:</p>
<ul>
  <li>A soldering iron</li>
  <li>Solder</li>
  <li>Some form of tip cleaner (a wet soldering sponge or brass wool — my preferred option)</li>
  <li>Wire snippers (flush cut snippers are probably best, but anything roughly craft-sized will do. You could even get away with using scissors if you're in a pinch.)</li>
</ul>

<p>If you are going to install the Pink and White in a 125B Hammond-style enclosure, you'll also need:</p>
<ul>
  <li>A drill of some kind — your standard power drill will do just fine</li>
  <li>Drill bits (I suggest something small to drill a pilot hole, and a stepped drill bit)</li>
  <li>A Phillips-head screwdriver</li>
  <li>A center punch and a hammer</li>
  <li>A marker or a pencil</li>
  <li>A ruler or measuring tape</li>
</ul>

<p>The following would also be helpful, but aren't crucial:</p>
<ul>
  <li>Helping hands</li>
  <li>Tip tinner</li>
  <li>Multimeter</li>
  <li>Flux and some desoldering braid (in case you need to remove a component or clean up an overzealous solder joint)</li>
  <li>A bright light (it really helps when you can see what you're doing)</li>
  <li>Anti-static mat</li>
  <li>90% isopropyl alcohol and a clean toothbrush — you can use these to clean the PCB after you're done building</li>
</ul>
<br>

<h2>Part 0: Gather Ye Together Yon Components and Hear My Tale</h2>
<p>Start by gathering together all your stuff — your tools, all the components — and make sure you aren't missing anything. It also helps to have a clean work surface.</p>
<img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/01.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="The parts">
<h2>Part 1: Let the Soldering ..... COMMENCE!</h2>
<p>Generally, the rule with soldering PCBs is <i>low to high</i>, so we start with the components that lay flattest against the PCB and work our way up. So, with that in mind:</p>

<ol>
  <li>Start with the three resistors</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/02.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Resistance">
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/03.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Trimmers">

  <li>Then the diode — <i>make sure to match the <b>stripe on the diode</b> with the <b>stripe on the PCB</b></i></li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/04.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Diodes, baybeee">
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/05.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Diodes, baybeee">

  <li>Next, flip the PCB over and solder in the two trimmers. I like to do these now since they're the only things on that side of the board and you'll have more space to work with.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/11.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Trimmers">

  <li>The IC sockets are next. Make sure to match the notch on the socket to the notch on the silkscreen.
    <ul>
      <li>I like to solder one pin, then check to ensure the socket is flat against the PCB. If it isn't, just reheat the solder on the pin while applying gentle pressure. You should feel the socket seat itself flat against the PCB.</li>
    </ul>
  </li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/06.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Sockets">

  <li>Insert the voltage regulator and gently bend it down so the plastic housing rests against the PCB. Use the outline on the silkscreen as a guide.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/07.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Voltage regulator">

  <li>Now solder the 100nF capacitors.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/08.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="100nF capacitors">

  <li>Then the 1nF capacitor</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/10-1.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="1nF capacitor">

  <li>And then the 10µF capacitor
    <ul>
      <li><b>Note:</b> The 10µF capacitor is polarized — match the short leg to the filled section of the footprint on the silkscreen.</li>
    </ul>
  </li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/09.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="10µF capacitor">
</ol>

<h2>Part 2: Put It in Something</h2>
<ol start="9">
  <li>Now you'll need to drill holes for the audio jacks and the power input. The centerpoints of the audio jacks are roughly 2.8cm apart. My suggestion is to find the center point of the enclosure and make two marks 1.4cm apart from the center. As with all things: measure twice, and cut (or, in this case, drill) once. I also recommend checking the placement of the holes against the PCB.</li>

  <li>Use a center punch to mark the center of your two holes, then drill pilot holes using a small drill bit. <b>Go slow to ensure the bit doesn't slip out of place.</b></li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/12.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Tools!">
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/13.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Marks on metal">

  <li>Slowly increase the hole size, checking until the audio jacks fit snugly. It doesn't need to be exact.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/14.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="This is your captain speaking">
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/15.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Looks about right">

  <li>Place the audio jacks in the PCB, aligning the notches, and carefully insert them through the holes in the enclosure. Finger-tighten the nuts. If you've measured correctly, everything should fit nicely.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/18.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Yeah, so what if they're a bit off-center?">

  <li>If everything fits, solder the audio jacks to the board, then unscrew them from the enclosure.</li>

  <li>Now install the power input. Drill another hole — I suggest placing it on the side furthest from the power pads on the PCB, especially if you're using battery power.</li>
  <ul>
    <li>This is what I mean:</li>
    <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/23.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="The Heavylifter">
    <li>Follow the same drilling steps from above.</li>
  </ul>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/16.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="The Mark">
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/17.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Wish I could keep your little bodyyyyy">

  <li>Install the power input and solder the provided wires and battery snap as shown <a href="images/DCjack.jpg" target="_blank">here</a>.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/19.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Good enough, I spose">
  <ul>
    <li>This follows the standard for guitar pedals (9V center-negative), but you're free to wire it differently. If you want center-positive, search "<i>9v center positive wiring</i>" — you’ll likely find what you need. I stuck with center-negative for compatibility with existing gear.</li>
  </ul>

  <li>If you haven’t already, insert the chips into their sockets. <b>Make sure to match the orientation with the notch on the socket.</b>
    <ul>
      <li>The LM358 has a dot in one corner — make sure it's in the "top left."</li>
      <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/20.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="The Op Amp">
      <li>The Noise2 chip has a notch and a dot — match the notch to the socket and silkscreen.</li>
      <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/21.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="The Heavylifter">
    </ul>
  </li>

  <li>Solder the power wires to the corresponding pads marked <code>+</code> and <code>−</code> on the PCB.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/22.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Power">

  <li>You're almost done! Reinsert the PCB and screw the jacks back onto the enclosure. Leave the back plate off for now so you can test it.
    <h3>The Pink and White is <i>loud</i> — start with your amp volume low!</h3>
    <ul>
      <li>If it's making sound — great! If not, double-check connections, power, and trimmer positions.</li>
      <li>The Pink and White outputs up to 5V — that’s nearly 5x a typical <a href="https://en.wikipedia.org/wiki/Line_level" target="_blank">line level signal</a>. Use caution with your (or anyone’s) gear.</li>
      <li>Try a continuity test if you have a multimeter.</li>
      <li>Still stuck? Email me and I’ll try to help.</li>
    </ul>
  </li>

  <li>You may notice the PCB gets grimy over the course of the build. Dust, fingerprints, and dander accumulate — even if you're wearing those YouTube-standard black nitrile gloves. Clean it with 90% isopropyl alcohol and a soft toothbrush. I use a spray bottle, spritz it on, and gently scrub. A few passes should do it.</li>
  <img src="https://raw.githubusercontent.com/ge-ep/pinkandwhite/main/images/24.jpg" style="width:49%; display:inline-block; vertical-align:top;" alt="Gleaming!">

  <li>Once you've confirmed everything works, screw on the enclosure's back plate. If you’ve got anti-slip feet, throw those on too.</li>
</ol>
