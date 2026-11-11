# Kliniway

**Where should I go for care tonight?**

Kliniway helps people answer that one question fast. Given where you are and what's going on, it points you to the right kind of care: an emergency room, a walk-in clinic, a pharmacist, or virtual care. It shows what's open nearby right now, with wait times where they're published.

> **Kliniway is not medical advice.** It is a wayfinding tool that helps you choose between care options. If you think you are having a medical emergency, call your local emergency number (911 in Canada and the US) immediately.

---

## Why Kliniway exists

When something is wrong at 9 pm, most people face the same three problems:

1. **They don't know which kind of place to go to.** An ER is the default, but it's often the slowest and most expensive option for things a pharmacist or walk-in clinic could handle.
2. **They don't know what's actually open.** Hours on Google are frequently stale, and walk-in clinics often close intake well before their posted closing time.
3. **They don't know how long they'll wait.** Some health systems publish ER wait times, but the data lives on a dozen different sites.

Kliniway puts all of this in one place so the decision takes a minute, not an hour.

## What it does

- **Care-type guidance.** A short set of questions narrows the choice to ER, walk-in clinic, pharmacist, or virtual care.
- **What's open near you.** A list and map of nearby options filtered to what's open right now, including when intake closes.
- **Wait times where published.** Live or recently updated wait times for locations whose health system makes them public. Where no data exists, Kliniway says so rather than guessing.
- **Clear next step.** Directions, a phone number, or a link to start a virtual visit.

## What it does not do

- It does not diagnose conditions or recommend treatments.
- It does not replace a call to emergency services.
- It does not store your symptoms or location beyond what's needed to show you results.

---

## Status

Kliniway is in early development. This repository was created on 2026-11-11 and does not yet contain application code. The sections below are placeholders that will be filled in as the project takes shape.

## Getting started

<!-- TODO: fill in once the stack is chosen. Suggested shape: -->

```bash
git clone https://github.com/SaifOver9000/Kliniway.git
cd Kliniway
# install dependencies
# copy .env.example to .env and fill in API keys
# run the dev server
```

### Requirements

<!-- TODO: runtime version, package manager, any system dependencies. -->

### Environment variables

<!-- TODO: list each variable, what it's for, and whether it's required. For example:
| Variable | Required | Description |
|---|---|---|
| `MAPS_API_KEY` | yes | Map tiles and geocoding |
-->

## Project structure

<!-- TODO: one line per top-level folder once they exist. -->

## Data sources

Kliniway only shows wait times that a health system publishes openly. Each data source will be listed here with where it comes from, how often it refreshes, and what region it covers.

<!-- TODO: table of sources, e.g.
| Source | Region | Refresh | Notes |
|---|---|---|---|
-->

Hours and location data come from <!-- TODO: provider --> and are verified against <!-- TODO -->.

## Contributing

Contributions are welcome. Before opening a pull request:

1. Open an issue describing the change so we can agree on the approach.
2. Keep pull requests focused on one thing.
3. Add or update tests for anything that touches care-type guidance or wait-time parsing. These paths affect real decisions, so they need to be right.

If you are adding a new wait-time data source, include a link to the public page it reads from and a note on its terms of use.

## Safety and medical disclaimer

Kliniway provides general information about care options and is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of a qualified health provider with any questions you have about a medical condition. Never disregard professional medical advice or delay seeking it because of something you saw in Kliniway.

Wait times and opening hours are provided as-is from third-party sources and may be inaccurate or out of date.

## License

<!-- TODO: choose a license and add a LICENSE file. -->
