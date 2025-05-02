# Birthday QR Code RSVP System

A web-based RSVP system for Barrister Esther Otsabomhe's birthday. Guests can register via form and receive a unique QR code via email.

## Features
- RSVP form
- Unique verification passcode
- QR code emailed to guest
- Deployable on Render, Railway, or Replit

## Setup

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```env
SENDGRID_API_KEY=your_sendgrid_key
FROM_EMAIL=your_verified_email@example.com
```

Run locally:

```bash
python app.py
```

Deploy to Render or Railway with environment variables.
