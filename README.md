# Ableton Live AI Prompts

Created by [THE KEYPALS](https://www.thekeypals.com/) music collective, these prompts help you use AI with our custom Ableton Live setup. They work alongside both our [Project Template](https://github.com/thekeypals/ableton-live-project-template) and [User Library](https://github.com/thekeypals/ableton-live-user-library).  

The goal is to speed up your workflow by giving AI the project context and plugin parameters it needs, saving you from typing them out each time. 

Bookmark this page with `Ctrl` + `D` (Windows) or `Cmd` + `D` (Mac).

## AI Clients

You can copy and paste these prompts into any of the following AI platforms:

- [ChatGPT](https://chatgpt.com/)  
- [Gemini](https://gemini.google.com/)  
- [Claude](https://claude.ai/)  
- [Copilot](https://copilot.microsoft.com/)  

## Table of Contents

- [Project Setup](#project-setup) – copy these four sections into your AI chat when starting a project
  - [Project Details](#project-details)
  - [DAW Behaviour Notes](#daw-behaviour-notes)
  - [Song Structure](#song-structure)
  - [Device Parameters Instructions](#device-parameters-instructions)

- [User Presets](#user-presets) – devices and racks included in the Project Template and User Library  
  - [Analyser Rack](#analyser-rack)  
  - [Automation](#automation)  
  - [Backing Vocals Sidechain](#backing-vocals-sidechain)  
  - [Compressor Rack](#compressor-rack)  
  - [Delay Rack](#delay-rack)  
  - [Drum Buss](#drum-buss-user-preset)  
  - [EQ Rack](#eq-rack)  
  - [Gain Input](#gain-input)  
  - [Gain Output](#gain-output)  
  - [Glue Compressor](#glue-compressor-user-preset)  
  - [Kick Sidechain](#kick-sidechain)  
  - [Lead Vocals Sidechain](#lead-vocals-sidechain)  
  - [Master Buss Rack](#master-buss-rack)  
  - [Overdrive](#overdrive-user-preset)  
  - [Reverb Rack](#reverb-rack)  
  - [Spectrum](#spectrum-user-preset)  
  - [Tuner](#tuner-user-preset)  
  - [Vocal Rack](#vocal-rack)  

- [Ableton Live Default Plugins](#ableton-live-default-plugins) – all stock devices for quick reference  
  - [Auto Filter](#auto-filter)  
  - [Chorus-Ensemble](#chorus-ensemble)  
  - [Compressor](#compressor)  
  - [Delay](#delay)  
  - [Drum Buss](#drum-buss-default-plugin)  
  - [EQ Eight](#eq-eight)  
  - [Erosion](#erosion)  
  - [Gate](#gate)  
  - [Glue Compressor](#glue-compressor-default-plugin)  
  - [Grain Delay](#grain-delay)  
  - [Limiter](#limiter)  
  - [Multiband Dynamics](#multiband-dynamics)  
  - [Overdrive](#overdrive-default-plugin)  
  - [Reverb](#reverb)  
  - [Saturator](#saturator)  
  - [Spectrum](#spectrum-default-plugin)  
  - [Tuner](#tuner-default-plugin)  
  - [Utility](#utility)  

- [Third-Party Plugins](#third-party-plugins) – external VST/AU devices commonly used with Live  
  - [Youlean Loudness Meter](#youlean-loudness-meter)  

## Project Setup

Copy and paste these four blocks into AI in the order shown.

### Project Details

Copy this block into AI at the start of any project to give it context.

**To copy the text, click the copy icon in the top right of the code block.**

Note that when setting levels, you may need to remind the AI what your kick and bass are peaking at to ensure accurate feedback.

[Next Step → DAW Behaviour Notes](#daw-behaviour-notes)

```text
Project Details
- Song Title: 
- Tempo (BPM): 
- Key: 
- Time Signature: 
- Genre/Style: 
- Reference Songs: 
- DAW: Ableton Live 12 (THE KEYPALS Project Template)

Template Groups (White is always used for sub-groups)
- Reference (White) – chords, reference tracks
- Percussion (Red / Pink) – e.g. drums, extra percussion
- Bass (Orange) – e.g. sub, mid, synth bass
- Guitars (Yellow) – e.g. rhythm, lead, acoustic, electric
- Keys (Green) – e.g. piano, synths, pads
- Strings (Bright Blue) – e.g. orchestral, synthetic
- Brass (Blue) – e.g. trumpets, trombones, horns
- Sound FX (Purple) – e.g. transitions, risers, atmospheres
- Misc (Violet) – unique or experimental layers
- Vocals (Slate Grey) – e.g. lead, backing vocals
- Sends/Returns (White) – reverb, delay, shared effects
- Master Track (White) – final mix processing and monitoring

Gain Staging Guide
- Kick drum (if present) is the anchor, peaking around –12 dB to –10 dB
- Bass typically sits just below the kick to maintain low-end clarity
- Other instruments and vocals balanced relative to kick/bass
- The master track should peak around –6 dB before limiters
```

##### [Back to Top](#table-of-contents)

### DAW Behaviour Notes

Copy this block into AI to ensure parameter suggestions match Ableton Live controls.

[Next Step → Song Structure](#song-structure)

```text
DAW Behaviour Notes

- Ableton Live send levels use dB, not percentages
- Send range is -inf dB - 0 dB
- Panning is L - R on a 50L - Centre - 50R scale
- Use Ableton Live parameter names exactly as written in the UI
```

##### [Back to Top](#table-of-contents)

### Song Structure

Copy this block into AI to describe the song arrangement (add lyrics if relevant).

[Next Step → Device Parameters Instructions](#device-parameters-instructions)

```text
Song Structure

INTRO  
- Bars: [e.g. 1–8]  
- Time Signature: [e.g. 4/4]  
- Tempo: [e.g. 120 BPM]  
- Chords / Harmony: [e.g. 4x G C D G]  
- Notes: [e.g. Spoken word / Atmosphere / Instrumental idea]  
- Lyrics: [optional lyric lines here]  

VERSE 1  
- Bars:  
- Time Signature:  
- Tempo:  
- Chords / Harmony:  
- Notes:  
- Lyrics:  

CHORUS 1  
- Bars:  
- Time Signature:  
- Tempo:  
- Chords / Harmony:  
- Notes:  
- Lyrics:  

VERSE 2  
- Bars:  
- Time Signature:  
- Tempo:  
- Chords / Harmony:  
- Notes:  
- Lyrics:  

CHORUS 2  
- Bars:  
- Time Signature:  
- Tempo:  
- Chords / Harmony:  
- Notes:  
- Lyrics:  

BRIDGE  
- Bars:  
- Time Signature:  
- Tempo:  
- Chords / Harmony:  
- Notes:  
- Lyrics:  

CHORUS 3  
- Bars:  
- Time Signature:  
- Tempo:  
- Chords / Harmony:  
- Notes:  
- Lyrics:  

OUTRO  
- Bars:  
- Time Signature:  
- Tempo:  
- Chords / Harmony:  
- Notes:  
- Lyrics:  
```

##### [Back to Top](#table-of-contents)

### Device Parameters Instructions

Copy this block into AI to define how device parameters should be used during the project.

[Next Step → Choose a Device or Rack](#user-presets)

```text
Device Parameters Instructions

- Treat all parameter values as coming from real Ableton Live controls
- Only reference parameters that exist on the devices provided by the user
- When discussing a device, use the parameter list supplied in the prompt
- Never invent controls, values, ranges or modes that are not in the user’s text
- Give suggestions using the units shown in Ableton Live (dB, %, ms, Hz, L/R etc)
- If more information about a device is needed, ask the user which block to reference

Parameter Sources
- User Presets: devices and racks from the Project Template and User Library
- Ableton Live Default Plugins: all stock Ableton devices
- Third-Party Plugins: external VST/AU devices used in the project
```

##### [Back to Top](#table-of-contents)

## User Presets

### Analyser Rack

```text
PLUGIN CHAIN: Analyser Rack (Analyser Rack.adg)  
Type: Device Group (.adg)  

Purpose  
- Used on both the master track and reference track for consistent analysis  
- Splits the signal into low, mid and high ranges for quick soloing  
- Provides mono monitoring and real-time frequency spectrum display  

PLUGIN 1: Auto Filter Legacy — Low End  
- Toggle: On/Off (Shortcut: `p`) | Isolates low-frequency content for monitoring (sub balance)

PLUGIN 2: Auto Filter Legacy — Mids  
- Toggle: On/Off (Shortcut: `[`) | Isolates mid-frequency content for monitoring (body and presence)

PLUGIN 3: Auto Filter Legacy — Highs  
- Toggle: On/Off (Shortcut: `]`) | Isolates high-frequency content for monitoring (brightness and air)

PLUGIN 4: Utility (Mono)  
- Toggle: On/Off (Shortcut: `=`) | Switches signal to mono for phase and centre balance checks

PLUGIN 5: Spectrum  
- Purpose: Provides real-time frequency analysis of the signal
```

##### [Back to Top](#table-of-contents)

### Automation

```text
PLUGIN: Utility (Automation.adv)  
Type: Device Preset (.adv)  

Purpose  
- Automates core mix parameters such as volume, pan and stereo width without altering gain staging  
- Keeps automation independent for organised and flexible mix control  

INPUT  
- Left/Right Phase | Inverts selected channel polarity for automation-based phase effects or correction  
- Channel Mode: Left / Stereo / Right / Swap | Chooses or swaps signal channels  
- Stereo Width: 0% - 400% | Automates stereo image width (0% mono, 100% original, >100% widened)  
- Mono: On/Off | Automates mono conversion for phase or reference checks  
- Bass Mono: On/Off | Enables mono conversion of low frequencies  
- Bass Mono Frequency: 50 Hz - 500 Hz | Sets crossover frequency for Bass Mono  
- Bass Mono Audition | Solos low-frequency range for tuning Bass Mono settings  

OUTPUT  
- Gain: -∞ dB - 35.0 dB | Automates overall output level for mix transitions  
- Balance: 50L - 50R | Automates stereo balance and panning  
- Mute: On/Off | Toggles output muting for mix automation  
- DC: On/Off | Removes DC offset; normally left On in automated chains
```

##### [Back to Top](#table-of-contents)

### Backing Vocals Sidechain

```text
PLUGIN: Compressor (Backing Vocals Sidechain.adv)  
Type: Device Preset (.adv)  

Purpose  
- Used to create space for the lead vocal by reducing backing vocal levels when the lead is active  
- Not placed on the lead vocal track or buss — instead, insert on backing vocal groups or layers that should duck slightly when the lead vocal plays  
- Maintains vocal clarity and separation in the mix through gentle, transparent compression  

SIDECHAIN CONTROLS  
- Headphone Icon: On/Off | Solos the sidechain input for monitoring  
- External: On/Off | Enables sidechain input from an external source (e.g. Lead Vocals track)  
- Source: [List of available tracks / inputs] | Selects external track used as the sidechain trigger  
- Mix: 0% - 100% | Balances internal and external sidechain input for detection  
- SC Gain: -∞ dB - 24 dB | Adjusts level of the incoming sidechain signal  

SIDECHAIN EQ  
- SC Filter: On/Off | Activates sidechain filter to limit detection to a specific frequency range  
- Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Sets filter shape for sidechain signal  
- Frequency: 30 Hz - 15 kHz | Defines frequency focus of the sidechain detector  
- Q (Resonance): 0.10 - 12.00 | Controls sidechain filter bandwidth or steepness  

COMPRESSOR SETTINGS  
- Ratio: 1:1 - ∞:1 | Determines compression strength above the threshold  
- Attack: 0.01 ms - 1 s | Sets response time before compression begins  
- Release: 1 ms - 3 s | Sets recovery time after compression ends  
- Auto Release: On/Off | Automatically adjusts release time to input dynamics  
- Threshold: -∞ dB - 6 dB | Defines the input level at which compression starts  
- GR Meter: Visual | Displays real-time gain reduction amount  
- Output Gain: -36 dB - 36 dB | Controls final signal level after compression  
- Knee: 0 dB - 18 dB | Smooths transition between uncompressed and compressed signal  
- Makeup: On/Off | Enables automatic level compensation (before Output Gain)  
- Peak: Mode button | Responds to short, transient peaks  
- RMS: Mode button | Responds more gradually to overall signal level  
- Expand: On/Off | Activates upward expansion for increased dynamics  
- Dry/Wet: 0% - 100% | Blends compressed and unprocessed signal for parallel control
```

##### [Back to Top](#table-of-contents)

### Compressor Rack

```text
PLUGIN: Compressor Rack (Compressor Rack.adg)  
Type: Device Group (.adg)  

Purpose  
- Custom compressor rack combining essential dynamics controls and sidechain options for flexible audio shaping  
- Designed for quick access to core parameters via mapped macros  

MACRO CONTROLS (MAPPED TO COMPRESSOR PARAMETERS)  
- Macro 1: Comp Thresh → Threshold | Sets the input level where compression begins  
- Macro 2: Comp Ratio → Ratio | Adjusts compression intensity  
- Macro 3: Comp Attack → Attack | Controls onset time before compression engages  
- Macro 4: Comp Release → Release | Controls time taken for signal to return to normal  

SIDECHAIN CONTROLS  
- Sidechain Listen: On/Off | Solos sidechain input for monitoring  
- External Sidechain: On/Off | Enables input from external signal source  
- Source: [Track/Input List] | Selects signal used to trigger compression  
- Mix: 0% - 100% | Balances internal and external sidechain signal for detection  
- Sidechain Gain: -∞ dB - 24 dB | Adjusts sidechain input level  

SIDECHAIN EQ  
- SC Filter: On/Off | Enables frequency-specific sidechain detection  
- Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Selects sidechain filter type  
- Frequency: 30 Hz - 15 kHz | Defines frequency range affecting compression  
- Q (Resonance): 0.10 - 12.00 | Sets bandwidth or sharpness of the sidechain filter  

COMPRESSOR SETTINGS  
- Ratio: 1:1 - ∞:1 | Determines compression strength above threshold  
- Attack: 0.01 ms - 1 s | Sets how quickly compression starts  
- Release: 1 ms - 3 s | Sets how quickly compression ends  
- Auto Release: On/Off | Automatically adjusts release time for smoother response  
- Threshold: -∞ dB - 6 dB | Defines input level at which compression begins  
- Gain Reduction: Visual | Displays real-time gain reduction  
- Output Gain: -36 dB - 36 dB | Adjusts post-compression output level  
- Knee: 0 dB - 18 dB | Controls smoothness of compression onset  
- Makeup Gain: On/Off | Automatically compensates gain lost through compression  
- Peak Mode: — | Responds to short transients  
- RMS Mode: — | Responds to average level for transparent compression  
- Expand Mode: On/Off | Enables upward expansion for dynamic enhancement  
- Dry/Wet: 0% - 100% | Blends compressed and dry signal for parallel compression  
```

##### [Back to Top](#table-of-contents)

### Delay Rack

```text
PLUGIN CHAIN: Delay Rack (Delay Rack.adg)  
Type: Device Group (.adg)

Purpose  
- Multi-device rack for creative delay processing and tone shaping  
- Combines Delay, Auto Filter, and Utility for modulation, filtering and stereo width control  
- Used for rhythmic echo design, textural movement and space creation  

PLUGIN 1: Delay (Delay.adv) – On by default  
- Delay Mode: Sync / Time | Switches between beat-synced and time-based delay  
- Beat Division: 1 / 2 / 3 / 4 / 5 / 6 / 8 / 16 | Sets delay time in 16th-note divisions (Sync mode)  
- Delay Time: 1.00 ms - 5.00 s | Sets delay time in milliseconds (Time mode)  
- Delay Offset: -33% - 33% | Adjusts timing offset for swing or stereo variation  
- Stereo Link: On/Off | Links left and right delay times  
- Feedback: 0.0% - 95% | Controls amount of signal fed back into input  
- Freeze: On/Off | Loops current buffer indefinitely  
- Filter: On/Off | Activates band-pass filter on feedback path  
- Filter Frequency: 50 Hz - 18 kHz | Sets centre frequency of filter  
- Filter Width: 0.50 - 9.00 | Controls bandwidth of filter  
- Modulation Rate: 0.01 Hz - 40 Hz | Sets modulation speed  
- Filter < Modulation: 0.0% - 100% | Modulates filter frequency  
- Delay < Modulation: 0.0% - 100% | Modulates delay time  
- Delay Transition Mode: Repitch / Fade / Jump | Determines time-change behaviour  
- Ping Pong: On/Off | Alternates repeats between left and right channels  
- Dry/Wet: 0.0% - 100% | Balances dry and delayed signals (set to 100% on return track)  

PLUGIN 2: Auto Filter (Auto Filter.adv) – Off by default  
- Filter Type: Low Pass / High Pass / Band Pass / Notch / Morph | Selects filter mode  
- Filter Frequency: 20 Hz - 20 kHz | Sets cutoff frequency  
- Filter Resonance: 0.0% - 100% | Boosts signal near cutoff for tonal emphasis  
- LFO Amount: 0.0% - 100% | Controls modulation depth  
- LFO Frequency: 0.10 Hz - 60 Hz | Sets LFO speed  
- Envelope Amount: -100% - 100% | Controls modulation via input envelope  
- Drive: 0.0% - 100% | Adds pre-filter saturation  
- Filter Circuit: SVF / DFM / MS2 / PRD | Selects circuit model for tonal character  
- Soft Clip: On/Off | Prevents harsh peaks  
- Output: -∞ dB - 0.0 dB | Adjusts filter output level  
- Dry/Wet: 0.0% - 100% | Mixes filtered and unprocessed signal  

PLUGIN 3: Utility (Utility.adv) – On by default  
- Left/Right Phase | Inverts selected channel polarity for phase correction or stereo effect  
- Channel Mode: Left / Stereo / Right / Swap | Selects or swaps channels  
- Stereo Width: 0% - 400% | Adjusts stereo field (0% mono, >100% widens image)  
- Mono: On/Off | Converts stereo input to mono  
- Bass Mono: On/Off | Sums low frequencies to mono for phase stability  
- Bass Mono Frequency: 50 Hz - 500 Hz | Defines mono crossover point  
- Gain: -∞ dB - 35 dB | Adjusts output gain  
- Balance: 50L - 50R | Pans output left or right  
- Mute: On/Off | Silences signal  
- DC: On/Off | Removes DC offset and inaudible low frequencies  
```

##### [Back to Top](#table-of-contents)

### Drum Buss

```text
PLUGIN: Drum Buss (Drum Buss.adv)  
Type: Audio Effect (.adv)

Purpose  
- Multi-function drum processor combining drive, transient shaping, compression and low-frequency enhancement  
- Adds punch, saturation and cohesive character to drum groups or full mixes  

MAIN CONTROLS  
- Drive: 0.0% - 100% | Applies harmonic saturation and distortion to the input signal  
- Distortion Type: Soft / Medium / Hard | Selects distortion curve (Soft = waveshaping, Medium = limiting, Hard = clipping with bass boost)  
- Trim: -∞ dB - 0.0 dB | Reduces input level to compensate for drive boost  
- Compression: On/Off | Engages fixed compressor before drive stage for added punch and glue  

SHAPING CONTROLS  
- Crunch: 0.0% - 100% | Adds additional mid-high frequency distortion for grit  
- Damping Frequency: 500 Hz - 20.0 kHz | Applies a low-pass damping filter after processing to smooth harsh highs  
- Transients: -1.00 - 1.00 | Enhances or softens transient content (positive = punchier attack, negative = softer response)  

BOOM SECTION  
- Boom Amount: 0.0% - 100% | Boosts low-end frequencies for weight and depth  
- Boom Frequency: 30.0 Hz - 90.0 Hz | Sets the centre frequency of low-end enhancement  
- Boom Decay: 0.0% - 100% | Controls sustain length of low-frequency boost  
- Force To Note: — | Locks Boom Frequency to the nearest MIDI note pitch  
- Boom Audition: On/Off | Solos low-end enhancement signal for tuning  
- Bass Meter: 0.0% - 100% | Displays real-time low-frequency activity  

OUTPUT  
- Output Gain: -40 dB - 3.0 dB | Adjusts processed output level  
- Dry/Wet: 0.0% - 100% | Balances between dry input and processed signal  
```

##### [Back to Top](#table-of-contents)

### EQ Rack

```text
PLUGIN: EQ Rack (EQ Rack.adg)  
Type: Device Group (.adg)  

Purpose  
- Simplified EQ rack containing a single EQ Eight for fast tone cleanup  
- Provides macro control for high-pass and low-pass filtering  
- Commonly used as a track-wide filtering utility to manage frequency space  

MACRO CONTROLS  
- Macro 1: Low Cut → Band 1 (High-pass filter)  
- Macro 2: High Cut → Band 8 (Low-pass filter)  

UNDERLYING DEVICE – EQ EIGHT  
- Frequency: 10 Hz - 22 kHz | Sets frequency of selected filter  
- Gain: -15 dB - 15 dB | Adjusts amplitude of active band (inactive for cuts/notches)  
- Filter Q: 0.10 - 18.0 | Controls resonance or bandwidth of selected filter  
- Filter Mode: Low Cut (12 / 48 dB) / Low Shelf / Peak / Notch / High Shelf / High Cut (12 / 48 dB) | Selects filter type  
- Filter Activator: On/Off per band | Enables or disables individual filters  
- Global Mode: Stereo / L/R / M/S | Chooses EQ processing mode  
- Adaptive Q: On/Off | Narrows Q as gain increases for natural analogue behaviour  
- Scale: -200% - 200% | Adjusts intensity of all band gains proportionally  
- Global Gain: -12 dB - 12 dB | Sets output level after EQ processing  
- Analyse: On/Off | Displays live output spectrum  
- Audition Mode: On/Off | Solos selected band for focused frequency listening  

DEFAULT ACTIVE BANDS  
- Band 1 (Low Cut): 30 Hz, 24 dB/oct slope | Removes subsonic rumble  
- Band 8 (High Cut): 22 kHz, 24 dB/oct slope | Smooths excessive high-end
```

##### [Back to Top](#table-of-contents)

### Gain Input

```text
PLUGIN: Utility (Gain Input.adg)  
Type: Device Group (.adg)  

Purpose
- Gain: -12.0 dB (fixed) | Reduces input level to prevent downstream clipping  
- All other parameters remain at default values  

Notes
- Some devices (e.g. Simpler) already apply –12 dB automatically, making this preset unnecessary on those tracks  
```

##### [Back to Top](#table-of-contents)

### Gain Output

```text
PLUGIN: Utility (Gain Output.adg)  
Type: Device Group (.adg)  

Purpose  
- Provides final output level control for the track or bus  
- Ensures the signal integrates smoothly into the overall project mix  

Notes  
- Use to balance each track relative to core mix elements such as bass and drums  
- Final level will vary depending on track role and arrangement context  
- Maintain sufficient headroom for processing within the master chain  
```

##### [Back to Top](#table-of-contents)

### Glue Compressor
<a id="glue-compressor-user-preset"></a>

```text
PLUGIN: Glue Compressor (Glue Compressor.adv)
Type: Audio Effect (.adv)

Purpose
- Analogue-style compressor for bus processing and mix glue, modelled on classic SSL circuitry

SIDECHAIN CONTROLS
- Sidechain View Toggle: Show/Hide | Displays or hides sidechain section
- Sidechain Listen: On/Off | Auditions sidechain input only
- External Sidechain: On/Off | Enables external sidechain control source
- External Source: — | Selects audio source for sidechain input
- External Tapping Point: Pre FX / Post FX / Post Mixer | Chooses signal tap position
- External/Internal Mix: 0.00% - 100% | Blends internal and external sidechain signals
- Sidechain Gain: -∞ dB - 24 dB | Adjusts external sidechain input level

SIDECHAIN EQ
- Sidechain Filter: On/Off | Activates filter on sidechain signal
- Sidechain Filter Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Sets sidechain filter mode
- Sidechain Filter Frequency: 30 Hz - 15 kHz | Sets cutoff frequency for sidechain
- Sidechain Filter Q: 0.10 - 12.0 | Adjusts resonance or bandwidth of sidechain filter

COMPRESSOR CONTROLS
- Attack: 0.01 / 0.1 / 0.3 / 1 / 3 / 10 / 30 ms | Sets time to reach full compression
- Release: 0.1 / 0.2 / 0.4 / 0.6 / 0.8 / 1.2 / Auto s | Sets recovery time or enables automatic release
- Ratio: 2 / 4 / 10 | Sets input-to-output compression ratio
- Threshold: -40.0 dB - 0.00 dB | Sets level where compression begins
- Range: 0.00 dB - 70.0 dB | Limits overall compression depth
- Makeup Gain: 0.00 dB - 20.0 dB | Adjusts output level after compression
- Soft Clip: On/Off | Applies analogue-style waveshaping limiting up to -5 dB
- Clip LED | Displays red for clipping or amber when soft clipping is triggered
- Compression Meter | Displays compression amount (0 dB - 20 dB, visual only)
- Dry/Wet: 0.0% - 100% | Blends compressed and dry signals
```

##### [Back to Top](#table-of-contents)

### Kick Sidechain

```text
PLUGIN: Compressor (Kick Sidechain.adv)  
Type: Device Preset (.adv)  

Purpose  
- Applies rhythmic ducking compression triggered by a Kick or Kick Buss
- Not placed on the kick or kick buss — instead, insert on bass, synths, or other elements that should reduce in volume when the kick plays  
- Creates space in the mix by reducing level of other elements when the kick hits  

SIDECHAIN CONTROLS  
- Sidechain Toggle: On/Off | Enables external sidechain input  
- Audio From Source: — | Selects external sidechain trigger (e.g. Kick or Kick Buss)  
- Sidechain Gain: -∞ dB - 24 dB | Adjusts input level of the sidechain signal  
- Sidechain Listen: On/Off | Solos sidechain input for monitoring  
- Sidechain Mix: 0% - 100% | Balances internal and external sidechain signals  

SIDECHAIN EQ  
- SC Filter: On/Off | Activates sidechain filter  
- Filter Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Defines filter shape for sidechain detection  
- Frequency: 30 Hz - 15 kHz | Sets frequency focus for sidechain detector  
- Q (Resonance): 0.10 - 12.00 | Adjusts bandwidth of the sidechain filter  

COMPRESSION SETTINGS  
- Threshold: -∞ dB - 6 dB | Level at which compression begins  
- Ratio: 1:1 - ∞:1 | Sets compression strength  
- Attack: 0.01 ms - 1.00 s | Determines how fast compression engages  
- Release: 1.00 ms - 3.00 s | Determines how fast compression releases  
- Auto Release: On/Off | Automatically adjusts release timing  
- Knee: 0.0 dB - 18 dB | Softens transition into compression  
- Peak Mode: — | Responds to short transients  
- RMS Mode: — | Responds more gradually to average level  
- Dry/Wet: 0.0% - 100% | Blends compressed and dry signal  

OUTPUT  
- Output Gain: -36 dB - 36 dB | Adjusts final signal level after compression  
```

##### [Back to Top](#table-of-contents)

### Lead Vocals Sidechain

```text
PLUGIN: Compressor (Lead Vocals Sidechain.adv)  
Type: Device Preset (.adv)  

Purpose  
- Used to make space for the lead vocal in the mix  
- Not placed on the lead vocal track or buss — instead, insert on other elements (e.g. instruments, pads, guitars, reverb returns, etc.) that should reduce in volume when the lead vocal is active  
- Triggered by the Lead Vocal or Lead Vocal Buss via sidechain input  

SIDECHAIN CONTROLS  
- Sidechain Toggle: On/Off | Enables external sidechain input  
- Audio From Source: Selects sidechain trigger (typically Lead Vocal Buss)  
- Sidechain Gain: -∞ dB - 24 dB | Adjusts input level of sidechain signal  
- Sidechain Listen: On/Off | Solos sidechain input for monitoring  
- Sidechain Mix: 0% - 100% | Balances internal and external sidechain detection  

SIDECHAIN EQ  
- SC Filter: On/Off | Activates EQ on the sidechain signal  
- Filter Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Defines frequency range for detection  
- Frequency: 30 Hz - 15 kHz | Focuses detection on midrange vocal content  
- Q (Resonance): 0.10 - 12.00 | Adjusts sidechain filter bandwidth  

COMPRESSION SETTINGS  
- Threshold: -∞ dB - 6 dB | Level at which compression begins  
- Ratio: 1:1 - ∞:1 | Determines compression strength  
- Attack: 0.01 ms - 1.00 s | Controls how quickly compression engages  
- Release: 1.00 ms - 3.00 s | Controls recovery speed  
- Auto Release: On/Off | Automatically adjusts release time  
- Knee: 0.0 dB - 18 dB | Smooths compression transition  
- Peak Mode: — | Reacts to fast transients  
- RMS Mode: — | Reacts to sustained signal level  
- Dry/Wet: 0.0% - 100% | Blends compressed and dry signals  

OUTPUT  
- Output Gain: -36 dB - 36 dB | Adjusts final output level  
```

##### [Back to Top](#table-of-contents)

### Master Buss Rack

```text
PLUGIN CHAIN: Master Buss Rack (Master Buss Rack.adg)  
Type: Device Group (.adg)  

Purpose  
- Complete mastering chain for mix finalisation and loudness compliance  
- Balances tone, dynamics and stereo image for a cohesive, controlled sound  
- Designed for subtle enhancement and accurate metering, not heavy limiting  

PLUGIN 1: EQ Eight (EQ 1 – Mid/Side Cleanup)  
- Mode: M/S | Enables independent processing of Mid and Side channels  
- Edit Channel: Side | Focuses on stereo information to remove low-end mud  
- Filter Type: Low Cut | Removes sub and bass content from stereo field  
- Frequency: 200 Hz (typical) | Sets the cutoff point for side low-frequency removal  
- Q: 0.71 | Controls filter slope; lower Q = smoother curve  
- Gain: -15 dB | Reduces low-end stereo energy for a tighter mix  
- Adaptive Q: On | Maintains consistent filter response across gain settings  
- Analyser: On | Displays live frequency spectrum  
- Purpose: Keeps bass energy mono-focused while preserving stereo width above 200 Hz  

PLUGIN 2: EQ Eight (EQ 2 – Final EQ)  
- Purpose: Final tonal shaping and subtle correction before compression and limiting  
- Frequency Range: 10 Hz – 22 kHz | Full-spectrum equalisation  
- Filter Modes: Low Cut / High Cut / Bell / Shelf / Notch | Flexible tone control  
- Gain: -15 dB – +15 dB | Adjusts frequency balance as needed  
- Q: 0.10 – 18.0 | Controls width of EQ bands  
- Global Mode: Stereo | Full-band stereo equalisation  
- Use Cases:  
  - Gently roll off sub rumble if required  
  - Apply light high-shelf boost for air and clarity  
  - Subtle midrange dips can reduce boxiness  

PLUGIN 3: Spectrum  
- Purpose: Frequency monitoring and tonal analysis  
- FFT Block Size: 8192 (recommended) | High resolution for accuracy  
- Display Mode: Logarithmic | Matches perceived frequency spacing  
- Use for visual reference when EQing or balancing energy across the spectrum  

PLUGIN 4: Compressor Rack  
- Purpose: Transparent mix-bus compression (“glue”) for cohesive mix control  
- Macro 1: Comp Thresh | Sets threshold for compression onset  
- Macro 2: Comp Ratio | Adjusts compression intensity  
- Macro 3: Comp Attack | Controls how quickly compression engages  
- Macro 4: Comp Release | Controls release behaviour after transient peaks  
- Ratio: 2:1 – 4:1 | Gentle bus compression  
- Attack: 10 – 30 ms | Preserves transient clarity  
- Release: Auto | Smooth, musical response  
- Gain Reduction: Aim for 1 – 3 dB for transparency  

PLUGIN 5: Multiband Dynamics  
- Purpose: Frequency-specific dynamic control and tonal sculpting  
- Bands: Low / Mid / High | Independent compression and expansion per range  
- Low Band: Controls sub and bass impact (below ~120 Hz)  
- Mid Band: Manages body and presence (120 Hz – 5 kHz)  
- High Band: Adds brightness and clarity (above 5 kHz)  
- Ratio: Subtle (1.2:1 – 2:1) | Maintain dynamics while smoothing transients  
- Time Control (Global): 100% | Maintains consistent attack and release scaling  

PLUGIN 6: Saturator (A Bit Warmer)  
- Purpose: Adds gentle harmonic colouration and perceived warmth  
- Curve Type: Analog Clip | Smooth, musical saturation  
- Drive: +2 dB (typical) | Adds mild harmonic richness  
- Colour On: Off (optional) | Can enhance tonal focus if enabled  
- Recommended: Use subtly to avoid upper-mid buildup  

PLUGIN 7: Spectrum
- Purpose: Monitors frequency response after harmonic processing  
- Use to confirm saturation has not caused harsh peaks or low-end inflation  

PLUGIN 8: Limiter (Limiter 1 – Peak Control)  
- Purpose: Primary peak limiter for transient control  
- Ceiling: -1 dB | Prevents digital clipping  
- Lookahead: 1.5 – 3 ms | Catches fast transients  
- Release: Auto | Smooth adaptive response  
- Drive: Increase until 1 – 2 dB of gain reduction occurs cleanly  
- Goal: Preserve transients while preventing overs  

PLUGIN 9: Limiter (Limiter 2 – Loudness Maximiser)  
- Purpose: Final loudness stage for mastering level optimisation  
- Ceiling: -0.3 dB | Ensures safe streaming delivery  
- Threshold: Adjust for target loudness (integrated LUFS)  
- Mode: True Peak | Prevents inter-sample peaks  
- Use subtle gain increases; focus on perceived loudness, not raw level  

PLUGIN 10: Utility  
- Purpose: Final gain and stereo management  
- Stereo Width: 100% (default) | Can be widened slightly for openness  
- Mono: Off | Keep stereo field intact  
- Gain: Adjust for final output alignment  
- Optional Automation: Use slight gain automation (+1 dB for choruses) for mix lift  

PLUGIN 11: Youlean Loudness Meter  
- Purpose: Monitors loudness for mastering compliance  
- Mode: Integrated / Short-Term / Momentary | Provides LUFS readings  
- Reference: Choose streaming platform target (Spotify, Apple Music, YouTube, etc.)  
- Use for checking true peak level, integrated loudness and dynamic range consistency  
```

##### [Back to Top](#table-of-contents)

### Overdrive
<a id="overdrive-user-preset"></a>

```text
PLUGIN: Overdrive (Overdrive.adv)
Type: Audio Effect (.adv)

Purpose
- Distortion effect using band-pass filtering for frequency-targeted overdrive and tone shaping

FILTER SECTION
- Bandpass Display | X-Y control for filter frequency (horizontal) and bandwidth (vertical)
- Center Frequency: 50 Hz - 20 kHz | Sets centre frequency of band-pass filter
- Bandwidth: 0.50 - 9.00 | Adjusts width of filter band

DISTORTION AND TONE
- Drive: 0% - 100% | Sets distortion amount (minimum still applies slight saturation)
- Tone: 0% - 100% | Adjusts post-distortion brightness and high-frequency content
- Dynamics: 0.0% - 100% | Preserves dynamic range; higher values apply less compression

OUTPUT
- Dry/Wet: 0% - 100% | Balances dry and processed signals (Tone remains active even at 0%)
```

##### [Back to Top](#table-of-contents)

### Reverb Rack

```text
PLUGIN CHAIN: Reverb Rack (Reverb Rack.adg)  
Type: Device Group (.adg)  

Purpose  
- Multi-device rack for reverb and tonal shaping  
- Designed for cohesive ambience control with optional compression, saturation and filtering  
- Contains Reverb, Compressor Rack, Saturator, Auto Filter and Utility  

PLUGIN 1: Reverb  
- Purpose: Main reverb processor providing space, depth and dimension  
- Low Cut: 50 Hz – 18 kHz | Removes low-end from reverb input  
- High Cut: 50 Hz – 18 kHz | Removes high-end from reverb input  
- Spin: On/Off | Modulates early reflections for natural movement  
- Spin Amount: 2.00 – 55.00 | Controls modulation depth  
- Spin Rate: 0.07 – 1.30 Hz | Controls modulation speed  
- Shape: 0.00 – 1.00 | Adjusts reflection shape  
- Size: 0.22 – 500.00 | Defines virtual room size  
- Decay Time: 0.20 – 60.00 s | Controls reverb tail length  
- Freeze: On/Off | Sustains reverberation indefinitely  
- Stereo: 0.00 – 120.00 | Sets stereo width of reflections  
- Density: Sparse / Low / Mid / High | Adjusts reverb density and diffusion  
- Chorus: On/Off | Adds modulation to reverb tail  
- Chorus Amount: 0.01 – 4.00 | Modulation depth  
- Chorus Rate: 0.01 Hz – 8.00 Hz | Modulation speed  
- Reflect Level: -30 dB – +6 dB | Controls early reflection amplitude  
- Diffuse Level: -30 dB – +6 dB | Controls tail amplitude  
- Dry/Wet: 0% – 100% | Balances dry and reverberated signal  

PLUGIN 2: Compressor Rack (Off by default)  
- Purpose: Optional compression for dynamic control within the reverb tail  
- Macro 1: Comp Thresh → Threshold  
- Macro 2: Comp Ratio → Ratio  
- Macro 3: Comp Attack → Attack  
- Macro 4: Comp Release → Release  
- Threshold: -60 dB – 0 dB | Compression start point  
- Ratio: 1:1 – ∞:1 | Compression strength  
- Attack: 0.01 ms – 1 s | Onset speed of compression  
- Release: 1 ms – 3 s | Recovery time  
- Output Gain: -36 dB – +36 dB | Post-compression level  
- Knee: 0 – 24 dB | Smooths compression onset  
- Dry/Wet: 0% – 100% | Parallel compression control  
- Sidechain: On/Off | Enables external trigger source if needed  

PLUGIN 3: Saturator (Off by default)  
- Purpose: Adds harmonic richness and colour to the reverb return  
- Drive: 0 dB – +36 dB | Amount of saturation applied  
- Curve Type: Analog Clip / Soft Sine / Medium Curve / Hard Curve / Sine Fold | Selects distortion mode  
- Output: -36 dB – 0 dB | Output gain trim  
- Soft Clip: On/Off | Smooth limiting to prevent harsh peaks  
- Dry/Wet: 0% – 100% | Blend of clean and processed signal  

PLUGIN 4: Auto Filter (Off by default)  
- Purpose: Tonal shaping and movement within the reverb tail  
- Filter Type: Lowpass / Highpass / Bandpass / Notch / Morph | Selects filter curve  
- Frequency: 10 Hz – 30 kHz | Sets filter cutoff  
- Resonance (Q): 0% – 100% | Boosts frequencies near cutoff  
- Drive: -∞ – +36 dB | Adds harmonic drive pre-filter  
- Envelope Amount: -100% – 100% | Filter modulation depth  
- LFO Amount: -100% – 100% | Modulates filter cutoff via LFO  
- LFO Rate: 0.01 Hz – 30 Hz | Sets modulation speed  
- Dry/Wet: 0% – 100% | Blends filtered and dry signal  

PLUGIN 5: Utility (On by default)  
- Purpose: Final gain and stereo shaping for the reverb return  
- Channel Mode: Left / Stereo / Right / Swap | Defines output routing  
- Stereo Width: 0% – 400% | Controls stereo image  
- Mono: On/Off | Converts to mono if required  
- Bass Mono: On/Off | Forces low frequencies to mono  
- Bass Mono Frequency: 50 Hz – 500 Hz | Defines crossover for mono conversion  
- Gain: -∞ dB – +35 dB | Adjusts reverb output level  
- Balance: 50L – 50R | Pans wet signal  
- DC: On/Off | Removes subsonic frequencies and DC offset  
- Dry/Wet: 0% – 100% | Optional blending control when in return configuration  

NOTES  
- Adjust send level per track to control overall reverb depth  
- Enable the Compressor for tighter or more controlled reverb tails  
- Use the Auto Filter to remove low-end build-up or add subtle modulation  
- Activate the Saturator for additional warmth or harmonic density  
- Utility remains active for final gain and stereo width management  
```

##### [Back to Top](#table-of-contents)

### Spectrum
<a id="spectrum-user-preset"></a>

```text
PLUGIN: Spectrum (Spectrum.adv)  
Type: Audio Effect (.adv)  

Purpose  
- Provides real-time frequency analysis of audio signals  

DISPLAY SETTINGS  
- Block: 2048 / 4096 / 8192 / 16384 | Sets FFT size (larger = finer detail in lows, slower refresh)  
- Channel Mode: Left / Right / L+R | Selects which channel(s) are analysed  
- Refresh Rate: 40–200 ms | Controls how often the display updates  
- Average (Avg): 1–8 | Smooths the display by averaging over time  
- Graph Type: Line / Bar | Selects display style  
- Max Toggle: On/Off | Displays a “max hold” line for peaks  

X-AXIS SCALE (FREQUENCY)  
- Scale X: Linear / Logarithmic / Semitones | Sets scaling of the frequency axis  

Y-AXIS SCALE (AMPLITUDE)  
- Range: –200 dB to 0 dB | Sets visible dynamic range of the display  
```

##### [Back to Top](#table-of-contents)

### Tuner
<a id="tuner-user-preset"></a>

```text
PLUGIN: Tuner (Tuner.adv)  
Type: Audio Effect (.adv)  

Purpose  
- Provides visual pitch detection of incoming audio signals  

DISPLAY SETTINGS  
- Display Type: Histogram / Note | Selects how pitch is displayed (frequency distribution or nearest note)  
- Deviation Mode: Auto / Fine / Coarse | Controls sensitivity of pitch deviation display  
- Frequency Display: Hz / Note | Sets the unit for the frequency readout  
- Reference Frequency (Ref): 410–480 Hz | Sets tuning reference for A4  

ADDITIONAL CONTROLS  
- Show History: On/Off | Displays a scrolling history of pitch detection  
```

##### [Back to Top](#table-of-contents)

### Vocal Rack

```text
PLUGIN CHAIN: Vocal Rack (Vocal Rack.adg)  
Type: Device Group (.adg)  

Purpose  
- Multi-device vocal processing chain for dynamic control, tonal balance and creative enhancement  
- All devices are OFF until enabled  

CORE PROCESSORS: Gate, EQ 1, Compressor 1, EQ 2, De-esser, Glue Compressor  
CREATIVE PROCESSORS: EQ 3 Lift, Saturator, Chorus-Ensemble, Reverb, Grain Delay, EQ 4  

PLUGIN 1: Gate  
- Threshold: –80 dB to +10 dB | Level below which gate closes  
- Return: 0 dB to +∞ | Signal rise required to reopen gate  
- Attack: 0.01–200 ms | Gate open speed  
- Hold: 0–4000 ms | Minimum open duration  
- Release: 10–1000 ms | Gate close speed  
- Floor: –∞ dB to 0 dB | Maximum attenuation when closed  
- Lookahead: 0–2 ms | Anticipates transients  

PLUGIN 2: EQ 1 (High Pass – EQ Eight)  
- Frequency: 20 Hz–20 kHz | Cutoff point for high-pass filter  
- Resonance (Q): 0.10–10.0 | Filter slope steepness  
- Slope: 12 / 24 / 48 dB per octave | Filter slope selection  

PLUGIN 3: Compressor 1 (Peak Chopper)  
- Threshold: –60 dB to 0 dB | Level where compression begins  
- Ratio: 1:1 to ∞:1 | Compression intensity  
- Attack: 0.01 ms–1 s | Time to full compression  
- Release: 1 ms–3 s | Recovery time  
- Knee: 0–24 dB | Transition softness  
- Lookahead: 0–10 ms | Pre-detection timing  
- Makeup Gain: –36 dB to +36 dB | Output level adjustment  

PLUGIN 4: EQ 2 (Cut the Problems – EQ Eight)  
- Up to 8 Bell bands | Frequency 20 Hz–20 kHz, Gain –35 to +35 dB, Q 0.10–10.0  
- Common cuts: 200 Hz (boom), 400 Hz (box), 2–4 kHz (harshness), 5–8 kHz (sibilance)  

PLUGIN 5: De-esser  
- Frequency: 1–18 kHz | Target frequency range  
- Threshold: –60 dB to 0 dB | Activation level  
- Ratio: 1:1 to ∞:1 | Reduction amount  
- Attack: 1–50 ms | Reaction speed  
- Release: 10–500 ms | Recovery time  
- Soft Knee: On/Off | Smoothens onset  
- Mode: Wideband / Bandpass | Processing type  

PLUGIN 6: Compressor 2 (Glue)  
- Attack: 0.01–30 ms | Response time  
- Release: 0.1–1.2 s | Recovery time  
- Ratio: 2:1–10:1 | Compression strength  
- Threshold: –∞ to 0 dB | Level where compression begins  
- Makeup Gain: –∞ to +∞ dB | Output compensation  
- Range: 0–30 dB | Maximum reduction  
- Soft Clip: On/Off | Analogue-style limiting  
- Dry/Wet: 0–100% | Parallel blend  

PLUGIN 7: EQ 3 (Lift – EQ Eight)  
- Up to 8 Bell or Shelf bands | Frequency 20 Hz–20 kHz, Gain –35 to +35 dB, Q 0.10–10.0  
- Common boosts: 2–5 kHz (clarity), 8–12 kHz (air)  

PLUGIN 8: Saturator  
- Drive: –36 to +36 dB | Saturation intensity  
- Type: Analog Clip / Soft Sine / Hard Curve etc. | Distortion character  
- Colour: 20 Hz–20 kHz | Frequency focus  
- Depth: 0–100% | Processing depth  
- Soft Clip: On/Off | Peak rounding  
- Output: –36 to +36 dB | Final gain  
- Dry/Wet: 0–100% | Blend  

PLUGIN 9: Chorus-Ensemble  
- Mode: Classic / Ensemble / Vibrato | Chorus style  
- Rate: 0.01–5 Hz | Modulation speed  
- Amount: 0–100% | Depth of modulation  
- Feedback: 0–100% | Resonance feedback  
- High-pass Filter: 20 Hz–20 kHz | Removes low end from effect  
- Width: 0–100% | Stereo spread  
- Dry/Wet: 0–100% | Blend  

PLUGIN 10: Reverb  
- Predelay: 0–500 ms | Initial delay before reflections  
- Decay: 0.1–15 s | Reverb tail length  
- Size: 0–400% | Room simulation size  
- Density: 0–100% | Echo density  
- Diffusion: 0–100% | Echo spread  
- Spin Rate: 0–20 Hz | Reflection modulation rate  
- High Cut: 20 Hz–9 kHz | Removes high frequencies  
- Low Cut: 20–200 Hz | Removes low frequencies  
- Reflect Level: –∞ to +20 dB | Early reflections  
- Diffuse Level: –∞ to +20 dB | Late reflections  
- Dry/Wet: 0–100% | Blend  

PLUGIN 11: Grain Delay  
- Spray: 0–500 ms | Random grain offset  
- Frequency: 0.1–100 Hz | Grain rate  
- Pitch: –36 to +36 st | Grain pitch shift  
- Random Pitch: 0–100% | Pitch variation  
- Feedback: 0–100% | Echo regeneration  
- Sync/Time: On/Off | Delay timing mode  
- Delay Time: 1 ms–5000 ms or note division | Delay length  
- Dry/Wet: 0–100% | Blend  

PLUGIN 12: EQ 4 (Final EQ – EQ Eight)  
- Up to 8 bands | Frequency 20 Hz–20 kHz, Gain –35 to +35 dB, Q 0.10–10.0  
- Used for final tonal shaping  
```

##### [Back to Top](#table-of-contents)

## Ableton Live Default Plugins

A–Z list of all stock devices for quick reference. 

Some also appear under [User Presets](#user-presets), where they're included in the Project Template and User Library as custom racks or configured versions.  

### Auto Filter

```text
PLUGIN: Auto Filter (Auto Filter.adv)
Type: Audio Effect (.adv)

Purpose
- Dynamic filter for tone shaping, modulation and sidechain envelope control

SIDECHAIN SECTION
- Sidechain View Toggle: Show / Hide | Displays or hides the sidechain controls
- Sidechain Listen: On/Off | Auditions sidechain input only
- External Sidechain: On/Off | Enables external input as modulation source
- External Source: — | Selects track for sidechain input
- External Tapping Point: Pre FX / Post FX / Post Mixer | Defines where input is tapped
- External/Internal Mix: 0.00% - 100% | Balances internal and external sidechain signals
- Sidechain Gain: -∞ dB - 24 dB | Sets sidechain input level

FILTER SECTION
- Sidechain Filter: On/Off | Activates filter on sidechain signal
- Sidechain Filter Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Sets filter mode for sidechain
- Sidechain Filter Frequency: 30 Hz - 15 kHz | Sets cutoff frequency for sidechain
- Sidechain Filter Q: 0.10 - 12.00 | Adjusts resonance of sidechain filter
- Filter Frequency: 20 Hz - 20 kHz | Sets main filter cutoff
- Filter Type: Low Pass / High Pass / Band Pass / Notch / Morph / DJ / Comb / Resampling / Notch + LP / Vowel | Selects main filter type
- Filter Slope: 12 / 24 | Sets slope in dB per octave
- Filter Resonance: 0.0% - 100% | Controls resonance emphasis at cutoff

LFO SECTION
- Stereo Mode: Phase / Spin | Defines stereo offset behaviour
- LFO Phase: 0.0° - 360° | Sets left-right phase offset
- LFO Spin: 0.0% - 50% | Detunes LFOs relative to each other
- LFO Phase Offset: 0.0° - 360° | Shifts global LFO start phase
- Quantization Mode: None / Steps / S&H | Sets LFO quantization type
- LFO Steps: 2 - 64 | Defines number of LFO divisions
- LFO Amount: 0.0% - 100% | Sets LFO modulation depth
- LFO Frequency: 0.10 Hz - 60 Hz | Sets LFO speed
- LFO Waveform: Sine / Triangle / Saw / Square / Ramp Up / Ramp Down / Wander / S&H | Selects waveform shape
- LFO Morph: 0.0% - 100% | Morphs between LFO shapes
- LFO Time Mode: Rate / Time / Synced / Synced Triplet / Synced Dotted / Sixteenth | Selects timing mode

ENVELOPE SECTION
- Envelope Amount: -100% - 100% | Sets modulation polarity and strength
- Envelope Attack: 0.00 ms - 100 ms | Controls rise time
- Envelope Hold: On/Off | Maintains full attack before release
- Envelope Release: 0.00 ms - 3.00 s | Controls fall time
- Envelope S&H: On/Off | Enables quantised envelope modulation
- Envelope S&H Rate: 1/64, 1/32, 1/16, 1/8, 1/4, 1/2, 1 | Defines quantisation rate

OUTPUT SECTION
- Drive: 0.0% - 100% | Adds pre-filter saturation
- Filter Circuit: SVF / DFM / MS2 / PRD | Selects circuit model
- Soft Clip: On/Off | Limits peaks caused by high resonance
- Output: -∞ dB - 0.0 dB | Controls device output level
- Dry/Wet: 0.0% - 100% | Balances dry and wet signals
```

##### [Back to Top](#table-of-contents)

### Chorus-Ensemble

```text
PLUGIN: Chorus-Ensemble (Chorus-Ensemble.adv)
Type: Audio Effect (.adv)

Purpose
- Modulated delay effect for thickening, ensemble textures and vibrato motion

MODES AND FILTERS
- Mode: Classic / Ensemble / Vibrato | Selects effect type and modulation structure
- Filter: 20 Hz - 2.00 kHz | Enables or disables high-pass filtering
- Stereo Width: 0.0% - 200% | Sets stereo width of wet signal (Classic and Ensemble only)
- Modulation Offset: 0.0° - 180° | Adjusts phase offset between left and right modulation (Vibrato only)
- Modulation Waveform: 0.0% - 100% | Blends between sine and triangle modulation shapes (Vibrato only)

MODULATION AND FEEDBACK
- Modulation Rate: 0.10 Hz - 15.0 Hz | Sets modulation speed
- Modulation Amount: 0.0% - 100% | Sets modulation depth
- Feedback: 0.0% - 99% | Feeds output back into input for resonance (Classic and Ensemble only)
- Invert Feedback: On/Off | Reverses feedback polarity (Classic and Ensemble only)

OUTPUT AND MIX
- Output Gain: -∞ dB - 6.0 dB | Controls processed signal level
- Warmth: 0.0% - 100% | Adds harmonic distortion and tone softening
- Dry/Wet: 0.0% - 100% | Balances dry and wet signal mix (Classic and Ensemble only)
```

##### [Back to Top](#table-of-contents)

### Compressor

```text
PLUGIN: Compressor (Compressor.adv)
Type: Audio Effect (.adv)

Purpose
- Dynamics processor for controlling signal level and dynamic range via compression or expansion

SIDECHAIN SECTION
- Sidechain View Toggle: Show/Hide | Displays or hides sidechain controls
- Sidechain Listen: On/Off | Auditions sidechain input only
- External Sidechain: On/Off | Enables external input as control source
- External Source: — | Selects track for sidechain input
- External Tapping Point: Pre FX / Post FX / Post Mixer | Defines where sidechain input is tapped
- External/Internal Mix: 0.00% - 100% | Balances internal and external sidechain signals
- Sidechain Gain: -∞ dB - 24 dB | Adjusts sidechain input level

FILTER SECTION
- Sidechain Filter: On/Off | Activates filter on sidechain signal
- Sidechain Filter Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Selects sidechain filter type
- Sidechain Filter Frequency: 30 Hz - 15 kHz | Sets cutoff frequency for sidechain
- Sidechain Filter Q: 0.10 - 12.00 | Adjusts resonance of sidechain filter

COMPRESSION CONTROLS
- Ratio: 1.00:1 - ∞:1 (Peak/RMS) | Sets input-to-output compression ratio
- Ratio (Expand Mode): 1.00:1 - 1:2.00 | Sets upward expansion ratio
- Attack: 0.01 ms - 1.00 s | Determines how quickly compression engages
- Release: 1.00 ms - 3.00 s | Determines how quickly compression releases
- Auto Release: On/Off | Automatically adapts release time
- Threshold: -∞ dB - 6 dB | Sets input level at which compression begins
- Knee: 0.0 dB - 18 dB | Sets transition smoothness near threshold
- Lookahead: 0 ms / 1 ms / 10 ms | Delays input for precise peak detection
- Makeup Gain: On/Off | Automatically compensates output level
- Output Gain: -36 dB - 36 dB | Adjusts post-compression output
- Dry/Wet: 0.0% - 100% | Blends compressed and dry signal

MODES AND VIEWS
- Peak Mode: — | Responds to short peaks
- RMS Mode: — | Smooth response to average levels
- Expand Mode: — | Increases output for signals above threshold
- Collapsed View: — | Displays essential parameters
- Transfer Curve View: — | Shows input/output curve
- Activity View: — | Visualises signal level and gain reduction
```

##### [Back to Top](#table-of-contents)

### Delay

```text
PLUGIN: Delay (Delay.adv)
Type: Audio Effect (.adv)

Purpose
- Stereo delay for rhythmic echoes, spatial effects and filter-modulated feedback

DELAY TIME (LEFT / RIGHT)
- Delay Mode: Sync / Time | Switches between beat-synced and time-based delay
- Beat Division: 1 / 2 / 3 / 4 / 5 / 6 / 8 / 16 | Sets delay time in 16th-note divisions (Sync mode)
- Delay Time: 1.00 ms - 5.00 s | Sets delay time in milliseconds (Time mode)
- Delay Offset: -33% - 33% | Adjusts timing offset for swing or stereo variation
- Stereo Link: On/Off | Links left and right delay times

FEEDBACK
- Feedback: 0.0% - 95% | Sets amount of signal fed back into input
- Freeze: On/Off | Loops buffer contents indefinitely while ignoring new input

FILTER
- Filter: On/Off | Activates band-pass filter on feedback signal
- Bandpass Display: — | X-Y control for filter frequency (horizontal) and width (vertical)
- Filter Frequency: 50 Hz - 18 kHz | Sets centre frequency of filter
- Filter Width: 0.50 - 9.00 | Sets bandwidth of filter
- Modulation Rate: 0.01 Hz - 40.0 Hz | Sets modulation oscillator speed
- Filter < Modulation: 0.0% - 100% | Modulates filter frequency
- Delay < Modulation: 0.0% - 100% | Modulates delay time

MODE
- Delay Transition Mode: Repitch / Fade / Jump | Sets how delay time changes are processed
- Ping Pong: On/Off | Alternates echoes between left and right channels

OUTPUT
- Dry/Wet: 0.0% - 100% | Balances dry and delayed signals (set to 100% for return use)
```

##### [Back to Top](#table-of-contents)

### Drum Buss
<a id="drum-buss-default-plugin"></a>

```text
PLUGIN: Drum Buss (Drum Buss.adv)
Type: Audio Effect (.adv)

Purpose
- Drum processing tool for saturation, compression and transient shaping

DRIVE AND DISTORTION
- Drive: 0.0% - 100% | Sets input drive intensity
- Distortion Type: Soft / Medium / Hard | Selects waveshaping, limiting or clipping distortion mode
- Trim: -∞ dB - 0.00 dB | Reduces input level
- Compression: On/Off | Enables fixed pre-drive compressor
- Crunch: 0.0% - 100% | Adds distortion to mid-high frequencies

FILTERING AND TONE
- Damping Frequency: 500 Hz - 20 kHz | Applies post-processing damping filter

TRANSIENT AND LOW-END
- Transients: -1.00 - 1.00 | Emphasises or reduces transient attack
- Boom: 0.0% - 100% | Controls low-frequency enhancement
- Boom Frequency: 30 Hz - 90 Hz | Sets low-end enhancer frequency
- Boom Decay: 0.0% - 100% | Controls decay of enhanced low end
- Force To Note: — | Quantises boom frequency to nearest MIDI note
- Boom Audition: On/Off | Solos low-end enhancer output
- Bass Meter: 0.0% - 100% | Displays low-frequency output level

OUTPUT
- Output Gain: -40 dB - 3.00 dB | Sets output level after processing
- Dry/Wet: 0.0% - 100% | Balances dry and processed signal
```

##### [Back to Top](#table-of-contents)

### EQ Eight

```text
PLUGIN: EQ Eight (EQ Eight.adv)
Type: Audio Effect (.adv)

Purpose
- Eight-band parametric equaliser for precision tone shaping and spectral balancing

BAND CONTROLS
- Frequency: 10 Hz - 22 kHz | Sets frequency of selected filter
- Gain: -15 dB - 15 dB | Boosts or cuts selected band (disabled for cut and notch filters)
- Filter Q: 0.10 - 18.0 | Sets resonance or bandwidth of selected filter

FILTER CONTROLS
- Frequency Display: — | Visualises filter curves and spectrum when Analyse is enabled
- Filter Mode: Low Cut (12 / 48 dB) / Low Shelf / Peak / Notch / High Shelf / High Cut (12 / 48 dB) | Selects filter type
- Filter Activator: On/Off per band | Toggles individual filters

DISPLAY AND MONITORING
- Audition Mode: On/Off | Solos frequency range of selected filter while held
- Analyse: On/Off | Displays real-time output spectrum
- Expanded View: On/Off | Shows or hides detailed interface

GLOBAL CONTROLS
- Global Mode: Stereo / L/R / M/S | Selects EQ processing mode
- Edit Channel/Signal: L/R or M/S | Chooses which signal to edit per mode
- Adaptive Q: On/Off | Narrows Q as boost or cut increases for analogue-like behaviour
- Scale: -200% - 200% | Scales gain change of all active filters
- Global Gain: -12 dB - 12 dB | Adjusts overall EQ output level
```

##### [Back to Top](#table-of-contents)

### Erosion

```text
PLUGIN: Erosion (Erosion.adv)
Type: Audio Effect (.adv)

Purpose
- Distortion and texture effect using noise or sine modulation to add grit and movement

MODULATION CONTROL
- X-Y Controller | Horizontal controls frequency in Hz, vertical sets modulation amount (0 - 200); hold Opt for bandwidth (not in Sine mode)

MODE AND FREQUENCY
- Mode: Noise / Wide Noise / Sine | Selects modulation source and stereo behaviour
- Frequency: 300 Hz - 18 kHz | Sets modulation frequency and tonal character
- Width: 0.10 - 2.50 | Adjusts bandwidth in Noise and Wide Noise modes
- Amount: 0.00 - 200 | Sets modulation intensity
```

##### [Back to Top](#table-of-contents)

### Gate

```text
PLUGIN: Gate (Gate.adv)
Type: Audio Effect (.adv)

Purpose
- Dynamics processor that reduces or mutes quiet signals and passes louder ones, with optional sidechain control

SIDECHAIN CONTROLS
- Sidechain Listen: On/Off | Auditions sidechain input only
- External Sidechain: On/Off | Enables external control source
- External Source: — | Selects track or device for sidechain input
- External Tapping Point: Pre FX / Post FX / Post Mixer | Chooses signal tap position
- External/Internal Mix: 0.00% - 100% | Blends internal and external sidechain control signals
- Sidechain Gain: -∞ dB - 24 dB | Adjusts external sidechain level

SIDECHAIN EQ
- Sidechain Filter: On/Off | Activates filter on sidechain signal
- Sidechain Filter Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Selects sidechain filter mode
- Sidechain Filter Frequency: 30 Hz - 15 kHz | Sets cutoff frequency for sidechain
- Sidechain Filter Q: 0.10 - 12.0 | Adjusts bandwidth of sidechain filter

GATE CONTROLS
- Threshold: -∞ dB - 6.00 dB | Sets level required to open gate
- Return: 0.00 dB - 24.0 dB | Sets closing offset (hysteresis)
- Flip: On/Off | Reverses gate behaviour to open below threshold
- Lookahead: 0 ms / 1.5 ms / 10 ms | Delays input for early detection
- Attack: 0.02 ms - 150 ms | Controls gate opening speed
- Hold: 1.00 ms - 1.50 s | Sets minimum open duration
- Release: 0.10 ms - 3.00 s | Controls gate closing speed
- Floor: -∞ dB - 0.00 dB | Sets attenuation level when gate is closed
- Gate Activity | Displays input (rear) and output (front) levels
- Gain Reduction | Visualises current attenuation amount
```

##### [Back to Top](#table-of-contents)

### Glue Compressor
<a id="glue-compressor-default-plugin"></a>

```text
PLUGIN: Glue Compressor (Glue Compressor.adv)
Type: Audio Effect (.adv)

Purpose
- Analogue-style compressor for bus processing and mix glue, modelled on classic SSL circuitry

SIDECHAIN CONTROLS
- Sidechain View Toggle: Show/Hide | Displays or hides sidechain section
- Sidechain Listen: On/Off | Auditions sidechain input only
- External Sidechain: On/Off | Enables external sidechain control source
- External Source: — | Selects audio source for sidechain input
- External Tapping Point: Pre FX / Post FX / Post Mixer | Chooses signal tap position
- External/Internal Mix: 0.00% - 100% | Blends internal and external sidechain signals
- Sidechain Gain: -∞ dB - 24 dB | Adjusts external sidechain input level

SIDECHAIN EQ
- Sidechain Filter: On/Off | Activates filter on sidechain signal
- Sidechain Filter Type: Low Shelf / Bell / High Shelf / Low Pass / Band Pass / High Pass | Sets sidechain filter mode
- Sidechain Filter Frequency: 30 Hz - 15 kHz | Sets cutoff frequency for sidechain
- Sidechain Filter Q: 0.10 - 12.0 | Adjusts resonance or bandwidth of sidechain filter

COMPRESSOR CONTROLS
- Attack: 0.01 / 0.1 / 0.3 / 1 / 3 / 10 / 30 ms | Sets time to reach full compression
- Release: 0.1 / 0.2 / 0.4 / 0.6 / 0.8 / 1.2 / Auto s | Sets recovery time or enables automatic release
- Ratio: 2 / 4 / 10 | Sets input-to-output compression ratio
- Threshold: -40.0 dB - 0.00 dB | Sets level where compression begins
- Range: 0.00 dB - 70.0 dB | Limits overall compression depth
- Makeup Gain: 0.00 dB - 20.0 dB | Adjusts output level after compression
- Soft Clip: On/Off | Applies analogue-style waveshaping limiting up to -5 dB
- Clip LED | Displays red for clipping or amber when soft clipping is triggered
- Compression Meter | Displays compression amount (0 dB - 20 dB, visual only)
- Dry/Wet: 0.0% - 100% | Blends compressed and dry signals
```

##### [Back to Top](#table-of-contents)

### Grain Delay

```text
PLUGIN: Grain Delay (Grain Delay.adv)
Type: Audio Effect (.adv)

Purpose
- Granular delay effect for pitch shifting, time scattering and texture manipulation

DELAY SECTION
- Delay Mode: Sync / Time | Switches between beat-synced and millisecond delay
- Beat Division: 1 / 2 / 3 / 4 / 5 / 6 / 8 / 16 | Sets delay time in 16th notes (Sync mode)
- Delay Time: 1.00 ms - 128 ms | Sets delay time in milliseconds (Time mode)
- Feedback: 0.0% - 95% | Controls amount of delayed signal fed back to input

GRAIN PARAMETERS
- Spray: 0.00 ms - 500 ms | Adds random delay-time variation for temporal diffusion
- Frequency: 1.00 Hz - 150 Hz | Sets grain density and duration
- Pitch: -36.0 - 12.0 | Transposes grain pitch
- Random Pitch: 0 - 161 | Adds pitch randomness per grain

X-Y CONTROLLER
- X-Y Controller | Horizontal controls mapped X-axis parameter; vertical controls Y-axis parameter
- Delay Time → X Axis | Maps delay time to X-axis
- Spray → X Axis / Y Axis | Maps Spray parameter to X or Y
- Frequency → X Axis / Y Axis | Maps Frequency parameter to X or Y
- Pitch → X Axis / Y Axis | Maps Pitch parameter to X or Y
- Random Pitch → X Axis / Y Axis | Maps Random Pitch parameter to X or Y
- Feedback → X Axis / Y Axis | Maps Feedback parameter to X or Y
- Dry/Wet → Y Axis | Maps Dry/Wet to Y-axis

OUTPUT
- Dry/Wet: 0.0% - 100% | Balances dry and processed signals
```

##### [Back to Top](#table-of-contents)

### Limiter

```text
PLUGIN: Limiter (Limiter.adv)
Type: Audio Effect (.adv)

Purpose
- Peak limiter for controlling maximum output level and maintaining loudness without clipping

INPUT AND MAXIMIZE
- Input Gain: -24 dB - 24 dB | Adjusts input level before limiting (disabled when Maximize is On)
- Maximize: On/Off | Enables automatic gain compensation linked to Threshold
- Maximize Threshold: -24 dB - 0.0 dB | Sets input level where gain reduction begins (Maximize On)
- Maximize Output: -24 dB - 0.0 dB | Sets target maximum output level (Maximize On)

LIMITER CONTROLS
- Ceiling: -24 dB - 0.0 dB | Defines peak output ceiling
- Release: 0.01 ms - 3.00 s | Sets recovery time after limiting
- Auto-Release: On/Off | Enables automatic release adjustment
- Lookahead: 1.5 / 3 / 6 ms | Determines peak detection response time
- Channel Link: 0.0% - 100% | Controls how gain reduction is shared between channels
- Ceiling Mode: Standard / Soft Clip / True Peak | Selects ceiling behaviour
- Routing Mode: L/R / M/S | Selects stereo or mid/side processing configuration

METERING
- Gain Reduction | Displays current reduction amount (-24 dB - 0.0 dB)
```

##### [Back to Top](#table-of-contents)

### Multiband Dynamics

```text
PLUGIN: Multiband Dynamics (Multiband Dynamics.adv)
Type: Audio Effect (.adv)

Purpose
- Three-band compressor/expander for detailed dynamic control and spectral balance shaping

SIDECHAIN
- Sidechain View Toggle: Show/Hide | Displays or hides sidechain controls
- Sidechain Listen: On/Off | Auditions sidechain input only
- External Sidechain: On/Off | Enables external sidechain input
- External Source: — | Selects track for sidechain input
- External Tapping Point: Pre FX / Post FX / Post Mixer | Chooses signal tap position
- External/Internal Mix: 0.00% - 100% | Blends internal and external control signals
- Sidechain Gain: -∞ dB - 24 dB | Adjusts external sidechain input level

SPLIT FREQUENCY / BAND SECTION
- Low Band: On/Off | Enables low-band processing
- Low-Mid Crossover: 30 Hz - 3.00 kHz | Sets top frequency for low band
- Mid Band: On/Off | Enables mid-band processing
- Mid-High Crossover: 300 Hz - 15.0 kHz | Sets bottom frequency for high band
- High Band: On/Off | Enables high-band processing
- Band Solos (Low / Mid / High): On/Off | Solos selected frequency band
- Band Activators (Low / Mid / High): On/Off | Enables gain and dynamics per band

BAND INPUT GAIN
- Input Gain (Low / Mid / High): -24 dB - 24 dB | Adjusts pre-processing input level per band

DYNAMICS CONTROL (PER BAND)
- Below Threshold (Low / Mid / High): -80 dB - 0.00 dB | Sets expansion threshold
- Below Ratio (Low / Mid / High): 1:0.25 - 1:Inf | Sets expansion ratio
- Above Threshold (Low / Mid / High): -80 dB - 0.00 dB | Sets compression threshold
- Above Ratio (Low / Mid / High): 1:Inf - 1:0.50 | Sets compression ratio
- Attack (Low / Mid / High): 0.10 ms - 5.00 s | Sets attack time for above or below thresholds
- Release (Low / Mid / High): 0.10 ms - 5.00 s | Sets release time for above or below thresholds

BAND OUTPUT GAIN
- Output Gain (Low / Mid / High): -24 dB - 24 dB | Adjusts post-processing output level per band

GLOBAL CONTROLS
- Soft Knee: On/Off | Enables gradual onset of compression or expansion
- Peak/RMS Mode: On/Off | Selects envelope follower mode
- Time Scaling: 10% - 1000% | Scales all attack and release durations proportionally
- Amount: 0.0% - 100% | Adjusts global dynamics intensity across all bands
- Global Output: -24 dB - 24 dB | Adjusts overall output level
```

##### [Back to Top](#table-of-contents)

### Overdrive
<a id="overdrive-default-plugin"></a>

```text
PLUGIN: Overdrive (Overdrive.adv)
Type: Audio Effect (.adv)

Purpose
- Distortion effect using band-pass filtering for frequency-targeted overdrive and tone shaping

FILTER SECTION
- Bandpass Display | X-Y control for filter frequency (horizontal) and bandwidth (vertical)
- Center Frequency: 50 Hz - 20 kHz | Sets centre frequency of band-pass filter
- Bandwidth: 0.50 - 9.00 | Adjusts width of filter band

DISTORTION AND TONE
- Drive: 0% - 100% | Sets distortion amount (minimum still applies slight saturation)
- Tone: 0% - 100% | Adjusts post-distortion brightness and high-frequency content
- Dynamics: 0.0% - 100% | Preserves dynamic range; higher values apply less compression

OUTPUT
- Dry/Wet: 0% - 100% | Balances dry and processed signals (Tone remains active even at 0%)
```

##### [Back to Top](#table-of-contents)

### Reverb

```text
PLUGIN: Reverb (Reverb.adv)
Type: Audio Effect (.adv)

Purpose
- Algorithmic reverb for simulating space, ambience and diffusion characteristics

INPUT FILTER
- Lo Cut / Hi Cut: On/Off | Enables input filters to reduce frequency range before reverb
- Bandpass Display | X-Y control for frequency (horizontal) and resonance (vertical)
- Frequency: 50 Hz - 18 kHz | Sets centre frequency of input band-pass filter

EARLY REFLECTIONS
- Spin: On/Off | Toggles modulation of early reflections
- Amount: 2.00 - 55.00 | Sets modulation depth
- Rate: 0.07 Hz - 1.30 Hz | Sets modulation speed
- Shape: 0.00 - 1.00 | Adjusts envelope shape of reflections

DIFFUSION NETWORK
- High: On/Off | Enables high-frequency decay filter
- High Filter Type: 20 Hz - 16 kHz | Sets shelving or low-pass filter cutoff
- High Filter Q: 0.20 - 1.00 | Sets resonance for high filter
- Low: On/Off | Enables low-frequency decay filter
- Low Filter Frequency: 20 Hz - 15 kHz | Sets cutoff for low filter
- Low Filter Q: 0.20 - 1.00 | Sets resonance for low filter
- Diffusion: 0.1% - 96% | Controls echo density of reverb tail
- Scale: 5.0% - 100% | Adjusts diffusion coarseness and tonal colour

CHORUS
- Chorus: On/Off | Toggles modulation in reverb tail
- Amount: 0.01 - 4.00 | Sets modulation amplitude
- Rate: 0.01 Hz - 8.00 Hz | Sets modulation rate

DECAY SECTION
- Predelay: 0.50 ms - 250 ms | Sets time before first reflection
- Size Smoothing: None / Slow / Fast | Defines how smoothly Size transitions are applied
- Size: 0.22 - 500.00 | Sets virtual room size
- Decay Time: 200 ms - 60.0 s | Sets time for reverb to decay to -60 dB
- Freeze: On/Off | Sustains infinite reverberation
- Flat: On/Off | Bypasses filters when Freeze is active
- Cut: On/Off | Prevents new input from entering Freeze buffer
- Stereo: 0.00 - 120.00 | Adjusts stereo width of output
- Density: Sparse / Low / Mid / High | Sets processing density (higher values use more CPU)

OUTPUT / MIX
- Reflect: -30 dB - 6.0 dB | Adjusts early reflection level
- Diffuse: -30 dB - 6.0 dB | Adjusts tail diffusion level
- Dry/Wet: 0.0% - 100% | Balances dry and wet signal (set to 100% for return tracks)
```

##### [Back to Top](#table-of-contents)

### Saturator

```text
PLUGIN: Saturator (Saturator.adv)
Type: Audio Effect (.adv)

Purpose
- Harmonic distortion and signal colouring tool for shaping tone and saturation character

SHAPING & COLOUR
- Curve Type: Analog Clip / Soft Sine / Bass Shaper / Medium Curve / Hard Curve / Sinoid Fold / Digital Clip / Waveshaper | Selects shaping curve for input signal
- Post Clip Mode: No Clip / Soft Clip / Hard Clip | Defines post-clipping stage behaviour
- Color On: On/Off | Enables pre- and post-shaper EQ coloration filters
- Color Amount Low (Amt Lo): -100% - 100% | Adjusts saturation applied to low frequencies

LEVELS & MIXING
- Input Drive: -36 dB - 36 dB | Sets input gain before shaping stage
- Output Level: -36 dB - 0.0 dB | Controls output level after saturation
- Dry/Wet: 0.0% - 100% | Balances processed and dry signal
- Expanded View Toggle: Show/Hide | Displays Waveshaper and Colour Filter parameters

COLOUR FILTERS (EXPANDED VIEW)
- Color Curve | Displays colour EQ curve; drag to shape filter response
- Color Amount High (Amt Hi): -100% - 100% | Adjusts high-frequency saturation amount
- Color Frequency: 30 Hz - 18.5 kHz | Sets target frequency of high colour filter
- Color Width: 0.0% - 100% | Sets range affected by high colour filter

WAVESHAPER (EXPANDED VIEW)
- Waveshaper Drive: 0.0% - 100% | Sets amount of Waveshaper influence
- Waveshaper Curve: 0.0% - 100% | Adjusts harmonic shaping intensity
- Waveshaper Depth: 0.0% - 100% | Adds sine modulation depth to curve
- Waveshaper Linearity: 0.0% - 100% | Adjusts linear response section
- Waveshaper Damping: 0.0% - 100% | Flattens centre of waveform for gating-like effect
- Waveshaper Period: 0.0% - 100% | Controls number of sine wave oscillations
```

##### [Back to Top](#table-of-contents)

### Spectrum
<a id="spectrum-default-plugin"></a>

```text
PLUGIN: Spectrum (Spectrum.adv)
Type: Audio Effect (.adv)

Purpose
- Frequency analysis tool displaying real-time spectral data for monitoring and mix evaluation

FFT AND ANALYSIS
- FFT Block Length (Block): 2048 / 4096 / 8192 / 16384 | Sets FFT size; higher values increase accuracy and CPU load
- Channel: L / R / L+R | Selects input channel for analysis
- Refresh Time (Refresh): 40.0 ms - 200 ms | Sets measurement interval; lower values increase responsiveness
- Number of Averages (Avg): 1 - 8 | Averages FFT blocks for display stability

DISPLAY OPTIONS
- Graph: Line / Bins | Switches between continuous line or discrete bin display
- Maximum Amplitude (Max): On/Off | Displays peak spectrum levels; click display to reset
- Scale X: Lin / Log / ST | Selects x-axis scaling (linear, logarithmic or note values)
- Scale Y Range: Auto / Range | Defines visible amplitude range

DYNAMIC RANGE
- Dynamic Range Maximum: -200 - 40 | Sets upper boundary of display range
- Dynamic Range Minimum: -140 - 30 | Sets lower boundary of display range
```

##### [Back to Top](#table-of-contents)

### Tuner
<a id="tuner-default-plugin"></a>

```text
PLUGIN: Tuner (Tuner.adv)
Type: Audio Effect (.adv)

Purpose
- Pitch analysis tool for instrument and vocal tuning with visual accuracy modes

DISPLAY MODES
- Show Classic View | Displays pitch as a moving ball on a curve with note name centered (standard tuner style)
- Show Histogram View | Displays pitch over time; flat and sharp deviations shown below/above grey reference lines

VIEW BEHAVIOUR
- Target/Strobe Switch: Target / Strobe | Target shows deviation on a curve; Strobe uses rotating bands to show sharp/flat (Classic View only)
- Auto Pitch Following: Auto / Manual | Automatically centres display around incoming pitch (Histogram View only)

DISPLAY SETTINGS
- Hertz/Cents Switch: Hz / ct | Toggles between absolute frequency and cents deviation
- Reference Pitch: 410 Hz - 480 Hz | Sets tuning reference (default 440 Hz standard pitch)
```

##### [Back to Top](#table-of-contents)

### Utility

```text
PLUGIN: Utility (Utility.adv)
Type: Audio Effect (.adv)

Purpose
- Multi-function gain, phase and stereo management tool for signal correction and shaping

INPUT
- Left/Right Phase | Inverts selected channel polarity for phase correction or stereo effects
- Channel Mode: Left / Stereo / Right / Swap | Chooses or swaps signal channels
- Stereo Width: 0% - 400% | Adjusts stereo image width (0% mono, >100% widens field)
- Mono: On/Off | Converts stereo input to mono
- Bass Mono: On/Off | Converts low frequencies to mono to prevent phase issues
- Bass Mono Frequency: 50 Hz - 500 Hz | Sets crossover frequency for Bass Mono
- Bass Mono Audition | Monitors low-frequency content for Bass Mono tuning

OUTPUT
- Gain: -∞ dB - 35.0 dB | Adjusts output level
- Balance: 50L - 50R | Pans signal between left and right channels
- Mute: On/Off | Silences output signal
- DC: On/Off | Removes DC offset and subsonic frequencies
```

##### [Back to Top](#table-of-contents)

### Third-Party Plugins

A–Z list of third-party plugins.

## Youlean Loudness Meter

Download here:  
[Youlean Loudness Meter](https://youlean.co/youlean-loudness-meter/) (Use the VST3 plugin – compatible with Windows and Mac)

```text
PLUGIN: Youlean Loudness Meter  
Type: VST3 Plugin  

Purpose  
- Loudness, dynamic range and true peak metering for mastering and broadcast compliance  

METERING CONTROLS  
- Target Preset: None | Disables automatic standard selection for manual metering control  
- Metering Mode: LUFS + True Peak | Displays both loudness and inter-sample peaks for full mix analysis  
- Integrated LUFS | Measures average loudness over full track duration (use -14 LUFS for streaming, -9 LUFS for club masters)  
- Short-Term LUFS | Displays 3-second rolling loudness for dynamic consistency; aim for stability within ±3 LU of integrated value  
- Momentary LUFS | Shows instantaneous loudness for transient detail monitoring  
- True Peak: Display | Indicates inter-sample peak level; should not exceed -1.0 dBTP  
- Loudness Range (LRA): Display | Shows program dynamic range; 5–8 LU for controlled masters, 8–12 LU for natural mixes  
- Graph View: On/Off | Displays loudness history and dynamics over time  
- Refresh Rate: Default | Controls display update frequency; default provides smooth metering  
- X-Axis: None | Leaves display in standard loudness timeline mode  
- Y-Axis: None | Disables alternative scaling for simplified mastering view  
- Reset Meters | Clears previous readings before final playback check  

OUTPUT & EVALUATION  
- Reference Level | Compare Integrated LUFS and True Peak against platform targets  
- Output Trim (if available): -12 dB - 12 dB | Use to fine-tune loudness without affecting dynamics  

Recommended Master Targets  
- Streaming: -14 LUFS Integrated / -1.0 dBTP  
- Broadcast: -23 LUFS Integrated / -1.0 dBTP  
- Club / CD: -9 LUFS Integrated / -0.8 dBTP  

Use Youlean Loudness Meter last in the mastering chain to measure the final rendered signal before export.
```

##### [Back to Top](#table-of-contents)
