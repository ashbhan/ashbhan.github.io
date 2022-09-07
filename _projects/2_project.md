---
layout: page
title: Passive Haptic Learning
description: Creating vibrotactile gloves to accelerate piano learning
img: assets/img/glovedhands.jpg
importance: 1
category: ongoing
---


Currently, I have been working at the Contextual Computing Group at Georgia Tech's School of Interactive Computing. Under the advisement of Thad Starner, I have been working on the passive haptic learning project. 

Passive haptic learning is based on the idea that individuals can learn movements with little effort through a series of vibrotactile instructional cues. The application of this method that I am currently working on is learning the piano. This relies on using a pair of vibrotactile gloves (gloves with haptic motors located just above the knuckle), to apply cues to the fingers based on the actual fingerings of a song. Currently, our research efforts are focused on studying the idea of passive haptic reheresal, where passive haptic learning is used in tandem with active learning (traditional piano learning methods), to further increase retention and acquistion of piano skills.

My specific contributions to the project are with both the firmware and hardware parts of the project. In terms of hardware, I am involved with the current assembly and debugging of the system. In the next few months, I will be doing a revision of the hardware which will include a new PCB design and it's physical integration into the glove. In terms of firmware, I have programmed the gloves from the ground up, including setting up Bluetooth LE connections between the gloves and with a tablet and translating fingering patterns into actual haptic cues. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/gloveguts.png" title="glove brains" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Inside of the current version of the gloves
</div>

I will be presenting this work at the UbiComp/ISWC 2022 conference in Atlanta, GA as part of the Poster/Demo track. If you are interested in learning more about the system, you can view the demo submission video [here](https://youtu.be/LdF_jn4hWHc), and read the demo proposal paper [here](https://https://doi.org/10.1145/3544793.3560321). 
