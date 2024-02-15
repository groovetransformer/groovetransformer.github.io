---
layout: about
title: about
permalink: /
subtitle: <a href='#'>NIME '24</a>. Supplementary Documents.

profile:
  align: center
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p></p>
    <p></p>
    <p></p>

news: false # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

This website is prepared as an accompaniment to the paper submitted to `NIME 2024` conference. 

In this website, we have compiled a number of demos, as well as, all the source codes/files used for developing both the [Eurorack]({{ site.baseurl }}/Eurorack/) module as well as the [VST/Standalone]({{ site.baseurl }}/VST3/) clone of the module.

---
### Supplementary Material
---

To access the provided supplementary material for the `Eurorack` version, please refer to the 
[Eurorack]({{ site.baseurl }}/Eurorack/) page. In this page, you will find the [source code]({{ site.baseurl }}/Eurorack/#source-code), [pcb]({{ site.baseurl }}/Eurorack/#pcb),
and [faceplate]({{ site.baseurl }}/Eurorack/#faceplate) resources.

To access the provided supplementary material for the `VST/Standalone` version, please refer to the 
[VST3]({{ site.baseurl }}/VST3/) page. In this page, you will find the `VST3` [source code]({{ site.baseurl }}/VST3/#source-code) of the software version of the eurorack module. 

---
### Demos
---

The following recordings have been prepared by the authors of the paper. Live concert recordings will be uploaded soon as well. 

---
#### Live Accompaniment in Virtual Eurorack Environment

<video width="600" height="400" controls>
  <source src="/assets/video/VCV_VST_Keyboard_LowRes.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


Setup:

- An arpegiating bassline played back using an ableton stock plugin
- An Arturia Polybrute synthesizer played live. 
- `GrooveTransformer`receiving MIDI grooves from both the arpegiated basseline and the live performance on the synthesizer

Drum Synthesis:

- [Cardinal](https://github.com/DISTRHO/Cardinal) Virtual Eurorack Environment
- Cardinal receives the generated drums, strips the gats and velocities to trigger the modules
- Triggers used to activate voices while velocities are used either as VCA gains and/or synthesis parameters. 
- While 9 voices are generated, some voices were grouped together
- Typical Kick and Snare (with velocity controled VCAs) were used for kick and snares
- A single FM Operator was used for all hats (closed and open). The decay of the envelop was controlled by the type of trigger
- For Rides and Toms, two separate Mutable Instrument Plait modules were used.

---

#### Eurorack Jams

##### Jam 1

##### Jam 2

##### Jam 3


---

#### Module Videos (Exploring Synthesis)
<video width="320" height="240" controls>
  <source src="/assets/video/GT Demo_compressed.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

`Hardware 1`

<video width="320" height="240" controls>
  <source src="/assets/video/20230621_112345_compressed.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

`Hardware 2`

<video width="320" height="240" controls>
  <source src="/assets/video/20230621_114659_compressed.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---
#### Additional Jams (Audio Only)


##### 1

Live accompaniment generated based on a live synth performance. Drums synthesized using Microtonic layered with Acoustic drums

<audio controls>
  <source src="{{ '/assets/audio/2_Feb12_CardinalAndAcousticDrumsLayered_Polybrute.mp3' | relative_url }}" type="audio/mp3">
  Your browser does not support the audio element.
</audio>

##### 2

Here we play a sequence of chords (MIDI) and also play the synthesizer live. The drum accompaniments are generated using a modular patch and near the end using acoustic drums as well.

<audio controls>
  <source src="{{ '/assets/audio/1_Feb12_CardinalVCV_Polybrute.mp3' | relative_url }}" type="audio/mp3">
  Your browser does not support the audio element.
</audio>

##### 3

Here we play a sequence of chords (MIDI) and also play the synthesizer live. The drum accompaniments are generated using a modular patch and near the end using acoustic drums as well.

<audio controls>
  <source src="{{ '/assets/audio/3_Feb8_Acoustic Drums_Polybrute.mp3' | relative_url }}" type="audio/mp3">
  Your browser does not support the audio element.
</audio>


##### 4

In this one, we have programmed 4 sequences on the Electron Analog Four synth which are enabled/disabled during the performance. These sequences drive the accompaniment engine while we perform live on a separate synth as well. At times, we don't feed the groove of the live performance to the system so that the groove is stable and more conditioned on the programmed sequences

<audio controls>
  <source src="{{ '/assets/audio/4_Feb2_A4SequencesAndPolybruteAcousticDrums.mp3' | relative_url }}" type="audio/mp3">
  Your browser does not support the audio element.
</audio>

##### 5 & 6

These jams were done entirely in Ableton. However, we live looped many parallel midi sequences and also played live patterns that were fed to the accompaniment generator. All drums were synthesized using an acoustic drum kit

<audio controls>
  <source src="{{ '/assets/audio/5_Jan12_MultipleSequencesLoopedAbletonPush2.mp3' | relative_url }}" type="audio/mp3">
  Your browser does not support the audio element.
</audio>

<audio controls>
  <source src="{{ '/assets/audio/6_Jan17_SameSetupAs5.mp3' | relative_url }}" type="audio/mp3">
  Your browser does not support the audio element.
</audio>


