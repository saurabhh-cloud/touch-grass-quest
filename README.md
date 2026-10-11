# 🌿 Touch Grass Quest

An AI adventure planner that gets you off the screen. Tell it where you are and how much time you have. It plans a short walk with a route, things to look for and a checklist, lets you record notes and photos, and writes your **Adventure Journal** afterwards.

The AI is an open-weight model (Google's **Gemma 2 2B** by default) running **inside your browser** with [WebLLM](https://github.com/mlc-ai/web-llm) and WebGPU. No server, no API key, no account. Your location and notes stay on your device.

## How it works
1. **Tell it about your adventure:** place, landmarks you know, time, energy, weather, interests.
2. **Get a plan:** activity ideas, a route using only landmarks you named, things to look for, and a checklist.
3. **Download the offline card:** a small HTML file with your plan, checklist and a notes box. Open it on your phone. It works with no internet.
4. **Record notes and photos** while you walk.
5. **Write your Adventure Journal:** the AI uses only your own notes and ticked items. A built-in word check **highlights any word that is not in your notes**, so you can edit or delete anything the AI may have made up. Download it with your photos.

## Use it
Open the live link on a laptop or desktop with Chrome or Edge (needs WebGPU). Click **Load the AI** (one-time download, then cached). No GPU or phone? Click **Try a sample plan (no AI)**.

## Tech
WebLLM + Gemma 2 2B (Qwen 2.5 and Llama 3.2 selectable) · plain HTML, CSS and JavaScript in a single file.

Built for the Hacktoberfest "Touch Grass" challenge on DEV.
