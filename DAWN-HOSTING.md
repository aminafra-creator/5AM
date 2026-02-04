# Dawn — 5am Club PWA

## Deployment Guide

### Quick Deploy (Netlify Drop - 30 seconds)
1. Go to **app.netlify.com/drop**
2. Drag the entire `dawn-pwa` folder onto the page
3. Wait 30 seconds — get your URL!
4. Example: `https://dawn-5am-club.netlify.app`

### Files Included
```
dawn-pwa/
├── index.html          # Main app
├── dawn-manifest.json  # PWA configuration
├── dawn-sw.js          # Service worker (offline)
├── dawn-icon-192.png   # App icon (small)
├── dawn-icon-512.png   # App icon (large)
├── dawn-handout.html   # Printable clinic handout
└── DAWN-HOSTING.md     # This file
```

## The 15-Day Program

| Phase | Days | Wake Time | Shift |
|-------|------|-----------|-------|
| 1 | 1-3 | 8:00 AM | Start |
| 2 | 4-6 | 7:24 AM | -36 min |
| 3 | 7-9 | 6:48 AM | -36 min |
| 4 | 10-12 | 6:12 AM | -36 min |
| 5 | 13-15 | 5:36 AM | -36 min |
| **Goal** | **Day 15+** | **5:00 AM** | **-3 hours** |

## 9 Evidence-Based Habits

### Morning (Critical)
1. ☀️ **Morning Light** — Bright light within 30 min of waking
2. ⏰ **No Snooze** — Get up at first alarm
3. 🏃 **Exercise** — 15-30 min morning activity
4. 🍳 **Early Breakfast** — Eat within 1 hour of waking

### Afternoon
5. ☕ **No Late Caffeine** — No coffee after 2 PM

### Evening (Critical)
6. 🍽️ **Early Dinner** — Finish eating 3h before bed
7. 📱 **Screens Off** — No screens 1h before bed
8. 💡 **Dim Lights** — Dim all lights 90min before bed
9. ❄️ **Cool Room** — Bedroom at 18-20°C

## Features

- **Offline Support** — Works without internet after first load
- **Installable PWA** — Add to home screen on iOS/Android
- **Export Data** — WhatsApp, Email, CSV, JSON
- **Privacy First** — All data stays on device

## WhatsApp Distribution

Send this to patients:

```
☀️ Dawn — Join the 5am Club

Shift your wake time from 8:00 AM to 5:00 AM in 15 days!

Install: [YOUR_URL]

📱 iPhone: Open in Safari → Share → Add to Home Screen
📱 Android: Open → Tap "Install"

Track 9 daily habits. Complete 70% to advance.
```

## Clinic Handout

1. Open `dawn-handout.html` in your browser
2. Click "Print This Page" 
3. Add your QR code (from qr-code-generator.com)
4. Print on A4 paper

## Data Export Formats

| Format | Use Case |
|--------|----------|
| Text | WhatsApp/Email — readable summary |
| CSV | Excel/clinic EMR import |
| JSON | Full backup with all data |

## Technical Notes

- PWA with service worker for offline caching
- localStorage for data persistence
- No server required — 100% client-side
- Works on iOS 13+, Android 8+

---

Based on circadian rhythm research:
- Morning light is the #1 phase shifter
- 15-20 min gradual shifts every few days
- Consistency beats duration for health outcomes
