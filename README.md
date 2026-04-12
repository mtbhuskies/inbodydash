# InBody Tracker

Personal body composition tracker for InBody 270 (dietitian) scan results.

## Live app

**[Open InBody Tracker →](https://YOUR-USERNAME.github.io/inbody)**

## Setup

1. Fork or clone this repo
2. Go to **Settings → Pages → Source: main branch / root**
3. Open your Pages URL and go to ⚙️ Settings in the app
4. Enter your GitHub personal access token (needs `gist` scope only)
5. Leave Gist ID blank and tap Connect — it creates one automatically
6. Bookmark the URL and use it on any device

## How data is stored

Scan data is stored in a **private GitHub Gist** as `inbody_data.json`.  
The app reads and writes it directly via the GitHub API.  
Your token is stored in your browser's localStorage — it never leaves your device.

## Metrics tracked

Body composition · Muscle-Fat analysis · Body Fat % · BMI  
Body Fat 0 / Lean Body Mass Control · Research parameters (BMR, SMI)  
Segmental lean mass (arms, legs, trunk) with % scores
