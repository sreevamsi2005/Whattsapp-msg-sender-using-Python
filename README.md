# Whattsapp-msg-sender-using-Python
# Usage

1. Install PyWhatKit using pip: pip install pywhatkit
2. Replace the phone number in the script with the recipient's phone number (including the country code).
3. Run the script using Python (e.g., python (link unavailable)).

- phone_number: The recipient's phone number (including the country code).
- message: The message to be sent.
- hour: The hour to send the message (in 24-hour format).
- minute: The minute to send the message.

Example

The script sends the message "HI, This msg was sent by python code" to the phone number "+910123456789" at 20:30.

Note

Make sure to install the necessary dependencies and configure your WhatsApp account to work with PyWhatKit before running the script.

Code


import pywhatkit as pwt
pwt.sendwhatmsg("+910123456789", "HI, This msg was sent by python code ", 20, 30)
