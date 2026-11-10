# Drishtikon: AI Accessibility Assistant (Frontend)

## Problem statement

Visually impaired users depend on screen readers, which cannot describe images and are hard to use for quick tasks like summarising a block of text. They need an interface that works by voice and reads everything aloud.

## Solution

A voice-driven web interface built at a hackathon. Users upload an image or paste text, speak commands to control the app, and have the results read back to them, with the ability to copy or download them.

## Tech stack

Vue 3 (Composition API), Vite, Vue Router, Pinia, Tailwind CSS, Lucide icons, Web Speech API.

## Features

- **Voice commands**: say "upload", "summarize", "compare" or "commands", and the app responds
- **Spoken feedback**: speech synthesis reads back the interface and the results, with a clear message for unrecognised commands
- **Upload screen** with drag and drop for images, and a text box for pasted text
- **Result screen** with copy and download actions
- **Accessible design** with large, clearly labelled controls
- Routed pages for home, upload, results, settings and about

## Future steps

- Connect the upload and summarise actions to an AI backend for image description and text summaries
- More languages for voice input and speech output
- Settings for voice speed and volume
- Keyboard-only navigation and screen-reader testing

## Getting started

```bash
npm install
npm run dev
```

Use a Chromium-based browser for voice commands, since they rely on the Web Speech API.
