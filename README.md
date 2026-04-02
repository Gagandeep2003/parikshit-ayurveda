# 🌿 Shree Parikshit Ayurveda - Website

## Features
- Home, Services, Blog, Contact pages
- User Registration & Login
- Consultation Booking with time slot management
- No double-booking protection
- WhatsApp floating button
- Daily automated email with Excel report at 9 PM IST
- Dark Instagram-inspired UI theme

## Quick Start (Local)
```bash
pip install -r requirements.txt
python app.py
```
Visit: http://localhost:5000

## Deploy on Render.com (FREE)

1. Push code to GitHub
2. Go to https://render.com → New → Web Service
3. Connect your GitHub repo
4. Set environment variables:
   - `SMTP_EMAIL`: bharpur.spayur@gmail.com
   - `SMTP_PASSWORD`: Your Gmail App Password (see below)
   - `SECRET_KEY`: (auto-generated)
5. Deploy!

## Gmail App Password Setup (for daily emails)
1. Go to https://myaccount.google.com/security
2. Enable 2-Step Verification
3. Go to App Passwords
4. Create a new app password for "Mail"
5. Use this 16-character password as SMTP_PASSWORD

## Clinic Info
- **Hours**: Tue-Sun 10 AM - 8 PM | Monday: Closed
- **Phone**: +91 99909 78771
- **Address**: Plot 569, Sector 56, Gurugram
