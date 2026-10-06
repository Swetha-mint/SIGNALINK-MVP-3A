# SIGNALINK MVP-3A — Audio → Haptic Bridge

A browser test space for a non-visual communication path.

## Objective
Explore whether environmental audio characteristics can be converted into simple tactile events without depending on a visual output.

## Pipeline
Audio input → Web Audio FFT → frequency/level features → haptic pattern → simulated actuator

## Patterns
- Higher-frequency activity → rapid pulse pattern
- Lower-frequency activity → longer rhythmic pulses
- Low activity → idle

## Engineering value
This is a software proof of the signal-processing and decision layer. The browser vibration API is only a simulation of a future ESP32 GPIO/PWM-driven actuator.

## Important limitation
This prototype does not claim speech recognition, clinical accessibility performance, or hardware readiness. It tests the control concept.

Theory → Build → Measure → Explain → Hardware
