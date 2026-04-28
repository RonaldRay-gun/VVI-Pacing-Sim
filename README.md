VVI EPG Simulator

A browser-based VVI pacemaker teaching simulator designed to demonstrate core electrophysiology concepts including sensing, pacing, capture, oversensing, and ventricular rate behavior.

This tool is intended for education, demos, and training, providing a simplified but clinically meaningful visualization of how a VVI device behaves under different conditions.

⸻

Features

Real-Time EKG Simulation

* Continuous scrolling ventricular rhythm strip
* Distinct intrinsic vs paced QRS morphologies
* Visible pacing spikes

VVI Pacemaker Logic

* Lower rate pacing (VVI mode)
* Ventricular sensing with adjustable sensitivity
* Proper inhibition behavior
* Post-pace suppression of intrinsic activity

Capture vs Non-Capture

* Adjustable output (mA) and capture threshold
* Captured pacing produces QRS
* Non-capture shows spike only (no depolarization)

Oversensing Demonstration

* Adjustable noise level
* Option to hide noise visually while still sensing it
* Demonstrates inappropriate inhibition

Heart Rate Display

* HR calculated from true ventricular depolarizations only
* Includes:
    * Intrinsic beats
    * Captured paced beats
* Excludes:
    * Noise
    * Non-captured pacing
* Drops to 0 when no QRS is present

Visual Indicators

* VP (green LED): ventricular pacing
* VS (blue LED): ventricular sensing

⸻

🎛 Controls

Knobs

Control	Description
Lower Rate (bpm)	Minimum pacing rate
Sensitivity (mV)	Lower = more sensitive (detects smaller signals)
Output (mA)	Determines whether pacing captures

Advanced Controls

Control	Description
Intrinsic Rate	Simulated underlying rhythm
Noise	Electrical interference amplitude
Capture Threshold	Minimum output required for capture

Buttons

* Advanced → Show/hide advanced controls
* Hide/Show Noise → Visual toggle (does NOT affect sensing)

⸻

Scenarios

Scenario 1 – VVI Pacing

* LRL: 80 bpm
* Intrinsic: 0 bpm
* Normal capture
    Demonstrates baseline pacing

⸻

Scenario 2 – Oversensing

* LRL: 80 bpm
* Intrinsic: 20 bpm
* High noise, high sensitivity
* Noise hidden

Demonstrates:

* Inhibition due to oversensing
* Mismatch between device sensing (VS) and actual rhythm

⸻

Scenario 3 – Non-Capture

* LRL: 60 bpm
* Output below capture threshold
* No intrinsic rhythm

Demonstrates:

* Pacing spikes without depolarization
* HR dropping to 0

⸻

Educational Concepts Demonstrated

* VVI pacing behavior
* Sensing vs true depolarization
* Oversensing and pacing inhibition
* Capture vs loss of capture
* Relationship between output and threshold
* Difference between device interpretation and surface EKG

⸻

How to Use

1. Save the file as:

vvi_epg_simulator.html

2. Open in any browser:
    * Safari
    * Chrome
    * Edge
3. Interact with:
    * Knobs (click + drag)
    * Sliders
    * Scenario buttons

⸻

Notes

* This is a teaching tool, not a clinical simulator
* Signal morphology is simplified
* Timing and sensing are modeled for clarity, not full device fidelity

⸻

Future Enhancements (Ideas)

* Fusion and pseudofusion beats
* Dual-channel (surface vs sensed signal view)
* Adjustable refractory and blanking periods
* Additional pacing modes (DDD, VOO, etc.)

⸻

Summary

This simulator provides a clear, interactive way to teach pacemaker fundamentals, especially:

“What the device thinks vs what actually happens”

It is ideal for:

* EP training
* Device education
* Case-based teaching
* Live presentations

–

::
