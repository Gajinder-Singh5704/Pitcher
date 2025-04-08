PITHCER

🎙️ Audio Recorder & Effects App
This iOS app allows users to record audio and play it back with various sound effects, using a clean two-screen interface powered by UINavigationController.

📱 Features
Two main scenes:

Recording Screen – Record audio with start/stop functionality.

Playback Screen – Play recorded audio with sound effects.

Adaptive layout for iPhone & iPad in both Portrait and Landscape orientations.

UI updates dynamically (e.g., buttons enabled/disabled appropriately).

🎛️ Sound Effects
Playback screen includes 6 sound effect buttons:

🐌 Slow (Snail)

🐇 Fast (Rabbit)

🎈 High Pitch (Chipmunk)

🎤 Low Pitch (Darth Vader)

🔁 Echo

🎶 Reverb

🛠️ Technical Highlights
Uses AVAudioRecorder and AVAudioPlayer for audio handling.

Uses @IBAction methods for UI interactions.

Implements audioRecorderDidFinishRecording() delegate method.

Transitions between screens with performSegue(withIdentifier:).

Supports re-recording by navigating back using UINavigationController.

Clean, modular, and reusable Swift code with helpful comments and proper naming conventions.
