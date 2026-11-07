 🖐️ AI Hand-Tracking Web Interface project : 

A browser-based interface where hand gestures control a virtual electronic circuit in real time. An open hand turns the LED ON, and a fist turns it OFF. Everything runs in the browser, so no hardware or install is needed.


 How it works :
1. Camera input: the webcam feed is read in the browser.
2. AI classification: a neural network trained with Google Teachable Machine classifies each frame as `ON` (open hand) or `OFF` (fist).
3. Inference: the model runs locally with TensorFlow.js, so no video leaves your device.
4. Circuit response: an animated SVG circuit lights the LED when `ON`

Tech stack :
- HTML, CSS, JavaScript
- TensorFlow.js
- Teachable Machine (image model)

Files: 
- index.html: the full app (interface, circuit, AI logic)

Run it :
1. Open the live demo link.
2. Tap Start camera and allow access.
3. Show an open hand to light the LED, or a fist to turn it off.

 Possible improvements :
- Add more gestures (thumbs up, peace sign) to control several components
- Use MediaPipe Hands for true 21-point hand tracking
- Send the gesture to a real ESP32 over Wi-Fi or Web Serial to drive a physical LED or relay

Author :
Salem Ben Salah · [GitHub: TechGeek-SA]
