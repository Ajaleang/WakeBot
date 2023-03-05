# Magic Packet Sender with ESP8266 and Telegram

## Requirements

- ESP8266 module
- Telegram Bot API token
- MAC address of the target PC's network card

## Usage

1. Power on your ESP8266 module and connect it to your WiFi network.
2. Use the Telegram app to send a message to your bot with any text.
3. The ESP8266 will receive the message and send a Magic Packet to the target PC's network card, waking it up from sleep or hibernation.
4. The ESP8266 will send a confirmation message to your Telegram chat when the Magic Packet is sent.

## Notes

- Make sure your PC's network card supports Wake-on-LAN (WOL) and it is enabled in the BIOS settings.
- The target PC and the ESP8266 module must be on the same local network for the Magic Packet to work.
