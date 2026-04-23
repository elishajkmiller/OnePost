# OnePost

A free, open-source video cross-posting tool that lets you publish to multiple 
social media platforms with a single click. No subscriptions, no servers, 
no cloud — just open the file in your browser and post.

**Built by Elisha Miller

## 🔴 Live Demo
[View it here](https://elishajkmiller.github.io/OnePost)

## Supported Platforms
- Bluesky
- Facebook (mirrors to Instagram automatically)
- Mastodon
- YouTube

## How to Use
1. Open the app in your browser
2. Enter your API credentials in the settings section (one-time setup)
3. Pick your video, write your caption, select your platforms
4. Hit the button — done

## Getting Your Credentials

**Bluesky** — Settings → App Passwords → Add App Password

**Facebook/Instagram** — Create a free app at developers.facebook.com, 
add the Pages product, generate a Page Access Token. Link your Instagram 
to your Facebook Page first (Instagram Settings → Linked Accounts)

**Mastodon** — Settings → Development → New Application → copy Access Token

**YouTube** — console.cloud.google.com → New Project → Enable YouTube Data 
API v3 → Create OAuth Client ID → add `null` as authorized JavaScript origin

## Running Locally
No install needed. Just download `index.html` and open it in any browser.

## License
MIT
