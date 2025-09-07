# Apple Vision Pro Homepage Clone

## Overview
This project is a front-end clone of the [Apple Vision Pro homepage](https://www.apple.com/apple-vision-pro/), built to replicate its visually stunning and interactive user interface. The webpage features smooth scrolling, scroll-triggered animations, and canvas-based image sequence animations, mimicking Apple's dynamic design. It showcases advanced front-end development skills, including responsive design, animation libraries, and the Canvas API, making it a strong portfolio piece for UI/UX-focused roles.

## Features
- **Smooth Scrolling**: Powered by [Locomotive Scroll](https://github.com/locomotivemtl/locomotive-scroll) for a seamless scrolling experience across 23 sections.
- **Scroll-Triggered Animations**: Utilizes [GSAP](https://greensock.com/gsap/) with [ScrollTrigger](https://greensock.com/scrolltrigger/) to animate elements like headings, videos, and images based on scroll position.
- **Canvas Animations**: Implements two canvas-based image sequence animations:
  - A 360-degree view of the Vision Pro with 198 images on `#page7`.
  - A smaller sequence with 25 images on `#page18`.
- **Responsive Design**: Uses `vw`/`vh` units and canvas resizing to ensure compatibility across devices, with CSS styling for centered layouts and full-screen media.
- **Apple-Like UI**: Replicates Apple's aesthetic with precise positioning, smooth transitions, and high-quality media (videos and images).

## Technologies Used
- **HTML5**: Structures the webpage with 23 sections, including videos, canvases, and interactive buttons.
- **CSS3**: Provides responsive styling with `flex`, `transform`, and `vw`/`vh` units for layouts and visual effects.
- **JavaScript (ES6)**: Powers interactivity and animations using:
  - **Locomotive Scroll**: For smooth scrolling.
  - **GSAP ScrollTrigger**: For scroll-based animations (e.g., pinning, fading, moving elements).
  - **Canvas API**: For rendering image sequence animations.
- **External Libraries**:
  - [Locomotive Scroll v3.5.4](https://cdn.jsdelivr.net/npm/locomotive-scroll@3.5.4)
  - [GSAP v3.12.1](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.1/gsap.min.js)
  - [ScrollTrigger v3.12.1](https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.1/ScrollTrigger.min.js)

## Project Structure

