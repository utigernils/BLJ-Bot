# BLJ-Admin Discord Bot

BLJ-Admin is a Discord bot designed to automate and simplify various administrative tasks on a Discord server. With BLJ-Admin, users can check their balance, delete messages, order products, get information about bus connections, and more. Additionally, BLJ-Admin includes a feature to block gifs in certain channels and remind the user who sent the gif via direct message.

## Installation

To use BLJ-Admin in your Discord server, follow these steps:

1. Clone this repository to your local machine.
2. Customize the configuration.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Run the Python script `blj_admin.py` to start the bot.

## Usage

BLJ-Admin supports the following commands:

### General Commands

- `!hallo`: Get a greeting message from the bot and find out how long the bot has been online.
- `!kontostand`: Check your current balance on the server.
- `!clear <amount>`: Delete a specified number of messages in the current channel (only for moderators).

### Recharging Balance

- `!aufladen <amount>`: Recharge your balance. The amount must be greater than 0. Recharging requires confirmation from specific individuals.
- `!bestätigenaufladung <user-ID>`: Confirm a balance recharge (only for authorized individuals).
- `!ablehnenaufladung <user-ID>`: Decline a balance recharge (only for authorized individuals).
- **To create an account, contact the owner.**

### Ordering Products

- `!bestellen <product name> <quantity>`: Order a product in a specified quantity.
- `!bestätigen`: Confirm your order if you have enough balance.
- `!abbrechen`: Cancel the current order.

### Bus Connections

- `!bus`: Get information about bus connections between "Adligenswil, Stuben" and "Luzern, Bahnhof".

### Additional Features

- **GIF Blocking**: BLJ-Admin has the ability to block gifs in certain channels to maintain a safe and appropriate environment.
- **GIF Reminder**: When a gif is sent in a channel where gifs are blocked, BLJ-Admin reminds the user who sent the gif via direct message.
- **Order System**: The authorized individuals also get access to view the balance of everyone and order reminders via direct message.

## Contributing

Contributions to BLJ-Admin are welcome! Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

## Contact

For questions, issues, or feedback, feel free to reach out to the developer at [mail@utigernils.ch](mailto:mail@utigernils.ch).
