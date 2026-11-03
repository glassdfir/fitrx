# FitRx Sessions

Ramp, hold and rest routines for a FitRx wireless TENS/EMS unit.

A single-page Web Bluetooth controller for the FitRx Wireless (HRK-016B) unit. It runs ramp up, hold, ramp down and rest cycles with presets, sets the unit's own hardware timer as a backstop, and sends level 0 on stop, errors, or leaving the page. The protocol comes from reverse-engineering the vendor's Android app; see the blog post on jon.glass.

**Good for:** Custom routines the vendor app doesn't offer. Requires Chrome (Android or desktop) and HTTPS.

**Live:** https://jon.glass/fitrx/

A single self-contained page with no build step. Open `index.html` or serve the folder over HTTPS.

## Safety

This drives an electrical stimulator worn on the body. The unit's power button, or removing a pad, is the real emergency stop. Test with the pads off first. Not a medical device; follow your clinician's guidance.
