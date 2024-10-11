# Telegram Photo Bot

A Telegram bot that helps you relive memories by sending you photos from your OneDrive cloud storage that were taken on the same day in previous years. The bot allows you to view, manage, and delete photos directly through the Telegram interface, helping you clean up your photo collection while reminiscing about past moments.

## Features

- **Daily Photo Reminder**: Automatically sends photos from OneDrive that were taken on the same date in past years.
- **OneDrive Integration**: Connects to your OneDrive account to fetch and manage photos.
- **Photo Management**: Allows you to view photos directly in Telegram and delete unwanted ones.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- A Telegram account to create a bot
- OneDrive account
- Microsoft Azure App Registration (for OneDrive API access)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/WhiteIlya/OneDrive-photos-TelegramBot.git
   cd OneDrive-photos-TelegramBot

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv my_telegram_bot_env
    source my_telegram_bot_env/bin/activate

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt

4. Create a .env file in the project root with the following content:
    ```bash
    TELEGRAM_TOKEN=<your_telegram_bot_token>
    ONEDRIVE_CLIENT_ID=<your_onedrive_client_id>
    ONEDRIVE_CLIENT_SECRET=<your_onedrive_client_secret>
    ONEDRIVE_REDIRECT_URI=http://localhost:8000/
    ONEDRIVE_TENANT_ID=<your_tenant_id>


## Contributing

Feel free to open issues or submit pull requests. Contributions are always welcome.