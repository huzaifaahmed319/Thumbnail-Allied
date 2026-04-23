# Allied Thumbnails — Pipeline

YouTube thumbnail + title generation pipeline for WWII military history content.

## What It Does

Paste or upload a script PDF → AI analyzes it → outputs:
- **4 video title options** following the channel formula
- **3–4 background type recommendations** (map, newspaper, document, battle)
- **4 banner word options** optimized for CTR
- **Full Nano Banana Pro prompt** ready to generate
- **One-click generation** via Google AI Studio API

## Setup

### API Keys Needed
1. **Anthropic API key** — for script analysis (Claude Sonnet) → [console.anthropic.com](https://console.anthropic.com)
2. **Google AI Studio key** — for image generation (Nano Banana Pro) → [aistudio.google.com](https://aistudio.google.com)

### Cost Per Script
- Analysis (Claude Sonnet): ~$0.03
- Image generation (Nano Banana Pro): ~$0.134 per image

## Deployment (Vercel)

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Import this repo
3. Deploy — no build step needed, it's a static HTML file
4. Access at your Vercel URL

## Updating

1. Make changes to `index.html`
2. GitHub Desktop → Commit → Push
3. Vercel auto-deploys in ~30 seconds

## Workflow

1. Paste script text or upload PDF
2. Enter API keys
3. Hit **Analyze Script**
4. Select: title → background → banner word
5. Upload 2–3 reference photos of the general
6. Hit **Generate Thumbnail**
7. Download PNG

## Background Types

| Type | Use When |
|------|----------|
| Collision Map | Two forces clashing, command conflicts |
| Location Map | Raids, campaigns, geographic stories |
| Newspaper | Cover-ups, political decisions, court martials |
| Document | Ignored orders, bureaucratic betrayal |
| Battle Action | Direct combat, last stands |
