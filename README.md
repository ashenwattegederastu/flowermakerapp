🌼 Flower Giver

Flower Giver is a simple and heartwarming web app that randomly shows you a flower 🌸 and an inspirational quote 💬. It supports English and Chinese language switching, with a soft pastel yellow theme designed for mobile-first responsiveness.

The project is built with HTML, CSS, and JavaScript only — no frameworks, no external dependencies.

✨ Features

🌻 Random flower images displayed from a local images/ folder.

💌 Inspirational quotes in English and Chinese.

🔄 Toggle language with one button (persists using localStorage).

🎲 Get a new flower + quote with a button (or by tapping the image).

📱 Fully responsive design for mobile devices.

🎨 Soft pastel yellow theme for a calming look and feel.

🚀 Getting Started

Clone or download this repository:

git clone https://github.com/yourusername/flower-giver.git
cd flower-giver


Make sure you have an images/ folder with the flower images listed above.
(You can replace them with your own flowers, just update the paths in index.html if needed.)

Open index.html in any modern browser:

open index.html   # macOS
start index.html  # Windows
xdg-open index.html  # Linux


That’s it 🎉 — no installation or server needed.

📱 Mobile Optimization

The app uses meta viewport and flexible CSS (clamp, percentages, media queries) for responsiveness.

Tap the flower image to shuffle flowers & quotes.

Works offline since images are stored locally.

🔧 Customization

Add more flowers: Drop new images in the images/ folder and add them to the flowers array in index.html.

Add more quotes: Add { en: "...", zh: "..." } objects to the quotes array.

Change theme: Update the CSS background: #fff9e6; and color variables.

📦 Future Plans

📲 Wrap into a Flutter app for Android & iOS (with bundled local assets).

🎨 Add more pastel themes (pink, lavender, mint).

💾 Save favorites to local storage.

🔔 Daily flower & quote notifications (in app form).

🖊️ Credits

Project Author: Ashen Wattegedera

Built with ❤️ and pure HTML, CSS & JavaScript

Flower images: Pexels
 (royalty-free)

🌼 You are the flower.
