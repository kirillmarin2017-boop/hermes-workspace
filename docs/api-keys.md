# API Keys Setup

## Higgsfield API Keys
Used for AI video and image generation via Higgsfield (platform.higgsfield.ai).
- **Key ID:** `HIGGSFIELD_API_KEY_ID`
- **Key Secret:** `HIGGSFIELD_API_KEY_SECRET`
- Save to: `~/.config/hermes/.env`
- Also saved to Paperclip: `~/.paperclip/instances/default/env/higgsfield.env`

## ElevenLabs API Key
Used for audio transcription via ElevenLabs Scribe v1.
- Get your key from: https://elevenlabs.io/app/settings/api-keys
- Save to: `~/.config/hermes/.env` as `ELEVENLABS_API_KEY`
- Also saved to Paperclip: `~/.paperclip/instances/default/env/elevenlabs.env`

## Local Storage Locations
- `~/.config/hermes/.env` - Primary location for Hermes agent
- `~/.paperclip/instances/default/env/` - Paperclip agent environment files
- Never commit actual keys to GitHub - use `.env` files (ignored by git)
