# Gracefully Designed — Project Notes

## Goal
A simple, clean website for **Gracefully Designed**, an event decoration company (balloon arches, custom designs, event styling). The site should let potential clients learn about services, view past work, and book events.

## Booking Integration
- Use **Calendly (free tier)** for scheduling
- Embed the Calendly widget or link in the booking section
- Replace or supplement the current mailto form with Calendly

## Hosting
- Site is hosted on **onecompiler.com** as a single `index.html` file
- No file uploads are supported, so all images must use external URLs

## Images
- Use **Imgur** to host photos: upload at imgur.com, right-click the image → "Copy image address" (ends in `.jpg` or `.png`), paste into the `src` attribute of the `<img>` tag
- Current gallery images are Unsplash placeholders — replace with real event photos via Imgur

## Current File
- `index.html` — single-page site (all HTML + CSS inline)

## Known Issues / To Fix
- CSS bug: `font-family: 'Britta',` is missing a closing quote and semicolon, breaking the font and background-color declarations
- Email typo on page: `Graceeefully.designed@gmail.com` — confirm correct spelling
- Mailto form is unreliable across browsers; replace with Calendly embed

## Pages / Sections
- Header + Nav
- Hero
- Services (Balloon Arches, Custom Designs, Event Styling)
- Gallery (photo grid)
- Booking (Calendly embed + contact info)
- Footer
