# 🛡️ Smart Change Detection in Surveillance Footage

This project demonstrates an intelligent way to analyze surveillance (CCTV) video by automatically detecting and extracting only the **interesting or meaningful events** — such as the appearance of people, vehicles, or other motion — while skipping the static, uneventful parts.

Instead of watching hours of video manually, this tool detects changes in the environment and filters out irrelevant frames, helping users focus only on what matters.

---

## 📌 What This Project Does

- Parses a surveillance video into individual frames
- Uses change detection techniques to identify motion or activity
- Detects objects (like people and vehicles) using computer vision models
- Keeps only the frames that show **relevant motion or events**
- Annotates frames with detected object labels
- Reduces video review time by **eliminating unchanging footage**

---

## 🎥 Example Use Case

Imagine you have a **500-frame CCTV video** monitoring your front door. Most of the video is uneventful, but:

- A person appears at frame 230
- A car enters at frame 370

This project will:
- Automatically detect those moments
- Filter out static frames
- Provide you with a reduced set of frames (e.g., 202 out of 500)
- Annotate them with object types (e.g., `"person"`, `"car"`)

---


