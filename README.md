# YouTube Mobile UI Redesign for Mindful Watching

This project redesigns YouTube’s mobile viewing experience to discourage compulsive binge-watching while preserving engagement and retention. By introducing subtle, non-intrusive interface elements like the **Session Time Blossom** and **Mindful Break Overlay**, the design promotes healthy viewing habits without disrupting the dopamine-driven flow of content consumption. Built as a Figma prototype, it leverages micro-interactions and visual cues to nudge users toward mindful breaks.

## Problem Statement

Redesign YouTube’s mobile viewing experience to discourage compulsive binge-watching—but in a way that doesn’t negatively affect engagement or retention. Your design should subtly influence user behavior through interface alone (no backend logic), preserving the dopamine-driven flow of content consumption:
- Micro-interactions to encourage breaks.
- Visual rhythm cues tied to watch patterns.
- Non-intrusive session/time reminders.
- Subconscious nudges embedded in the layout.

This prototype addresses these goals by introducing two key features: a blooming blossom icon that tracks session time and a mindful break overlay that suggests a 30-second stretch, both designed to fit seamlessly into YouTube’s aesthetic.

## Design Idea

The design focuses on two primary features to promote mindful watching:

1. **Session Time Blossom**:
   - A small, elegant icon in the video player’s top-right corner that blooms after 20 minutes of continuous watching.
   - Acts as a non-intrusive session reminder, using a flower-like visual to symbolize growth and time.
   - On tap, it displays a tooltip suggesting a quick stretch, empowering users to take action without forcing a break.
   - The blooming animation (over 5 minutes) serves as a subtle visual rhythm cue, encouraging users to notice their watch time subconsciously.

2. **Mindful Break Overlay**:
   - Triggered by tapping “Take a Break” in the blossom’s tooltip, this semi-transparent overlay suggests a 30-second stretch.
   - Features a pulsing card and a progress ring that fills during the pause, creating a calming micro-interaction.
   - Users can choose to “Continue Watching” (returning to the video) or “Pause for 30s” (engaging the break), ensuring control and flexibility.
   - The overlay’s design is subtle, preserving YouTube’s dark theme and engagement-driven flow.

These features align with YouTube’s brand and prioritize user agency, ensuring breaks are optional and non-disruptive.

## Design Approach

Key principles:
- **Subtlety**: The blossom and overlay are unobtrusive, appearing only when relevant (after 20 minutes or on user interaction).
- **Engagement Preservation**: Optional interactions (tap to view tooltip, choose to pause or continue) respect the user’s desire to keep watching.
- **Visual Cues**: The blooming blossom and pulsing overlay use animations to draw attention without overwhelming the viewer.
- **Accessibility**: High-contrast colors and screen reader labels ensure inclusivity.

The prototype includes three artboards:
1. **Video Player Screen**: Displays the video, progress bar, and Session Time Blossom (empty and filled states).
2. **Video Player with Tooltip**: Shows the blossom’s tooltip with a “Take a Break” button.
3. **Mindful Break Overlay**: Offers a stretch prompt with a progress ring and continue/pause options.

## Tools Used

- **Figma**: For designing and prototyping the mobile UI (iPhone 16 Pro Max frame, 440x956px).
- **Figma Contrast Plugin** : To verify accessibility of color choices.

## Figma Prototype Link

Explore the interactive prototype here:  
https://www.figma.com/design/9vRKEi9rqn2bGKupMzptXA/Aamish_YTNUM-1-?node-id=0-1&t=FttAV0fHh1V9ViHa-1

## Screenshots

Below are key screens from the prototype, showcasing the design and interactions. Screenshots are stored in the `/screenshots` folder of this repository.

1. **Video Player Screen (Blossom Empty)**  
   Displays the initial video player with the empty blossom icon.  
   ![image](https://github.com/user-attachments/assets/81cd3f92-a914-445d-8c6d-9fe3ab795791)


2. **Video Player with Tooltip**  
   Shows the tooltip triggered by tapping the blossom, suggesting a break.  
   ![image](https://github.com/user-attachments/assets/dc5ae4c5-c522-40c2-a0b8-5bba64d6a366)


3. **Mindful Break Overlay (Initial)**  
   The overlay with a stretch prompt and progress ring (empty state).  
   ![image](https://github.com/user-attachments/assets/79387e78-c93c-471b-b3c6-8efc1312125b)


4. **Mindful Break Overlay (Pause State)**  
   The overlay during a 30-second pause, with a filled progress ring and pulsing card.  
   ![image](https://github.com/user-attachments/assets/d40f5445-2c5b-4ddb-9c73-66f7c67a82e7)


## Why This Design Works

- **Health-Focused**: Encourages physical well-being by nudging users to stretch after prolonged watching, addressing binge-watching’s sedentary effects.
- **User Empowerment**: Optional interactions ensure users feel in control, preserving YouTube’s engagement-driven experience.
- **Brand Alignment**: Uses YouTube’s aesthetic for a cohesive, trustworthy look.
- **Creative Appeal**: The blooming blossom and pulsing overlay are visually engaging, showcasing creativity in a simple prototype.

## How to View the Prototype

1. Open the Figma link provided above.
2. Click the Play button (top-right) to interact with the prototype.
3. Flow: Tap the blossom → View tooltip → Tap “Take a Break” → See overlay → Choose “Pause for 30s” or “Continue Watching.”
4. Explore animations like the blooming blossom and pulsing overlay.
---
