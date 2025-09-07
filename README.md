#Apple Vision Pro Homepage Clone
Overview
This project is a front-end clone of the Apple Vision Pro homepage, built to replicate its visually stunning and interactive user interface. The webpage features smooth scrolling, scroll-triggered animations, and canvas-based image sequence animations, mimicking Apple's dynamic design. It showcases advanced front-end development skills, including responsive design, animation libraries, and the Canvas API, making it a strong portfolio piece for UI/UX-focused roles.
Features

Smooth Scrolling: Powered by Locomotive Scroll for a seamless scrolling experience across 23 sections.
Scroll-Triggered Animations: Utilizes GSAP with ScrollTrigger to animate elements like headings, videos, and images based on scroll position.
Canvas Animations: Implements two canvas-based image sequence animations:
A 360-degree view of the Vision Pro with 198 images on #page7.
A smaller sequence with 25 images on #page18.


Responsive Design: Uses vw/vh units and canvas resizing to ensure compatibility across devices, with CSS styling for centered layouts and full-screen media.
Apple-Like UI: Replicates Apple's aesthetic with precise positioning, smooth transitions, and high-quality media (videos and images).

Technologies Used

HTML5: Structures the webpage with 23 sections, including videos, canvases, and interactive buttons.
CSS3: Provides responsive styling with flex, transform, and vw/vh units for layouts and visual effects.
JavaScript (ES6): Powers interactivity and animations using:
Locomotive Scroll: For smooth scrolling.
GSAP ScrollTrigger: For scroll-based animations (e.g., pinning, fading, moving elements).
Canvas API: For rendering image sequence animations.


External Libraries:
Locomotive Scroll v3.5.4
GSAP v3.12.1
ScrollTrigger v3.12.1



Project Structure
Apple-vision/
├── index.html        # Main HTML file with 23 sections
├── style.css         # CSS for responsive styling and layouts
├── script.js         # JavaScript for scrolling, animations, and canvas logic
├── Apple vision image.png  # Local image used in the project
└── README.md         # This file


Serve the Project:

Use a local server (e.g., Live Server in VS Code) or a tool like http-server:
npm install -g http-server
http-server


Open http://localhost:8080 in your browser.



Dependencies:

No installation is required, as all libraries (Locomotive Scroll, GSAP, ScrollTrigger) are loaded via CDNs in index.html.


Assets:

The project uses external Apple media (videos/images) and a local Apple vision image.png. Ensure internet access for external assets or replace with local equivalents.
For canvas animations, provide image sequences in the format vision_images/0001.webp to 0198.webp for #page7 and vision/0001.png to 0025.png for #page18 (not included in the repo due to size).



How It Works

Smooth Scrolling: script.js initializes Locomotive Scroll on the #main div, syncing with GSAP’s ScrollTrigger for precise animation triggers.
Animations:
Videos (e.g., #page>video) play when entering the viewport.
Sections (e.g., #page1, #page2) are pinned, with headings moving (e.g., top: -50%) or fading out.
Images (e.g., #page23>img) fade in on scroll.


Canvas Animations:
#page7 displays a 360-degree Vision Pro animation using 198 images, synced with scroll position.
#page18 shows a smaller sequence with 25 images.
Images are scaled responsively using the Canvas API’s drawImage and Math.min for aspect ratios.


Responsive Design: CSS uses vw/vh units, and JavaScript adjusts canvas sizes on window resize for cross-device compatibility.

Challenges Solved

Scroll Synchronization: Integrated Locomotive Scroll with GSAP ScrollTrigger using scrollerProxy to align scroll positions, handling mobile edge cases.
Canvas Scaling: Calculated aspect ratios (Math.min(hRatio, vRatio)) to ensure images fit responsively without distortion.
Animation Pacing: Tuned scrub and end values (e.g., 600% top for #page7) for smooth, Apple-like transitions.


Screenshots
(Add screenshots of key sections, e.g., #page with the hero video, #page7 canvas animation, etc., to visually showcase the project. You can generate these using browser dev tools or a screenshot tool.)
Live Demo
(Host the project on a platform like GitHub Pages or Vercel and add a link here, e.g., https://aadilkhan08.github.io/Apple-vision/. This requires setting up a live server and ensuring all assets are accessible.)
Acknowledgments

Inspired by the Apple Vision Pro homepage.
Thanks to Locomotive Scroll and GSAP for their powerful libraries.

License
This project is for educational purposes and not for commercial use, as it includes Apple’s media assets. Code is licensed under the MIT License.
Contact

