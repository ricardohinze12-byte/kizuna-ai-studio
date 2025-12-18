# Kizuna AI Studio - Full AI Anime Production Suite

Kizuna AI Studio is a **complete AI-powered anime production platform** designed to allow creators to generate, edit, and compile full anime episodes entirely with AI assistance. It combines story generation, character design, animation, voice synthesis, music creation, and episode compilation into one integrated workflow.

## Features

- **AI Story Generation:** Automatically create anime episode outlines and dialogues.
- **Scene Directing:** Control camera angles, emotions, and scene cuts.
- **Character Design:** Generate unique characters with outfits, hairstyles, and expressions.
- **Animation & Preview:** Render scenes and view live previews with AI-generated thumbnails.
- **Voice & Music:** Assign AI-generated voices and background music per scene.
- **Drag & Drop Timeline:** Intuitive editor for sequencing scenes and scrubbing previews.
- **Auto Opening/Ending:** AI generates opening and ending sequences automatically.
- **Episode Compilation:** Compile all scenes into a complete anime episode.
- **Frontend + Backend:** Full stack integration using React for UI and FastAPI for backend services.
- **Local or Replit Ready:** Run entirely locally or deploy quickly on Replit.

## How It Works

1. **Add Scenes** – Create new scenes and drag them into the timeline.
2. **Assign Characters, Voice, and Music** – Use AI to generate all assets.
3. **Preview Live** – See scene previews and play voice/music instantly.
4. **Generate Opening/Ending** – Automatically add AI-generated sequences.
5. **Compile Episode** – Export the final episode video ready for publishing.

## Technology Stack

- **Backend:** Python, FastAPI (with fallback HTTP server if SSL is unavailable)
- **Frontend:** React, React Beautiful DnD, Axios
- **AI Integrations:** GPT for story/dialogue, text-to-speech for voices, Stable Diffusion or placeholder AI for animation thumbnails
- **Video Handling:** FFmpeg for episode compilation
- **Deployment:** Replit-ready with one-click run

## Use Cases

- Indie anime creators wanting rapid prototyping
- AI experimenters exploring generative media
- Education and learning tools for animation production

## Getting Started

1. Clone the repository.
2. Run the studio on **Replit** or locally:
   ```bash
   bash start.sh
