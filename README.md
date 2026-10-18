# Zero to Robots — A Beginner Walkthrough

Live: https://adityapratap0077-cloud.github.io/physical-ai-roadmap/

A single-page, beginner-first walkthrough that takes someone with zero AI
knowledge from writing their first AI-assisted code to training robot policies.

## What makes it a walkthrough (not just a diagram)

- **6 ordered steps**, each with an honest time estimate
- **"First, the words"** — every new term explained in plain language before it is used
- **"Your moves"** — numbered, concrete actions: what to click, install, and type,
  including copy-paste code blocks (YOLO detection, ROS 2 talker/listener test)
- **"You are done when"** — checklists per step, saved in the browser
  (localStorage), with a live progress bar in the sticky header
- **Clickable step chips** + Prev/Next navigation between steps
- Every external link verified (Cursor, Google Colab, Teachable Machine,
  ROS 2 Jazzy docs, Google AI Studio, LeRobot install docs)

## The 6 steps

1. Write code by talking to AI (Cursor, ~1 hr)
2. Teach your computer to see (YOLO in Google Colab, ~2 hrs)
3. Train your own AI (Teachable Machine, no code, ~1 hr)
4. Learn robot software (ROS 2 + Gazebo simulation, a weekend)
5. Give AI a planning brain (Gemini API + plan-and-check loop, ~2 hrs)
6. Put AI on a robot (LeRobot PushT simulation, a weekend; real hardware optional)

## Files

- `walkthrough.html` — source of the page (published as `index.html`)
- `build.py` — regenerates `index.html` from the original upload (kept for history)
- `publish.py` — original publish helper (kept for history)

## Design

Same luminous design tokens as the original interactive roadmap
(deep-space background, cyan/violet/green glow accents, glassmorphism cards).
