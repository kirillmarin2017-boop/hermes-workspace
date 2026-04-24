# API Keys Setup

## ElevenLabs API Key
Used for audio transcription via ElevenLabs Scribe v1.
- Get your key from: https://elevenlabs.io/app/settings/api-keys
- Save to: `~/.config/hermes/.env` as `ELEVENLABS_API_KEY`
- Also saved to Paperclip: `~/.paperclip/instances/default/env/elevenlabs.env`

## Local Storage Locations
- `~/.config/hermes/.env` - Primary location for Hermes agent
- `~/.paperclip/instances/default/env/` - Paperclip agent environment files
- Never commit actual keys to GitHub - use `.env` files (ignored by git)
