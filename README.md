# SafeRide

SafeRide is an emergency response web application designed for vehicles (cars, motorcycles, and bikes). In the event of a crash, it triggers an SOS response, including sounding an alarm, listing nearby hospitals, simulating calls to police and ambulance services, and notifying loved ones.

## Features

- **Crash Detection**: Simulates crash detection (extendable with device sensors in a native app).
- **Alarm Sound**: Plays a siren sound upon crash detection.
- **Emergency Calls**: Provides clickable links to call police or ambulance (uses `tel:` protocol).
- **Nearby Hospitals**: Displays a list of nearby hospitals (mock data; extendable with a maps API).
- **Notify Loved Ones**: Simulates sending notifications to predefined contacts.

## Demo

This is a web-based prototype. Open `index.html` in a browser to test the app. Click the "Simulate Crash" button to trigger SOS actions.

## Prerequisites

- A modern web browser (Chrome, Firefox, Safari, etc.).
- Internet connection.
- Audio-enabled device to hear the alarm.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/techdrivex/SafeRide.git
   ```
2. Navigate to the project directory:
   ```bash
   cd SafeRide
   ```
3. Open `index.html` in a web browser:
   ```bash
   open index.html
   ```

No additional dependencies are required.

## Usage

1. Open the app in a browser.
2. Click the **Simulate Crash** button to trigger the SOS response.
3. Observe the following actions:
   - An alarm sound plays.
   - Emergency call links for police and ambulance appear.
   - A list of nearby hospitals (mock data) is displayed.
   - A notification status updates to simulate contacting loved ones.
4. Use the `tel:` links to initiate calls (prompts your device’s dialer).

## Extending the App

To make SafeRide production-ready:

- **Crash Detection**: Integrate with device accelerometers or vehicle OBD-II systems (e.g., using React Native).
- **Maps API**: Use Google Maps or OpenStreetMap for real hospital data.
- **Messaging**: Add Twilio or SendGrid for SMS/email notifications.
- **Native App**: Port to React Native or Flutter for sensor access and direct calling.
- **Custom Alarm**: Replace the base64 audio with a louder, externally hosted sound file.

## Contributing

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request.

Please ensure your code follows the existing style and includes comments for clarity.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Ride with confidence—emergency help at your fingertips!
