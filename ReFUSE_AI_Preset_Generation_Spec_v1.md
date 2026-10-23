# ReFUSE AI Preset Generation Specification

Version: 1.0
Purpose: AI-optimized specification for generating valid ReFUSE .fuse preset files.

---

# Mission

This document is intended for AI systems generating ReFUSE presets.

Primary objectives:

1. Generate valid .fuse files.
2. Follow documented ReFUSE signal-chain rules.
3. Select components that best recreate the requested sound.
4. Produce playable and practical presets.

---

# Tone Creation Rules

Priority Order:

1. Replicate the sound.
2. Preserve feel and playability.
3. Match original gear when practical.

Default Usage Target:

- Home playing
- Recording
- Rehearsal
- Usable live performance

Default Guitar Assumption:

- Fender Telecaster
- Standard single-coil pickups

Artist Request Hierarchy:

1. Song
2. Album
3. Era/Tour
4. Artist
5. Genre

Default Reference:

- Most recognizable studio tone.

---

# ReFUSE Preset Construction Workflow

Step 1:
Determine target tone.

Step 2:
Determine available information.

Required inputs when available:

- Guitar
- Pickup type
- Desired artist/song/genre
- Platform version

Step 3:
Select amp model.

Step 4:
Select cabinet.

Step 5:
Build legal signal chain.

Step 6:
Assign parameters.

Step 7:
Generate .fuse XML.

Step 8:
Provide guitar recommendations.

---

# Signal Chain Rules

General Chain:

Input
→ Pre-Amp Effects
→ Amp
→ Post-Amp Effects
→ Output

Available Categories:

- Stomp
- Modulation
- Delay
- Reverb

Rule:
Only use legal module positions documented by ReFUSE.

Avoid unnecessary complexity.

Prefer:

Amp
→ Delay
→ Reverb

unless the requested tone requires otherwise.

---

# Preset Design Philosophy

Prefer:

- Simple signal chains
- Musical settings
- Realistic gain staging
- Practical EQ values

Avoid:

- Maximum parameter values
- Excessive bass
- Excessive gain
- Excessive ambience

unless specifically required.

---

# Blues Knowledge Base

Status:
Trained

Preferred Amps:

- 65 Deluxe Reverb
- 65 Twin Reverb
- 59 Bassman
- Super-Sonic
- 57 Deluxe

Typical Gain:

- Edge of breakup
- Approximate median gain: 3.7

Typical EQ:

Treble: 5.6
Middle: 4.4
Bass: 4.4

Common Effects:

- Spring Reverb
- Overdrive
- Compressor
- Chorus
- Tremolo

Delay Usage:

- Limited
- Style dependent

Reverb Usage:

- Strongly preferred

---

# Artist Profiles

John Mayer:

- Deluxe Reverb
- Overdrive
- Tremolo
- Spring Reverb

Texas Blues:

- Deluxe Reverb
- Compressor
- Chorus
- Spring Reverb

Hendrix-Inspired Blues:

- Bassman
- Tape Delay
- Increased gain
- Reduced mids

Slide Blues:

- Twin Reverb
- Strong mids
- Minimal effects

Vintage Blues:

- Deluxe Reverb
- Mild overdrive
- Echo or reverb
- Darker EQ

---

# Required Output Structure

Preset Information:

- Preset Name
- Target Tone
- Assumptions
- Amp
- Cabinet
- Signal Chain
- Parameters

Guitar Settings:

- Pickup Selection
- Guitar Volume
- Guitar Tone
- Pick Attack
- Technique Guidance
- Performance Notes

---

# Future Training Areas

Pending:

- Country
- Worship
- Classic Rock
- Metal
- Community Preset Analysis
- Advanced Artist Profiles

---

# Source Documents

- ReFUSE - How To Make .fuse Preset Files
- Factory Preset Examples
- ReFUSE Project Memory Files
- ReFUSE Preset Engineer Knowledge Base

This document acts as the technical specification used by AI systems when generating ReFUSE presets.
