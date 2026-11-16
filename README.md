# knwp

A daily training tracker I built for my iPad. It runs my whole program in one place: a home routine, gym workouts, conditioning, nutrition, and a daily check-in.

It's one HTML file. No framework, no build step, no backend, no account.

**Live:** https://soaceace.github.io/knwp/training.html

## Why I built it

I wanted a structured plan to go from not working out to lifting regularly and eventually starting Muay Thai. Spreadsheets and paper logs didn't stick, so I made something that opens like an app, shows me exactly what to do today, and is quick to check off.

## Features

- **Today view** that builds the day automatically from a start date: home routine, the right gym session, nutrition, and check-in
- **Phased program** (Phase 1, Phase 2, Phase 3 for Muay Thai) with an upper body day and a leg day that alternate on their own
- **Move to tomorrow** button that pushes a missed session forward without breaking the A/B rotation
- **Weight logging** per exercise, with a "last time" reminder and a prompt to move up when I hit the top of the rep range
- **How buttons** on every exercise with short form cues, a backup option if a machine is taken or missing, and a link to video demos
- **All exercises view** that lists the full program by workout and phase
- **Nutrition and recovery tracking** for protein, water, and sleep
- **Daily check-in** with pain sliders and a weekly weigh-in
- **Week view and progress charts**
- Light and dark themes, large tap targets, works offline once loaded

## How it works

- Plain HTML, CSS, and JavaScript in a single file
- All data stays on the device in `localStorage`. Nothing gets sent anywhere, and no personal data lives in this repo
- Hosted on GitHub Pages and saved to the iPad Home Screen so it opens full screen like an app
- Tested in a headless browser (Playwright) across light/dark mode and portrait/landscape

## Run it yourself

1. Download `training.html`
2. Open it in any browser

To use it on an iPad, host it (GitHub Pages works), open the link in Safari, then tap **Share > Add to Home Screen**.

## How it was built

I designed the program and the features, and built the app with an AI coding assistant (Claude). I handled the requirements, testing on my iPad, and deployment.

## Notes

This is a personal tool, not medical or fitness advice.
