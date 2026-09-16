# Scam Alert

A small browser-based cybersecurity awareness project for identifying common scam warning signs in messages and call transcripts.

## Features

- Analyse pasted suspicious messages
- Rule-based scam risk indicator
- Detect verification-code requests
- Detect urgency and pressure
- Detect requests not to call/hang up
- Detect payment/transfer requests
- Detect credential requests
- Optional browser speech recognition
- Local-only pattern history with `localStorage`

## Run locally

### Option 1 — just open it

Double-click `index.html`.

### Option 2 — local web server with Python

```powershell
python -m http.server 8000
```

Then open:

`http://localhost:8000`

### Option 3 — VS Code Live Server

Install the **Live Server** extension, right-click `index.html`, then choose **Open with Live Server**.

## Git workflow

```powershell
git status
git add .
git commit -m "Build Scam Alert prototype"
git push
```

## Educational note

This prototype detects text patterns. It cannot prove that a sender/caller is malicious or automatically identify the real owner of a phone number or email.
