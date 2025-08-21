# Slicer Privacy Policy
_Last updated: 21 Aug 2025_

Slicer never sells your data and shows no ads. We keep data to the minimum needed for the app to work.

## What the app stores (on your device)
Stored locally using secure storage:
- **Apple Music tokens**: a short-lived developer token and your MusicKit **music user token** (lets the app access your library & play music on your device).
- **Daily cleanup counter** (to enforce the free-tier limit).
- **Theme preference** (light/dark).
- **In-app purchase flags (iOS)**: whether you’re Pro (lifetime or subscription) so features unlock on this device.
- Small UX prefs (e.g., whether you’ve seen onboarding; hidden playlist IDs in the Apple list).

We do **not** run a user database for Slicer.  
We do **not** upload your Apple Music library, playlists, or listening history to our servers.

## Data we read from Apple Music
To show and clean your playlists we read, via Apple’s APIs:
- Your **library playlists** and their **tracks**.
- Your **authorization/subscription status** (to enable playback and create a cleaned playlist).

This data is used in-app and **not** persisted to Slicer servers.

## Third-party services we use
- **Apple MusicKit JS & Apple Music API** — authentication, library access, playback.
- **Apple StoreKit (iOS)** — in-app purchases and restorations.
- **Stripe + Supabase** — payments/portal on non-iOS platforms (if applicable).
- **Vercel** — hosts a tiny endpoint that mints the Apple developer token. It returns a signed token; it does **not** store your library data.

> **Spotify** — *Coming soon.* Spotify integrations are paused while we work toward the required quota.

## Analytics & tracking
None. We do not include analytics SDKs or third-party advertising.

## Security & retention
- App data is stored **locally** on your device. Deleting the app removes this data.  
- Support emails you send us are kept only as long as needed to help; you can request deletion at any time.

## Your choices
- **Delete local data:** delete the app.
- **Restore purchases:** Settings → **Restore Purchases** (Slicer also auto-restores after sign-in).
- **Contact us:** **stafaa03@gmail.com**
