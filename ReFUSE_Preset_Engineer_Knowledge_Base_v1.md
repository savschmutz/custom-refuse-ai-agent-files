# ReFUSE Preset Engineer Knowledge Base

Version: 1.0
Last Updated: 2026-10-23

## Project Overview

ReFUSE is a custom replacement for Fender FUSE.

Goal:
- Generate guitar amp and effects presets from natural-language requests.
- Prioritize reproducing the target sound rather than replicating the exact original equipment.
- Provide detailed guitar setup recommendations.
- Eventually generate importable ReFUSE preset files.

---

# Core Tone Philosophy

Priority Order:

1. Replicate the sound.
2. Preserve feel and playability.
3. Match original equipment when practical.

Design Principles:

- Prefer practical and musical presets.
- Avoid excessive effects unless stylistically required.
- Favor usable real-world tones.
- Optimize for home playing while remaining suitable for rehearsal and live use.

---

# Default Assumptions

Unless otherwise specified:

- Guitar: Telecaster
- Pickups: Standard single coils
- Tone Reference: Most recognizable studio tone

Artist Request Priority:

1. Song
2. Album
3. Era/Tour
4. Artist
5. Genre

Examples:

- "Slow Dancing in a Burning Room" → Song tone
- "Continuum" → Album tone
- "John Mayer" → Most recognizable studio tone

Default to studio tone unless live tone is requested.

---

# Preset Generation Workflow

1. Determine target tone.
2. Identify missing equipment information.
3. Build legal ReFUSE signal chain.
4. Select amp and cabinet.
5. Select effects.
6. Assign parameters.
7. Generate ReFUSE-compatible preset.
8. Provide guitar recommendations.

---

# Required Output Format

## Preset Information

- Preset Name
- Target Tone
- Assumptions
- Amp Model
- Cabinet
- Signal Chain
- Effect Settings
- Parameter Settings

## Guitar Settings

- Pickup Selection
- Guitar Volume
- Guitar Tone
- Pick Attack
- Technique Notes
- Performance Notes

---

# Technical Foundation

Status: Complete

Learned Areas:

- Preset file structure
- Component catalog
- Parameter definitions
- Signal-chain rules

Factory Presets Reviewed:

- Fusion Lead
- Liquid Solo
- Super Flanger
- Super-Live Album
- Vee Eight

Observations:

- Factory presets favor simple signal chains.
- Delay and reverb are frequently used.
- Modulation is used selectively.
- Amp voicing is a primary contributor to tone.

---

# Community Tone Knowledge

## Blues

Status: Trained

### Preferred Amp Models

- 65 Deluxe Reverb
- 65 Twin Reverb
- 59 Bassman
- Super-Sonic
- 57 Deluxe

### Gain Philosophy

- Edge of breakup
- Median gain approximately 3.7
- Dynamic response preferred

### Typical EQ

- Treble: 5.6
- Middle: 4.4
- Bass: 4.4

### Common Effects

- Spring Reverb
- Overdrive
- Compressor
- Chorus
- Tremolo

### Effect Usage

Spring Reverb:
- Very common

Delay:
- Less common
- Use only when stylistically appropriate

Compression:
- Helpful but not mandatory

Overdrive:
- Common for lead-oriented blues tones

---

## Blues Substyles

### John Mayer Style

Typical Setup:

- Deluxe Reverb
- Overdrive
- Tremolo
- Spring Reverb

### Texas Blues

Typical Setup:

- Deluxe Reverb
- Compressor
- Chorus
- Spring Reverb

Characteristics:

- Strong mids
- Responsive dynamics

### Hendrix-Inspired Blues

Typical Setup:

- Bassman
- Tape Delay

Characteristics:

- Higher gain
- Reduced mids
- Tone knob often rolled back slightly

### Slide Blues

Typical Setup:

- Twin Reverb
- Spring Reverb

Characteristics:

- Strong mids
- Minimal effects

### Vintage Blues

Typical Setup:

- Deluxe Reverb
- Mild overdrive
- Echo or reverb

Characteristics:

- Darker EQ profile

---

# Guitar Guidance Standards

Every preset should include:

- Pickup Selection
- Guitar Volume Setting
- Guitar Tone Setting
- Pick Attack Guidance
- Technique Suggestions
- Optional Performance Notes

Example:

Pickup: Bridge
Volume: 10
Tone: 8
Pick Attack: Medium-Heavy
Technique: Hybrid Picking
Notes: Roll volume back for rhythm passages.

---

# Future Training Roadmap

In Progress:

- Tone Building Preferences
- Guitar Guidance Standards
- Artist Tone Methodology

Planned Community Training:

- Country
- Worship
- Classic Rock
- Metal

Future Enhancements:

- Large-scale community preset analysis
- Artist-specific tone databases
- Automated ReFUSE file generation
- Production ReFUSE Preset Engineer Agent

---

# Knowledge Sources

Project Memory:

- guitar_preset_project_memory_v4.yaml

Technical Documentation:

- ReFUSE - How To Make .fuse Preset Files.txt

Factory Preset References:

- Fusion Lead
- Liquid Solo
- Super Flanger
- Super-Live Album
- Vee Eight

Community Blues Training:

- Blues_reference_guide.md
- Blues_library.xml
- Blues_summary.md

This document serves as the foundational knowledge base for the ReFUSE Preset Engineer project.
