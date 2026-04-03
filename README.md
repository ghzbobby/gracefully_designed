# Gracefully Designed — Website

A simple, single-page website for **Gracefully Designed**, an event decoration company specializing in balloon arches, custom designs, and full event styling.

## How the Website Works

The site is built as a single HTML file (`index.html`) with all styles written inline. No frameworks or build tools are needed — it runs directly in any browser.

The page is organized into these sections:

- **Header / Nav** — Logo and links that scroll to each section
- **Hero** — A short tagline introducing the business
- **Services** — Cards describing the three main offerings
- **Gallery** — A photo grid showcasing past work
- **Booking** — Where clients schedule their event
- **Footer** — Copyright info and contact

## Booking: Why Calendly

Scheduling for an event business involves a lot of back-and-forth — confirming availability, agreeing on a date, avoiding double-bookings. To eliminate that friction, the booking section uses **Calendly**.

Calendly lets the business owner set their own availability in advance. When a client visits the site, they see real open times and can book directly without any emails going back and forth. Both parties receive automatic confirmation. The free tier of Calendly supports unlimited bookings for one event type, which is sufficient for this use case.

## Adding / Replacing Gallery Photos

The site is hosted on [onecompiler.com](https://onecompiler.com), which only supports a single HTML file — local image files can't be uploaded. All images must use external URLs.

**How to add your own photos using Imgur:**
1. Go to [imgur.com](https://imgur.com) and upload your photo
2. Right-click the displayed image and select "Copy image address" — the URL will end in `.jpg` or `.png`
3. In `index.html`, find the `<img>` tag you want to replace and paste the Imgur URL into the `src` attribute

```html
<img src="https://i.imgur.com/XXXXXXX.jpg" alt="Your description">
```

Imgur is free and requires no account for basic uploads. Links are permanent and direct.

## Credits

- Scheduling powered by [Calendly](https://calendly.com) — free scheduling software
- Gallery photos from [Unsplash](https://unsplash.com) (placeholder images)
