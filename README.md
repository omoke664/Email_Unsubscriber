# Email Unsubscriber

A Python program that connects to your email account, searches for emails, and extracts unsubscribe links from them. This tool is particularly useful for managing unwanted email subscriptions.

## Features

- Connects to Gmail using IMAP.
- Extracts unsubscribe links from email content using regex.
- Supports extraction from both the email body and headers.
- Configurable to limit the number of emails processed and the time frame for searching.

## Requirements

- Python 3.x
- Required Python packages:
  - `imaplib`
  - `email`
  - `os`
  - `logging`
  - `re`
  - `dotenv`
  - `concurrent.futures`
  - `html2text`
  - `requests` (if you plan to use it for anything else)
  - `urllib.parse`

You can install the required packages using pip:





