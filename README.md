# Hacker News Email Digest

Automated Python script that scrapes Hacker News and sends daily email digests.

## Features
- Web scraping of Hacker News top stories
- HTML formatted email digest
- Automated email delivery via Gmail SMTP
- Daily timestamp in subject line

## Setup
1. Clone the repository
```bash
git clone https://github.com/yourusername/hacker-news-digest.git
cd hacker-news-digest
```

2. Install dependencies
```bash
pip install requests beautifulsoup4
```

3. Configure Gmail credentials
- Enable 2-Step Verification in Google Account
- Generate App Password for Gmail
- Update credentials in config file

## Usage
```bash
python hacker-news.py
```

## Configuration
Update the following variables in `hacker-news.py`:
```python
FROM = 'your-email@gmail.com'
TO = 'recipient-email@domain.com'
PASS = 'your-16-digit-app-password'
```