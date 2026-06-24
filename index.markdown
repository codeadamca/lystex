<script src="form.js"></script>
<style>@import url("//readme.codeadam.ca/readme.css");</style>

![LYSTEX Logo](images/lystex-logo-low.png)

<!--
<div style="position: relative; width: 100%; max-width: 100%; height: 0; padding-bottom: 56.25%; margin-bottom: 20px;">
    <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" controls poster="images/poster.png">>
        <source src="videos/demo.mp4" type="video/mp4">
    </video>
</div>

> <small>Music by: https://www.bensound.com/fre    e-music-for-videos License code: 38VOT6UMWYZVD3FW Artist: : Yunior Arronte</small>

---
-->

## What is LYSTEX?

[![LYSTEX](images/lystex-low.png)](images/lystex-high.png)

[LYSTEX](https://lystex.codeadam.ca) is a playable video game made entirely out of LEGO® bricks. Players use an Xbox controller to navigate a space rover through a series of puzzles to the bunker before the planet explodes.

### Game Stack

The playable game environment is built using LEGO® bricks. The interactive elements use LEGO® Spike™ and Pybricks (a custom firmware for the LEGO® Spike™).

[![LYSTEX Map](images/map-low.png)](images/map-high.png)

The LYSTEX Player App ia a companion application delivering video hints to the player as checkpoitns are completed. This app is building using vanillia HTML and JavaScript, [Firebase](https://firebase.google.com/), and [GitHub Pages](https://pages.github.com/). 

[![LYSTEX Control App](images/app-control.png)](https://lystex.codeadam.ca/player/control.html) [![LYSTEX Player App](images/app-player.png)](https://lystex.codeadam.ca/player/player.html)

1. Open both apps in separate browser windows
2. Click the player app to allow audio
3. In the control apop, click a video tpo play or modify the timer 

### Game Design

Original design drawing includes puzzles and location of key LEGO® components. 

[![LKYSTEX Original Design](images/design-low.png)](images/design-high.png)

### Game Setup

Follow these steps to get the game up and running:

1. Plug the two USB hubs (black chords) into the wall.
2. Ensure there are nine USB cables connecting the USB hubs to the nine Spike hubs mounted to the bottom of the plywood.
3. Turn on the nine Spike hubs by pressing the primary button for about one second. The Spike hubs will emit a 3x3 grid when turned on.
4. Activate the code on each Spike hub by pressing the primary button again. The Spike hubs will animate a rotating square when the code is running. 

    If the hub returns to a 3x3 grid after activating the code, this means the code is encountering an error. Ensure all the cables are pluggin in firmly and try again. If the problem repeats, the issue will need to be diagnosed with [Pybricks](https://code.pybricks.com/).
    
5. Turn on the Essentials hub on the rover by pressing the primary button once.
6. Turn on the Xbox controller, the Xbox logo will blink.
7. Activate the code on the Essentials hub by pressing the primary button again. The Xbox logo will turn to a solid light. 

    The code on the Essentials hub will take approximately 30 seconds to reset the escape room puzzles and the driving controls to start working.

8. Begin playing!

### Video Queues

If you want to use the video queues follow these steps:

1. Plug a Chromebook into the wall, turn on, and login using the password *polytchnic*.
2. Connect the speakers and adjust the volume.
3. Ensure the Chromebook will not activate the sdreensaver when plugged in.
4. Open a browser on the Chromebook and visit the [Lystex Player](https://lystex.codeadam.ca/player/player.html).
5. Click the fullscreen button, flip the keyboard so the Chromebook is in tablet mode, and place the Chrombook on top of the bunker.
6. Open a browser on a second device (a laptop or cellphone) and open the [Lystex Controller](https://lystex.codeadam.ca/player/control.html).
7. Click a video on the second device to confirm the two devices are interacting. 

### Solution

To solve the escape room, follow these steps:

1. First we need to use the power station to supply power to the bridge. Drive the rover to the first pink power building in the back left corner and rotate the radar to point at the bridege, the bridge structure and groud will light up. Use the left and right bumper to rotate power radar.
2. Next, we need unlock the gate. Notice the blue and yellow symbol on the bridge. Drive to the first light station and 

> <small>LEGO® is a trademark of the LEGO Group of companies which does not sponsor, authorize or endorse this site.</small>

---

## Make Contact

Reach out to request a custom interactive LEGO® experience:

<form id="contactForm" action="#" method="post" style="max-width:800px;">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name">
    <br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email">
    <br>
    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="5"></textarea>
    <br>
    <button type="submit">Send</button>
</form>

<div class="components" id="resources">--resources--</div>
<script src="https://cdn.codeadam.ca/components@1.0.0/components.js"></script>

---

<a href="https://codeadam.ca">
<img src="https://cdn.codeadam.ca/images@1.0.0/codeadam-logo-coloured-horizontal.png" width="100">
</a>

<style>
button {
    background: #0366d6;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 4px;
    font-size: 1em;
    cursor: pointer;
    transition: background 0.2s;
}

button:hover {
    background: #024ea2;
}

input, textarea {
    border: 2px solid #e1e4e8;
    background: #f6f8fa;
    padding: 5px;
    box-sizing: border-box;
    border-radius: 4px;
    margin-bottom: 8px;
    width: 100%;
    font-size: 1em;
}


</style>
