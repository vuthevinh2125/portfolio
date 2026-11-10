# Changelog

A log of each round of changes to this portfolio, newest first. Each entry says what changed, why, and how it was checked.

## 2026-11-10 · NetSentinel on real traffic

- NetSentinel card: one feature now reports the evaluation on 28 real, labelled malware captures (14/18 infected host-days caught, 2.2 false alerts a day, the IPv6 bug real data exposed), and one result tile shows 14/18. Added Zeek to the stack.

## 2026-11-10 · NetSentinel project

- New project card for **NetSentinel**, an AI-assisted mini SOC: screenshot of the SOC console, three layers (lab network, detection, AI analyst), six features, results (7/7 attacks, 0.4 false alerts/day, 10/10 AI verdicts, 16 tests), stack, and links to the live demo and source.
- Fully bilingual through `data-vi`.
- Checked on desktop and phone width: no sideways scroll, no console errors.

## 2026-11-10 · Share preview, favicon, changelog

- **Share cover image** (`images/og-cover.jpg`, 1200×630): the red PORTFOLIO title, the portrait cutout and the name, so a link pasted into Facebook, LinkedIn or Zalo shows a proper preview card.
- **Meta tags**: `og:image` now uses the full URL (social sites ignore relative paths), plus `og:url`, `og:site_name`, image size and alt text, `twitter:card`, `canonical`, `author`, `keywords`, `robots` and `theme-color`.
- **Favicon**: a small red "V" in SVG (`images/favicon.svg`).
- **This changelog.**

## 2026-11-10 · Project screenshots

- VietUrban (store level 10, day 5) and Giza (North–South cross-section) screenshots, each in an app-window frame with a bilingual caption.
- Click a screenshot to open it full size; close with the button, Esc or a click outside.
- The auto demo builds the screenshot frames and pauses on each one.
- Checked on desktop and phone width: no sideways scroll, no console errors.

## 2026-11-10 · VIE / ENG

- Every visible string has a Vietnamese version stored in a `data-vi` attribute; the switch swaps the text without touching layout or animation.
- The choice is remembered per visitor; browsers set to Vietnamese open in Vietnamese; `#vi` or `#en` at the end of the link forces a language.
- Buttons, the demo hint and the tab title follow the language too.

## 2026-11-06 · Skills from new projects

- Skills regrouped into Languages, AI engineering, 3D/graphics/games, Data & cloud, Infrastructure & DevOps, Working with people.
- Added GLSL, Claude tool use, agent evals, three.js, stencil-buffer rendering, Unity URP, Cloudflare Workers, Monte Carlo simulation.

## 2026-11-05 · Giza 3D project

- New project card for the Great Pyramid of Giza model (three.js, 22,994 instanced stones, muon simulation, Claude tool-use guide, 20-case agent eval).

## 2026-11-04 · Redesign

- New dark/red single-page site: cutout portrait in front of a giant PORTFOLIO title, network-packet canvas, traceroute-style experience timeline.
- VietUrban Supermarket Simulator added with figures from the final report (+61% FPS, 38/38 tests, 23 root-cause fixes).
- Auto demo: four agent cursors drag out frames and build the page section by section, then a cursor tours it; the intro builds slower so the GPA and workplace can be read.
- Previous version moved to `v1/`.
