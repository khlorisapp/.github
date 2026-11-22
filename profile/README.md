# khloris 🌿

**A private indoor plant journal, 100% local.**

khloris is a native app to inventory, identify, and track your indoor plants —
no account, no cloud, no network. Everything stays on the device: photos, data,
adaptive reminders, and vacation mode.

> 🌐 Showcase: [khloris.app](https://khloris.app)

The **iPhone** version is under development; an **Android** version is planned.

## Founding principles

- **100% local by default**: data, photos, and notifications stay on the device
- **No mandatory account**: no sign-up, no imposed cloud sync
- **Local AI first**: on-device photo identification, offline
- **Check-in reminders**: "Check the Monstera's soil" rather than "Water now"
- **Rich metadata**: species, size, pot, material, substrate, room, exposure, history

## Features

- 📷 **Photograph your plants** and inventory them by room
- 🧠 **Identify them locally** (offline, abstains when uncertain)
- 💧 **Track watering** with adaptive reminders
- ✈️ **Vacation mode**: preparation list, shareable checklist
- 📄 **Share** the checklist via WhatsApp, Signal, AirDrop, Mail…
- 📅 **Calendar widget** (3 sizes) + "Identify a plant" widget
- 🌍 **7 languages**: French, English, German, Dutch, Italian, Spanish, Portuguese

## Stack

- **Language/UI**: Swift + SwiftUI (iOS) ; Dart + Flutter (Android)
- **Data**: SQLite local, photos on disk
- **AI**: Vision + Core ML, Apple Intelligence (when available)
- **Website hosting**: Cloudflare Workers (static, no trackers)

## Privacy

khloris collects no personal data. No account, no cloud, no tracker. Photos and
inventory stay on the user's device.

## Roadmap

- **iPhone**: current version under development (on-device testing, beta coming)
- **Android**: planned, after the iOS version stabilises
