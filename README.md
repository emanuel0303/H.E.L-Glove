# H.E.L Glove Project 🛡️⚡🌐

Welcome to the H.E.L Glove project repository! The H.E.L Glove is a cutting-edge wearable device designed to prioritize personal safety and security. This innovative glove integrates an electric shock mechanism with advanced GPS and GSM modules, providing users with a powerful tool for self-defense and emergency response.

## Running the Project 🚀

To run the H.E.L Glove project, follow these steps:

### Arduino Code
Use the provided Arduino code to program your Arduino board. This code manages the interaction with the glove's hardware components, including the electric shock mechanism, GPS module, and button input.

### Python Code
Utilize the provided Python code on your computer. Before running the code, ensure you have installed the required libraries (`pyserial` and `twilio`) using pip:

```markdown
pip install pyserial twilio
Next, replace the following placeholders in the Python code with your Twilio credentials and recipient phone number:

- `account_sid`: Your Twilio account SID.
- `auth_token`: Your Twilio authentication token.
- `recipient_phone_number`: The phone number where you want to receive emergency alerts.

Finally, update the `arduino_port` variable with the appropriate serial port to which your Arduino board is connected.

### Execution
Once both the Arduino and Python scripts are set up, execute the Python script. It will establish a serial connection with the Arduino board, monitor the glove's button input, and send SMS alerts using Twilio when an emergency signal is received from the glove.

With these steps completed, your H.E.L Glove project should be up and running, providing you with enhanced personal safety and security. Stay safe!

### Contributions and Support 🤝
Contributions to the H.E.L Glove project are welcome! If you have ideas for improvements or would like to report issues, feel free to open an issue or pull request in this repository.

If you encounter any difficulties while setting up or running the project, don't hesitate to reach out for support. We're here to help you make the most of your H.E.L Glove experience.

### License 📜
The H.E.L Glove project is licensed under the MIT License. Feel free to use, modify, and distribute the code for personal or commercial projects.

Enjoy your H.E.L Glove journey, and stay safe and empowered! 🛡️💪
