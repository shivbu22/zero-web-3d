# Zero — Human Infrastructure to Get Hired (Clone)

A precise 1:1 clone of [why.zero.university](https://why.zero.university/).

## Included Assets & Features

- **Full WebGL / Three.js 3D Pipeline**:
  - Interactive stages & cameras (`camera_1.glb`, `camera_2.glb`)
  - 3D hands and interactions (`loader_hand.glb`, `human_hand_1.glb`, `human_hand_2.glb`, `fancy_hand_2.glb`)
  - Physics-driven glass shatter and tunnel effects (`stage2_glass-shatter.glb`, `tunnel_new_new.glb`, `glass_shards.glb`)
  - Complete collection of 10 3D origami models (`angelfish`, `cat`, `dog`, `dolphin`, `elephant`, `fox`, `goldfish`, `rhino`, `seal`, `wolf`) with high-resolution ambient occlusion maps
- **Decoders & Transcoders**:
  - Google Draco WASM & JS decoders (`/vendor/draco/`)
  - Basis Universal KTX2 transcoders & WASM (`/vendor/basis/`)
- **KTX2 Texture Atlases & WebP Textures**:
  - Board certificates, cloud layers, godrays, human hands, leather & money shreds, petals, world map
  - Matcaps, frost shaders, and custom background textures
- **Interactive Audio**:
  - Full ambient score (`amb_stage1.mp3`, `amb_stage2-3.mp3`, `amb_stage4-5.mp3`, `amb_stage5.mp3`)
  - Audio FX: drag, whoosh, glass shatter, tunnel, money burn, xp topup, click, hand entry
- **Video & Rich Media**:
  - Background loop videos (desktop & mobile)
  - Interactive company project cards with video reels (`Nike`, `OpenAI / ChatGPT`, `Google`, `Spotify`)
  - Star animations (480p / 720p)
- **Typography & Brand**:
  - Custom OTF fonts: *Supply Sans*, *PP Supply Mono*, *Bethany Elingston*, *STK Bureau Serif*
  - Brand vectors, favicons, open-graph cards, and UI cursors atlas

## How to Run

A lightweight server supporting HTTP Range requests (for video and audio streaming) and proper MIME types is included.

### Option 1: Using npm
```bash
npm start
```
or
```bash
npm run dev
```

### Option 2: Using Node directly
```bash
node server.js
```

Then navigate to:
```
http://localhost:3000/
```
