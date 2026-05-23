# Bank-Chan 🤑

AI-powered Banker experience. Users describe a vibe, meme, or crypto scenario and get back a custom Bank-Chan response with personality, visuals, and content generation.

## Files

- `index.html` — the website frontend
- `api/generate.js` — the backend that calls AI generation APIs
- `vercel.json` — Vercel configuration

## Deploy to Vercel

1. Upload this folder to a GitHub repository
2. Import the repo on vercel.com
3. Add these environment variables in Vercel project settings:
   - `OPENAI_API_KEY` = your OpenAI API key (sk-...)
   - `REPLICATE_API_TOKEN` = your Replicate API token (r8_...)
4. Deploy!

## How it works

1. User enters a prompt about Bank-Chan
2. The AI generates a themed response, dialogue, or content
3. Optional image/audio generation APIs create media assets
4. The final result is displayed directly on the page

## Features

- AI-generated Bank-Chan personality responses
- Crypto meme and branding generation
- Fast serverless deployment with Vercel
- Customizable prompts and themes
- Simple frontend + API architecture

## Tech Stack

- HTML / JavaScript
- Vercel Serverless Functions
- OpenAI API
- Replicate API

## License

MIT
