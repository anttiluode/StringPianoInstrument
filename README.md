#  String Piano Instrument

A live audio-visual synthesizer that transforms webcam input into music through motion detection and visual control.

## What It Does

The String Piano Instrument creates a unique musical interface where:
- **10 individual strings** each produce different musical notes (C2-C7 range)
- **Motion detection zones** on the right side of the screen control string pitch
- **Real-time visual feedback** shows active notes on a piano display
- **Manual controls** allow fine-tuning of each string

## How to Use

1. Open `index.html` in a modern web browser
2. Click "ACTIVATE PIANO" and grant camera permissions
3. Move up and down in the right-side zones to control string pitch
4. Watch the piano keys light up as notes activate
5. Use the left-side controls for manual adjustment

## Features

- **Motion Zone Control**: Right side divided into 10 zones, each controlling one string
- **Visual Piano Display**: Real-time visualization of active notes
- **Individual String Controls**: Manual sliders and buttons for each string
- **Audio Parameters**: Adjustable volume, motion sensitivity, and note smoothing
- **Pure Web Technology**: No plugins required - runs entirely in browser

## Technical Details

- Built with vanilla JavaScript and Web Audio API
- Uses webcam for real-time motion detection
- No server required - fully client-side application
- Compatible with modern browsers supporting getUserMedia

## Controls

- **Master Volume**: Overall audio level
- **Motion Sensitivity**: How much movement affects pitch changes
- **Note Smoothing**: Speed of note transitions
- **String Sliders**: Direct pitch control for each string
- **+/- Buttons**: Fine-tune individual string notes

## Browser Compatibility

Requires a modern browser with:
- WebRTC (getUserMedia) support
- Web Audio API support
- HTML5 Canvas support

Tested on Chrome, Firefox, Safari, and Edge.

## Live Demo

Simply download and open `index.html` - no installation required!

---

*Experience music through movement. Point your camera and play.*
This README gives users everything they need to understand and use your String Piano Instrument! 🎹✨
