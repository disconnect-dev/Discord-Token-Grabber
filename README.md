# Discord Token Extractor

![rounded-image (1)](https://github.com/user-attachments/assets/482b8dcd-32b2-494e-93b3-2857cc6e9793)

## Features

- Extracts tokens from popular browsers
- Decrypts protected tokens
- Validates tokens against Discord API
- Collects account metadata
- Analyzes user servers and relationships
- Reports results via Discord Webhook

## Supported Browsers

- Discord (Stable, Canary, PTB)
- Chrome
- Edge
- Opera/Opera GX
- Brave
- Yandex

## Requirements

- Python 3.6+
- requests
- pycryptodome
- pywin32 (Windows only)

## Usage

1. Set your webhook URL in `Grabber.py`
2. Run the script:

```python
python main.py
```

## How It Works

The extractor scans browser storage files for tokens using regex patterns, decrypts them when necessary, validates them against Discord's API, and collects account metadata for reporting.

## Disclaimer

This tool is for educational purposes only. Unauthorized use violates Discord's Terms of Service and may be illegal. Use only on your own accounts or with explicit permission.

## Security Tips

- Enable 2FA on your Discord account
- Regularly check active sessions
- Use strong passwords
- Be cautious with browser extensions
