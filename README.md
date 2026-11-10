# Kcal Ledger

A simple weekly calorie tracker. Log what you eat and burn each day, and see your calorie deficit and how much weight you can expect to lose by Sunday.

It's a single `index.html` file with no build step, no backend and no sign-up.

## Features

- **My week:** expected weight change by Sunday, a graph of the week, total and average deficit, and expected weight on Sunday.
- **Log a day:** pick Indian meals (chapati, dal, sabzi, rice, poha, idli, dosa and more) by tapping + or −, add any other food with your own calorie number, or type a total.
- **Burnt calories:** choose whether you log exercise only (your resting burn is added each day) or a total for the day from a watch or app.
- **Weight & settings:** record weigh-ins, see the change over time, and estimate your resting burn from weight, height, age and sex.

## How the numbers work

- Daily deficit = calories burnt (+ resting burn if you log exercise only) − calories eaten
- Expected change by Sunday = weekly deficit ÷ 7,700 kcal per kg. Days you haven't logged are assumed to match your average.
- Resting burn estimate = Mifflin-St Jeor BMR × 1.2

Food calories are typical home-cooked portions (1 katori ≈ 150 ml) and are only estimates.

## Run it

Open `index.html` in any browser.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `kcal-ledger`.
2. Upload `index.html`, `README.md` and `LICENSE` (**Add file → Upload files**), then commit.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two the app is live at `https://<your-username>.github.io/kcal-ledger/`.

## Your data

Everything is stored in your browser's local storage on that device. Nothing is sent to a server. Clearing your browser data, or opening the page in another browser or device, starts with an empty log.

## Disclaimer

This is a rough estimate tool, not medical advice. Real weight change also depends on water, sodium, hormones and how accurate your logging is.
