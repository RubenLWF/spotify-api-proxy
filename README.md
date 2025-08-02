# Spotify API Proxy

This is a serverless API proxy deployed on Vercel to handle Spotify API calls made from my personal website

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Set up environment variables in Vercel dashboard:
   - `SPOTIFY_CLIENT_ID`
   - `SPOTIFY_CLIENT_SECRET` 
   - `SPOTIFY_REFRESH_TOKEN`

## Endpoints

- `POST /api/token` - Get Spotify access token
- `GET /api/currently-playing` - Get currently playing track (requires Authorization header)

## Deploy to Vercel

1. Push this code to a GitHub repository
2. Connect the repository to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy!

## Local Development

```bash
npm run dev
```
