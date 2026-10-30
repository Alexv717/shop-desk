# Shop Desk

A free, phone-friendly web app for performance auto shops. One file (`index.html`): no build step, no server, no accounts.

**Live link:** _coming once GitHub Pages is on_

## Tabs

- **Reviews** – builds a Google review request text from the customer's name and vehicle. Copy, "Open in Messages", a "Mark as sent" log with a monthly count, and a printable counter QR code of the shop's review link.
- **Quotes** – parts $ and labor-hour lines, using the labor rate, tax %, what tax applies to, and deposit % from Setup. Makes a text the customer can reply YES to.
- **Checklists** – vehicle check-in, pre-dyno inspection, misfire diagnosis, "before the car goes home", student daily. Mark each item OK or Issue, then copy a summary.
- **Tuning calc** – fuel/injector sizing, injector flow at a new pressure, duty cycle and pulse width, HP from MAF, airflow needed, turbo pressure ratio, AFR/lambda/EQ, displacement and compression ratio.
- **Setup** – shop name, phone, Google review link, labor rate, tax, deposit. Backup/restore with a copyable code.

Direct links: `#reviews`, `#quotes`, `#checklists`, `#calc`, `#setup`.

## Your data stays on your phone

Everything you type is saved in that phone's browser (`localStorage`, keys starting with `shopdesk.`). Nothing is sent anywhere, and no shop or customer data is in this repo. To move settings to another phone, use Setup → Backup code.

## Add it to your home screen

- **iPhone:** open the link in Safari → Share → Add to Home Screen.
- **Android:** open the link in Chrome → ⋮ menu → Add to Home screen / Install app.

## Notes

- The tuning calculator gives planning numbers only. Final fuel and timing decisions come from the wideband, the knock data and an experienced tuner.
- The QR code uses qrcodejs 1.0.0 from cdnjs. Fonts are from Google Fonts.
