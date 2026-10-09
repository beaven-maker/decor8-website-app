# DECOR8 Website & App

Premium website starter for **DECOR8 Curtains Blinds Shutter and Wallpaper (Pty) Ltd**.

## Features
- Responsive navy, gold and white branded landing page
- Product sections for curtains, blinds, shutters, wallpaper and motorised blinds
- Inspiration gallery and service information
- Room design brief generator with local photo preview (does not upload or analyse the image)
- Starter product advice assistant and floating chat panel
- Quote request form that prepares a copyable message
- Mobile responsive layout

## Deploy on Render
1. Sign in at https://render.com.
2. Choose **New + → Static Site**.
3. Connect GitHub and select `beaven-maker/decor8-website-app`.
4. Branch: `main`.
5. Build command: leave blank.
6. Publish directory: `.`
7. Click **Create Static Site**.

The site is a single static `index.html`, so no build command is required.

## Important before launch
- Add and verify DECOR8's official phone, WhatsApp, email and address; these are intentionally not invented.
- The AI assistant and room-design flow are currently demo experiences. To enable real conversational AI and image analysis/generation, add a secure backend and provider API key as a Render environment secret. Never put private API keys in browser JavaScript.
- Product images are remote Unsplash image URLs and need internet access.
- For native iOS/Android app-store releases, add a mobile wrapper or cross-platform app project and complete Apple/Google developer account setup. This website is responsive but is not itself a published native app.
