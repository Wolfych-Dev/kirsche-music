### Kirsche Music
Full music production environment.

Seven-page DAW inspired by classic trackers and modern DAWs: Channel Rack, Playlist, Piano Roll, Mixer, Automation, Perform, Audio Editor. Built on Web Audio, AudioWorklet, and WebAssembly (WCLAP) under the hood. Export to WAV, MP3, OGG, MIDI, or stems.
### Site
[![Launch Web App](https://img.shields.io/badge/Launch-Web_App-3d8bd9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://wolfych-dev.github.io/kirsche-music/)

### AppImage
[![Download AppImage](https://img.shields.io/badge/Download-AppImage-e8613c?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/Wolfych-Dev/kirsche-music/releases/download/release/Kirsche-Music.AppImage)

## Features

## Channel Rack
Step sequencer with note, velocity, probability, and ratchet edit modes. Euclid fill, randomize, rotate, invert, fill patterns. Channel types: built-in drum synths, modular synth, sampler, and WCLAP (WebAssembly CLAP) instruments. Per-channel mute and solo.

## Playlist
PAT / SONG / LIVE modes. Pattern tracks, three automation lanes, three audio lanes, section markers, loop region, punch in/out. Track folders with hide/show, per-lane mute/solo and draggable heights. Audio clips with WSOLA time-stretch, pitch-shift, reverse, normalize, fade handles, grouping, and take lanes. Multi-monitor pop-out windows.

## Piano Roll
Ghost notes, slide notes, scale highlighting and snap, velocity lane with multi-select and marquee. Chorder with inversions and voicings. Stamp / riff machine: arpeggio, rhythm figure, scale run, random riff. Strum, flam, chop, quantize, humanize. Chord detection. Zoom, copy/paste/duplicate. Note colors by velocity or channel, multi-channel overlay.

## Mixer
Up to 125 inserts with a drag-to-connect routing graph and acyclic checks. Plugin delay compensation, sends, sample-accurate sidechain. Around 25 built-in effects including Multiband Comp, OTT (upward + downward per band), Gross Beat (stutter / tape-stop). True-stereo path, per-insert CPU and latency meters, clip and intersample-peak meter.

## Synth
Sub, FM (4-operator matrix), additive (16 partials), wavetable, granular, physical modeling (Karplus-Strong / membrane), and noise engines. Up to 7-voice unison, hard sync, ring mod, per-source ADSR, sub oscillator, two filters with envelope tracking, LFO modulation matrix, glide / legato, arpeggiator, oversampling up to 8×.

## Sampler
Zones with key and velocity mapping, round-robin, loop points with crossfade, reverse, time-stretch, pitch and filter envelopes. Auto-slice by transients or chop points. Import SFZ and SF2. Real-time mic / line recording with latency compensation, overdub, and take lanes. Edison-style Audio Editor with a non-destructive edit list.

## Perform
Clip launcher with pads, exclusive mode, and next-bar quantized triggering via keys 1–9.

## Workflow
Undo tree with branch switching and a history graph. Autosave. Theme editor (14 CSS variables, contrast check, import/export). Customizable hotkeys with search and import/export. MIDI Learn for any parameter. Sample browser with persistent folders via the File System Access API.

## Deliver
Offline render through the real synth engines in a Web Worker pool. WAV (44.1/48/96 kHz, 16/24-bit), MP3 (CBR up to 320k), OGG Vorbis (VBR), stems as ZIP, MIDI with automation as CC7/CC10 plus extra CC lanes. Project save/load as JSON or as a self-contained `.zip` bundle with audio, samples, and optional WCLAP plugins.
