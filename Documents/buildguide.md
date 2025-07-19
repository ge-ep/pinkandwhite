<h1>Build Guide</h1>
<p>Here's my suggested build guide for the Pink and White noise generator. It would be a good idea to read through the buiild guide from top to bottom <i>before</i> you start building. Just sayin'. 
  If you have questions or get stuck somewhere, email me: <i>knifeinthetoaster (at) gmail (dot) com.</i></p>
<br>
<h2>Tools:</h2>
<p>You'll need the following tools:</p>
<p><li>A soldering iron</li>
   <li>Solder</li>
   <li>Some form of tip cleaner (a wet soldering sponge or brass wool (my prefered option))
   <li>Wire snippers (flush cut snippers are probably best, but anything roughly craft sized will do. You could even get away with using scissors if you're in a pinch</li></li></p>
<p>If you are going to install the Pink and White in a 125B Hammond-style enclosure you'll also need:</p>
<ul><li>A drill of some kind, your standard power drill will do just fine</li>
    <li>Drill bits (I suggest something small to drill a pilot hole and a stepped drill bit)</li>
    <li>A Philips-head screw driver</li>
    <li>A center punch and a hammer</li>
    <li>A marker or a pencil</li>
    <li>A ruler or measuring tape</li></ul>
<p>The following would also be helpful, but aren't crucial:</p>
<p><li>Helping hands</li>
   <li>Tip tinner</li>
   <li>Multimeter</li>
   <li>Flux and some desoldering braid in case you need to remove a component or remove some solder from an overzealous join</li>
   <li>A bright light (it really helps when you can see what you're doing)</li>
   <li>Anti-static mat</li>
   <li>90% isopropyl alcohol and a clean toothbrush. You can use these to clean the PCB after you're done building</li></p>
   <br>
   <h2>Part 0: Gather Ye Together Yon Components and Hear My Tale</h2>
   <p>Start by gathering together all of your stuff; your tools, all the components and make sure you aren't missing anything. It also helps to have a clean worksurface </p>
   <p><li></li></p>
   <h2>Part 1: Let the Soldering ..... COMENCE!</h2>
   <p>Generally, the rule with solding PCBS is <i>low to high</i>, so we start with the components that lay flattest against the PCB, and work our way up. So, with that in mind
   <p><ol>
      <li>Start with the three resistors</li>
      <li>And then the diode <i>making sure to match the <b>stripe on the diode</b> with the <b>stripe on the PCB</b></i></li>
      <li>Next we'll flip the PCB over and solder in the two trimmers; I like to do these now since they're the only thing on that side of the board and you'll have more space to work with.</li>
      <li>The IC sockets are next. Make sure to match the notch on the socket to the notch on the silkscreen.
      <ul><li>I like to solder one pin then check to ensure the socket is flat against the PCB. If it isn't just reheat the solder on the pin while applying gentle pressure. You should feel the socket seat 
      itself flat against the PCB</li></ul>
      <li>The voltage regulator comes next. Insert the legs and gently bend it down so the plastic housing rests against the pcb. You can use the outline on the silkscreen as a guide. </li>
      <li>Now you can do the 100nf capacitors.</li>
      <li>Then the 1nf capacitor</li>
      <li>And then the 10uf capacitor
          <ul><li><b>Please note</b>: the 10uf capacitor is polarized, you need to match the short leg of the capacitor to the filled section of the footprint on the silkscreen</ul></li>
<h2>Part 2: Put it in something</h2>
      <li>Now you'll need to drill holes for the audio jacks and the power input. The centerpoints of the audio jacks are roughly 2.8cm apart, so my suggested process is find the center point of the
          enclosure and make two marks 1.4cm apart from the center. As with all things, measure twice and cut (or, in this case, drill) once. I also recommend checking the placement of the holes agains the 
          PCB.</li>
      <li>Using a center punch, mark the center of your two holes and then using a small drill bit, drill pilot holes. <b>Go slow to ensure the bit doesn't slide out of place)</b> </li>
      <li>Next slowly increase the size of the hole, checking to see if the audio jacks will fit. It doesn't have to be exact, so I just drill and check until I have a good fit.</li>
      <li>Once both holes are drilled, check to see that you got it right. Place the audio jacks in the PCB matching the notches. Next, carefully insert the jacks into the holes you drilled in the enclosure
          and screw them finger-tight to the enclosure. If you've measureed correctly, everything should fit nicely.</li>
      <li>If everything fits as expected, solder the audio jacks to the board. Once the jacks are soldered, unscrew them from the enclosure.</li>
      <li>Now you need to install the power input. To do this you'll need to drill another hole in the enclosure. I suggest drilling a hole in the side furthest away from the power input on the PCB, especially if you're planning to use battery power.</li>
      <ul><li>Follow the same process as steps 9 - 11 above.</li></ul>
      <li>Install the power input and solder solder the provided wires and battery snap as shown <a href="" target="_blank">here</a>
      <ul><li>This is the standard for effects pedals (i.e. 9v center negative), but you don't have to connect it that way, if you'd prefer center positive, search "(9v center positive wiring -ai" and you'll likely find what you're looking for. I wanted to stick with the 9v center negative wiring since it's most common for guitar effects. If you already have guitar effects you'll probably have things on hand you can use to power it.</li></ul></li>
     <li>If you haven't already done so, put the chips in their corresponding sockets. <b>Make sure to match the orientation of the ICs with the notch on the top of the socket</b>. The LM358 IC has a dot in one corner, so make sure the dot is in the "top left". The Noise2 IC has a notch (as well as a dot) so just match the notch on the chip to those on the socket and silkscreen.</li>
      <li>Now solder the wires from the power input to the corresponding inputs on the PCB; they marked with + and - for clarity.</li>
     <li>You're just about done! Now you can put the PCB back in the enclosure and screw on the jacks. Leave the back plate of the enclosure off for now, because we need to test it to ensure it's all working as expected. You'll need something to hear if it's making any sound, an amp or a mixer or something like that. <h3>The Pink and White is <i>loud</i> so start with the volume very low!</h3> If it's making sound, that's great! If not, check that everything is plugged in and powered on and that the trimmers aren't set to zero.</li>
     <ul><li>The Pink and White will output somewhere between 0 and 5v with the trimmers turned all the way up. <i>This means it will be nearly 5x louder than your average <a href="https://en.wikipedia.org/wiki/Line_level" target="_blank">line level signal</i></a>, so make sure to consider that when using the Pink and White with your (or someone else's) gear. The trimmers come set to the mid-point, but you can easily adjust them in either direction with a screw driver (or by hand, if you're dextrous enough).</li>
         <li>You may also want to try a continuity test if you have a multimeter</li>
         <li>If you just can't get it working, send an email to the address above and I'll do my best to help.</li></ul>
      <li>Once you've tested it and determined that it's working, screw on the bottom of the enclosure and you're done. If you have some anti-slip feet, put those on too.</li>
   </ol>
