# Electronic Scoreboard

## Overview

The **Electronic Scoreboard** project is an innovative solution designed to enhance the experience of scoring in badminton matches. Utilizing an Arduino module and an LCD display, this project allows referees to easily track and update the scores of two players. The scoreboard supports manual updates via push buttons and voice recognition commands for greater convenience and accuracy.

## Features

- **Score Display:** Real-time score display for a badminton match on an LCD screen.
- **Manual Score Update:** Update scores manually using push buttons.
- **Voice Recognition:** Score updates through voice commands:
  - **"Advantage"** for advantage points.
  - **"Deuce"** for deuce situations.
  - **"Player 1"** for incrementing Player 1's score.
  - **"Player 2"** for incrementing Player 2's score.
- **Match End Condition:** The match ends automatically when one player reaches 21 points.

## Components

- **Arduino Board:** Acts as the central controller for the scoreboard.
- **LCD Display:** Shows the current score of the match.
- **Push Buttons:** Used for manual score updates.
- **Microphone Module:** Captures voice commands for voice recognition.
- **Voice Recognition Module:** Interprets voice commands and updates scores accordingly.
- **Power Supply:** Provides the necessary power for the entire system.

## Installation

1. **Hardware Setup:**
   - Connect the LCD display to the Arduino according to the provided wiring diagram.
   - Attach the push buttons to the designated pins on the Arduino.
   - Set up the microphone and voice recognition modules as per the connection guidelines.

2. **Software Setup:**
   - Download the Arduino IDE from [Arduino's official website](https://www.arduino.cc/en/software).
   - Clone this repository to your local machine:
     ```bash
     git clone https://github.com/yourusername/electronic-scoreboard.git
     ```
   - Open the project in the Arduino IDE.
   - Install any required libraries as indicated in the `libraries.txt` file.
   - Upload the code to your Arduino board.

3. **Configuration:**
   - Ensure that the voice recognition module is calibrated to recognize the specified commands.
   - Adjust the pin configurations in the code if necessary, depending on your hardware setup.

## Usage

- **Manual Score Updates:** Press the designated push buttons to increment the score of either player.
- **Voice Commands:** Speak the commands clearly into the microphone:
  - "Advantage" to give advantage points.
  - "Deuce" to set the game to deuce.
  - "Player 1" or "Player 2" to increment the respective player's score.

- The LCD display will automatically update to reflect the current score and match status.

## Troubleshooting

- **LCD Not Displaying:** Check the wiring connections and ensure the LCD is properly powered.
- **Voice Recognition Issues:** Verify that the voice recognition module is correctly configured and responsive to commands.
- **Score Not Updating:** Ensure that the push buttons and voice commands are properly connected and functioning.

## Contributing

Feel free to contribute to this project by submitting issues, proposing changes, or submitting pull requests. Your contributions are welcome and appreciated!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or support, please contact [nilesh.srrm@gmail.com](mailto:nilesh.sriram@gmail.com)

---

Thank you for checking out the Electronic Scoreboard project! We hope it brings efficiency and ease to scoring your badminton matches.
