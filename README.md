# Defender

## Project Summary

**Defender** is a fully functional, instant crypto payout platform utilizing blockchain for secure and rapid transactions.  
- Built with Flask (Python)
- Exports transaction history as CSV
- Manages terminals and users
- Admin and superadmin access controls
- Ready to deploy on [Render](https://render.com) — no code changes needed

## Getting Started

1. **Clone this repo or upload ZIP to GitHub.**
2. **On Render:**  
   - Create a new Web Service from this repo  
   - Set environment variables as shown in `.env.example`  
   - Render auto-detects `render.yaml` and deploys your Flask app
3. **Local Development:**  
   - Install Python 3.11+  
   - `pip install -r requirements.txt`  
   - `python app.py`

## Directory Structure

```
app.py
requirements.txt
render.yaml
Procfile (optional)
runtime.txt
wsgi.py (optional for WSGI)
static/
templates/
utils/
password.json
master.json
secret.json
```

## Security

- Do not commit your real secrets (`password.json`, `master.json`, `secret.json`) to public repositories.
- Set up secrets in Render's environment variables dashboard instead.

---
