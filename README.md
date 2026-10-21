# Dr. Pawar's Hariruddha Polyclinic — WhatsApp Automation Demo

Interactive, mobile-first client demo prototype customized for **Dr. Pawar's Hariruddha Polyclinic**.

## What This Demo Demonstrates
1. **Instant WhatsApp Booking (30-second flow):**
   - Patient opens WhatsApp, chooses consultant (Dr. Pawar, Pediatric, Checkup).
   - Selects slot (Morning / Evening).
   - Receives instant confirmed token ticket with clinic Google Maps location pin.
2. **Automated 2-Hour Visit Reminder:**
   - Simulated push notification and WhatsApp reminder message to eliminate patient no-shows.
3. **Clinic Reception & Doctor Queue Portal:**
   - Toggle switch in top bar lets the doctor see where booked tokens immediately appear without any manual phone-calling or paper registers.

---

## How to Deploy in 60 Seconds (Free & Instant)

### Option A: Drag & Drop on Netlify (Fastest - No Terminal Needed)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag and drop this folder (`cliet-demo`).
3. You immediately get a live `https://[random-name].netlify.app` link. You can rename the domain to `dr-pawar-clinic-preview.netlify.app`.

### Option B: Deploy via Vercel CLI
```bash
npx vercel deploy --prod
```

### Option C: GitHub Pages
1. Push `index.html` and `preview.png` to a GitHub repository.
2. In Repository **Settings > Pages**, set Branch to `main` and Folder to `/ (root)`.
3. Your link will be `https://<username>.github.io/<repo-name>`.

---

## WhatsApp Message to Send to the Doctor

Copy and paste this message directly on WhatsApp:

```text
Good day Dr. Pawar,

Here is the quick interactive preview we prepared for Dr. Pawar's Hariruddha Polyclinic:

👉 [YOUR_LIVE_DEMO_LINK]

In 30 seconds, you can see:
1. How a patient books a slot & gets a token automatically on WhatsApp
2. The automated 2-hour reminder alert that prevents no-shows
3. The live reception queue view that saves staff hours of manual calling

Tap the link on your phone to test it. Looking forward to your thoughts!
```
