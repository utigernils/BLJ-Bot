# BLJ-Admin Discord Bot

BLJ-Admin is a Discord bot designed to automate and simplify various administrative tasks on a Discord server. With BLJ-Admin, users can check their balance, delete messages, order products, and get information about bus connections, among other features.

## Installation

To use BLJ-Admin in your Discord server, follow these steps:

1. Clone this repository to your local machine.
2. Customize the configuration file according to the instructions in `config.py.example`, and rename it to `config.py`.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Run the Python script `blj_admin.py` to start the bot.

## Usage

BLJ-Admin supports the following commands:

### General Commands

- `!hello`: Get a greeting message from the bot and find out how long the bot has been online.
- `!balance`: Check your current balance on the server.
- `!clear <amount>`: Delete a specified number of messages in the current channel (only for moderators).

### Recharging Balance

- `!recharge <amount>`: Recharge your balance. The amount must be greater than 0. Recharging requires confirmation from specific individuals.
- `!confirmrecharge <user-ID>`: Confirm a balance recharge (only for authorized individuals).
- `!declinerecharge <user-ID>`: Decline a balance recharge (only for authorized individuals).
- **To create an account, contact the owner.**

### Ordering Products

- `!order <product name> <quantity>`: Order a product in a specified quantity.
- `!confirm`: Confirm your order if you have enough balance.
- `!cancel`: Cancel the current order.

### Bus Connections

- `!bus`: Get information about bus connections between "Adligenswil, Stuben" and "Luzern, Bahnhof".

## License

[License information is still missing]

## Contributing

Contributions to BLJ-Admin are welcome! Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

## Contact

For questions, issues, or feedback, feel free to reach out to the developer at [mail@utigernils.ch](mailto:mail@utigernils.ch).
