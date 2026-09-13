# Smart Patrol Check-in System

A lightweight, responsive web application for security guard patrol check-ins with multi-location support, custom shift timings, and dynamic WhatsApp notification routing based on scheduled guard / supervisor phone numbers.

## Features

- 📍 **Multi-Location Support**: Configure multiple patrol locations (e.g. Main Gate, Back Gate, Warehouse).
- 📷 **QR Scanner Tag Support**: Open direct checkpoint pages via URL query (e.g. `index.html?loc=main-gate`).
- ⏰ **Dynamic Time Slot Matching**: Evaluates current system time against scheduled shift ranges (including overnight cross-midnight shifts like 22:00 to 06:00).
- 📱 **WhatsApp Message Routing**: Automatically routes check-in reports to the designated supervisor's WhatsApp mobile number for the active shift.
- ⚙️ **PIN-Protected Admin Settings**:
  - Add, edit, or delete locations and shift timings.
  - Alter supervisor names and mobile numbers.
  - Set fallback/emergency contact details.
  - Generate printable QR Code tags for physical checkpoints.
  - Export and Import system configuration JSON across devices.

## Usage

1. Open `index.html` in any web browser or via mobile scanner.
2. Select or scan a location checkpoint.
3. The app displays the active shift and designated supervisor for the current time.
4. Tap **PATROL DONE ✅** to send an auto-formatted WhatsApp report.

## Admin Access
- Tap the **⚙️ Gear Icon** in the top right header.
- Enter the Security PIN (Default: `1234`).
- Manage locations, shifts, phone numbers, or print scanner QR codes.