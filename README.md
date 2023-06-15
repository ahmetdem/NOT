# Notification from Website

This project is a Python script that sends a notification to your desktop when a website changes. It uses the `requests` and `beautifulsoup4` libraries to fetch and parse the website's HTML, and the `email` library to send an email.

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the `notification_from_website` folder.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Edit the `main.py` to specify the website URL and the element you want to get and go from there.
5. Run the script by executing `python main.py`.

## Usage

Once the script is running, it will periodically check the website for changes. If a change is detected, it will display a notification with the specified message.
