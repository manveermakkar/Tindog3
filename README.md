# 🐾 TinDog

> *Tinder, but for dogs.* — A fun, fully responsive landing page built while following a web development course.

---

## 📖 About This Project

TinDog is a fictional dog-matchmaking app landing page. It was built **side-by-side with a web development course** as a hands-on learning project — meaning every section, layout choice, and styling decision was coded along with the course material in real time. It serves as a practical demonstration of core front-end web development skills.

---

## ✨ Features

### 🧭 Navigation Bar
- Responsive navbar built with **Bootstrap 4**
- Collapses into a hamburger menu on smaller screens
- Smooth anchor links to **Contact**, **Pricing**, and **Download** sections

### 🦴 Hero / Title Section
- Bold headline with a custom **Roboto Mono** monotype font
- App store–style download buttons (Apple & Google Play)
- iPhone mockup image with a **CSS rotation transform** for a stylish tilt effect
- Responsive layout: image resets to static position on mobile

### ✅ Features Section
- Three-column icon grid highlighting app benefits:
  - **Easy to use** — Simple enough for your dog
  - **Elite Clientele** — The greatest dogs
  - **Guaranteed to work** — Find love or your money back
- Uses **Font Awesome 5** icons with hover color transitions

### 💬 Testimonials Carousel
- Bootstrap **carousel/slider** with two testimonial cards
- Dog and human profile images
- Previous/Next carousel controls
- Custom padding and font sizing for large, readable quotes

### 📰 Press Section
- Logos from fictional/real-world press outlets: TechCrunch, TNW, Business Insider, Mashable
- Consistent logo sizing and spacing

### 💰 Pricing Section
- Three-tier pricing cards:
  | Plan | Price | Highlights |
  |---|---|---|
  | **Chihuahua** | Free | 5 matches/day, 10 messages/day |
  | **Labrador** | $49/mo | Unlimited matches & messages |
  | **Mastiff** | $99/mo | Priority listing + unlimited everything |
- Bootstrap card components with outlined and filled button variants

### 📲 Call to Action (CTA)
- Bold CTA text encouraging downloads
- Apple and Google Play download buttons
- High-contrast colored section background

### 🔗 Footer
- Social media icons: Facebook, Twitter, Instagram, Email
- Copyright notice

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and semantic markup |
| **CSS3** | Custom styling, transforms, media queries |
| **Bootstrap 4** | Responsive grid, navbar, cards, carousel |
| **Font Awesome 5 Pro** | Icons throughout the page |
| **Google Fonts** | Montserrat, Ubuntu, Roboto Mono |
| **jQuery + Popper.js** | Bootstrap JS dependencies |

---

## 📱 Responsive Design

- Mobile-first approach using Bootstrap's grid system (`col-lg-*`, `col-md-*`)
- Custom media query at `1028px` to reset the title image position and center the hero section
- Navbar collapses to a toggler on small screens

---

## 🎨 Design Highlights

- **Color palette**: Coral/pink (`#ff4c68`) for colored sections, white for alternating sections
- **Typography**: Roboto Mono for the hero heading; Montserrat throughout; Ubuntu for the brand logo
- **Hover effects**: Feature icons shift from soft coral to vivid pink on hover
- **iPhone mockup**: Positioned and rotated with CSS for a dynamic feel

---

## 🚀 How to Run

No build tools needed — it's plain HTML/CSS.

1. Clone or download this repository
2. Make sure the folder structure includes:
   ```
   ├── index.html
   ├── css/
   │   └── styles.css
   └── images/
       ├── iphone6.png
       ├── dog-img.jpg
       ├── lady-img.jpg
       ├── TechCrunch.png
       ├── tnw.png
       ├── bizinsider.png
       └── mashable.png
   ```
3. Open `index.html` in any modern browser

---

## 📚 Course Context

This project was completed **alongside a web development course**, coding each feature in real time as part of the learning process. It covers foundational skills including:

- Structuring a multi-section landing page with semantic HTML
- Styling with custom CSS alongside a CSS framework (Bootstrap)
- Using a responsive grid system
- Integrating third-party libraries (fonts, icons, JS plugins)
- Building interactive components like navbars and carousels

---

## 📄 License

This project is for educational purposes. All brand logos used are property of their respective owners.
