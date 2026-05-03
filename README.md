# 🗺️ Holidaymaker – India Travel Website
An interactive, map-based travel guide to explore every state and union territory of India. Built entirely with HTML and CSS, this project lets users register their travel interest, navigate an interactive map of India, and discover destinations, landmarks, and attractions for each region — all from the browser with no backend required.

✨ Features
🗺️ Clickable, interactive map of India with region-specific navigation
🏛️ Dedicated pages for all 28 states and 8 union territories
🖼️ Rich image gallery showcasing landmarks, wildlife, temples, beaches, and cultural sites
📋 User registration form with country selection and visit history
📱 Responsive design that adapts to mobile and desktop screens
🎨 Immersive full-page background with a consistent travel-themed aesthetic
🧑‍🎓 Great for students, educators, or anyone exploring India's geography and culture

📚 Use Cases
🔹 Browse and discover tourist attractions across every Indian state

🔹 Use as a reference for travel planning within India

🔹 Educational tool for learning Indian geography and cultural landmarks

🔹 Practice project for front-end web development with HTML, CSS, and image maps

🛠 Technologies
Languages: HTML5, CSS3

Layout & Navigation: HTML image maps (`<map>`, `<area>`)

Styling: Custom CSS with responsive media queries

Environment: Any modern browser — no server or build step needed

## 📁 Folder Structure
```
travel website/
│
├── travel.html               ← Entry point: user registration form
├── map.html                  ← Interactive map of India
├── TRAVEL.css                ← Shared stylesheet
│
├── andrapradesh.html
├── arunachalpradesh.html
├── assam.html
├── bihar.html
├── chandigarh.html
├── chattishgarh.html
├── dadarandnagarhaveli.html
├── damannddiu.html
├── deelhi.html
├── goa.html
├── gujarat.html
├── haryana.html
├── himachalpradesh.html
├── j&k.html
├── jharkhand.html
├── karnataka.html
├── kerala.html
├── ladakh.html
├── madhyapradesh.html
├── maharashtra.html
├── manipur.html
├── meghalaya.html
├── mizoram.html
├── nagalan.html
├── odisha.html
├── pondicherry.html
├── punjab.html
├── RAJASTHAN.html
├── skkim.html
├── tamilnadu.html
├── telangana.html
├── tripura.html
├── uttarakhand.html
├── uttarpradesh.html
├── westbengal.html
│
└── images/                   ← 300+ landmark and travel photos
```

## 🚀 How to Run

### 🖥️ Option 1: Open Directly in Browser (Recommended)
No installation or server needed. Simply:

1. Download or clone the repository
2. Open `travel.html` in any modern browser (Chrome, Firefox, Edge, Safari)
3. Fill in the registration form and click **Next** to explore the map
4. Click any region on the India map to visit its dedicated state page

### 🧩 Option 2: Run with a Local Server (Optional)
If you want to serve the project via a local server (e.g., to avoid any browser CORS restrictions on local files):

Using Python:
```bash
cd "travel website"
python -m http.server 8000
```
Then open `http://localhost:8000/travel.html` in your browser.

Using VS Code with the Live Server extension:
1. Open the project folder in VS Code
2. Right-click `travel.html` → **Open with Live Server**

### 📌 Requirements
- A modern web browser (Chrome, Firefox, Edge, or Safari)
- No frameworks, libraries, or build tools required
- All assets (images, CSS) are bundled locally — no internet connection needed after download

## 🗺️ Pages Overview

| Page | Description |
|---|---|
| `travel.html` | Registration form — entry point of the website |
| `map.html` | Interactive India map with clickable state regions |
| `[state].html` | Individual pages for each state/UT with attractions and images |

## 🖼️ Image Assets
All images are stored in the `images/` folder and include 300+ photographs covering: famous monuments and heritage sites, beaches and hill stations, national parks and wildlife sanctuaries, temples, lakes, valleys, and cultural festivals.

## 🔗 Contributing / Feedback
Found a bug or want to add a new state or attraction? Feel free to open an issue or submit a pull request!

## ❓ Frequently Asked Questions (FAQ)

**📌 Q1: Do I need a web server to run this project?**
A: No. All pages are plain HTML and CSS. Just double-click `travel.html` to open it in your browser. A local server is optional and only needed if you run into browser security restrictions with local files.

**📌 Q2: How does navigation between states work?**
A: The `map.html` page uses an HTML `<map>` element with `<area>` tags mapped to polygonal regions of the India map image. Clicking a region redirects to the corresponding state's HTML page.

**📌 Q3: Can I add more states or attractions?**
A: Yes! Each state has its own self-contained `.html` file. You can copy an existing state file, update the content and images, and add a new `<area>` entry in `map.html` to link it.

**📌 Q4: Why are some filenames inconsistent (e.g., `skkim.html`, `nagalan.html`)?**
A: These are minor typos in the original filenames. The links in `map.html` already point to the correct filenames, so navigation works as expected. Future contributions are welcome to standardise the naming.

**📌 Q5: Can I use this project on mobile?**
A: The registration form and individual state pages are responsive and work on mobile. The interactive map (`map.html`) uses pixel-based image coordinates, so it works best on desktop at its intended resolution.

## 🧑‍💻 Author
Kinjal Sethiya titipo08

## 📄 License
This project is licensed under the [MIT License](LICENSE).
