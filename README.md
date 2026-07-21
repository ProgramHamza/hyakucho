# Project Hyakuchō — 百蝶

**Wearable Autonomous Butterfly Swarm Platform**

Project Hyakuchō is a futuristic design concept and cinematic experience blending high-fashion wearable tech with swarm robotics. It showcases a swarm of one hundred micro-drones housed inside an inductive docking harness (backpack) that reacts to human body gestures in real-time, forming dynamic kinetic shapes around the wearer.

## Project Structure

This project is structured for **Vercel** deployment with zero-configuration static hosting:

- `index.html`: The premium homescreen introducing the project, technical specifications, system architecture, conceptual description, and core features, with a smooth, lightweight sakura falling animation.
- `experience.html`: The 3D Three.js scroll-linked interactive cinematic reveal.
- `vercel.json`: Configuration to enable Vercel Clean URLs and rewrite `/experience` to point to `experience.html`.

---

## Deployment to Vercel

### Option 1: Deploy with GitHub & Vercel Dashboard (Recommended)

1. Create a new repository on your GitHub account.
2. Open your terminal in this project directory and push the code:
   ```bash
   git init
   git add .
   git commit -m "Initialize Project Hyakucho Vercel Deploy"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
3. Go to the [Vercel Dashboard](https://vercel.com/dashboard) and click **Add New > Project**.
4. Import your newly created repository and click **Deploy**. Vercel will automatically configure and publish your project!

### Option 2: Deploy using Vercel CLI

If you have Node.js and NPM installed, you can deploy directly from your command line:

1. Install the Vercel CLI globally:
   ```bash
   npm install -g vercel
   ```
2. Log in to Vercel:
   ```bash
   vercel login
   ```
3. Deploy the project:
   ```bash
   vercel
   ```
   *Follow the prompts, selecting the defaults to deploy instantly.*

---

## Features

- **Rich Aesthetics**: Responsive typography using Outfit and Noto Serif JP fonts.
- **Micro-Animations**: Hover-triggered translations, smooth visual borders, and performance-optimized canvas-like sakura petal drift.
- **Dynamic 3D Swarm**: Fully integrated Three.js swarm simulator with post-processing Unreal Bloom, custom film grain, lighting, and sound integration.
