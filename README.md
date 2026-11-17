# 【entity-Meta¦canonical_name=Meta】 Vision Lab - Real-time Vision Augmentation for Quest 3

Turn any HDMI source (【entity-PS5¦canonical_name=PS5】, Fire Stick, PC) into 3D, enhanced vision in 【entity-Meta¦canonical_name=Meta】 Quest 3.
No gaming PC needed. Just Quest 3 + UVC capture card.

## What is this?

A single 【entity-Unity¦canonical_name=Unity】 app for Quest 3 with 4 experiments:

1.  **HDMI Capture + Upscaler:** 【entity-PS5¦canonical_name=PS5】 in a giant virtual screen with FSR upscaling.
2.  **Fake Depth Map to 3D:** Convert any flat game to 3D automatically using Depth Anything V2 Small + head-motion.
3.  **Animal Vision:** Head-tracked stabilization, focal zoom, predator/prey modes.
4.  **Night Vision:** Use Quest IR cameras + TV remote IR emitter to see in the dark.

## Current Status - v0.1

- [x] 【entity-PS5¦canonical_name=PS5】 HDMI capture working in Quest 3
- [ ] Depth Anything V2 Small integration (in progress)
- [ ] Animal Vision modes
- [ ] IR Night Vision

## Hardware Used

- Meta Quest 3
- 【entity-PS5¦canonical_name=PS5】 (HDMI source)
- Generic UVC HDMI to USB Capture Card
- Amazon Fire Stick 4K (second test source)
- 【entity-Mac¦canonical_name=Mac】 (【entity-Unity¦canonical_name=Unity】 6000.6)

## Why is this different?

Most VR tools need a powerful PC. This project runs everything inside Quest 3 with lightweight AI.

## How to test?

See `/Docs/01-PS5-Capture.md` for full setup.

## Author

David Ramirez - Costa Rica
Beginner in Unity, learning in public. All progress documented here.

## License
MIT
