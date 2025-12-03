#  Filmagnet – Streaming Platform Landing Page

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)  
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)  
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)  

A modern, responsive streaming platform landing page built with **HTML, CSS, JavaScript, and Bootstrap 5**. Filmagnet showcases movies and TV shows with dynamic interactivity and visually engaging layouts, including a fully functional movie detail page.

---

##  Live Demo

[View Live Demo](#) *(replace `#` with your GitHub Pages or hosted link)*

---

##  Table of Contents

- [Features](#-features)  
- [Technologies Used](#-technologies-used)  
- [File Structure](#-file-structure)  
- [How It Works](#-how-it-works)  
- [Adding New Movies](#-adding-new-movies)  
- [Future Improvements](#-future-improvements)  
- [License](#-license)  

---

##  Features

- **Responsive Design**: Fully adaptable to desktop, tablet, and mobile devices using Bootstrap’s grid system.  
- **Hero Section**: Eye-catching hero background with gradient overlay and featured movie content.  
- **Dynamic Movie Cards**: Interactive movie cards with hover animations including scaling, brightness, and text movement.  
- **Movie Detail Page**: Dedicated pages dynamically populated with URL parameters (`title`, `img`, `summary`) and a “WATCH NOW” button linking to streaming sites.  
- **Modern Typography & Styling**: Google Fonts integration using **Antonio** for headings and **Inter** for body text.  
- **External Streaming Integration**: Each movie redirects users to its streaming site dynamically using JavaScript.  
- **Smooth Animations**: Hover effects for buttons and links, giving a polished user experience.  

---

##  Technologies Used

- **HTML5** – Semantic markup and structure  
- **CSS3** – Styling, animations, and responsive layouts  
- **JavaScript** – URL parameter parsing, dynamic content rendering, button interactivity  
- **Bootstrap 5** – Grid system, responsive navbar, buttons, and components  
- **Bootstrap Icons** – Vector icons for modern UI  
- **Google Fonts** – Antonio (headings) and Inter (body text)  

---

##  File Structure
/Filmagnet
│
├── index.html # Homepage with hero section & movie cards
├── movie.html # Dynamic movie detail page
├── style.css (optional)# Additional CSS if separated
├── Oppenheimer.jpeg # Hero image example
├── [Movie Images] # e.g., Inception.jpg, Dune2.jpg, etc.
└── README.md # Project documentation


---

##  How It Works

1. **Homepage (`index.html`)**
   - Displays a hero section and collection of movie cards.  
   - Each card has clickable links with query parameters: `title`, `img`, `summary`.  
   - Hovering triggers animations (scale, brightness, and text movement).

2. **Movie Detail Page (`movie.html`)**
   - Reads URL parameters using JavaScript (`URLSearchParams`).  
   - Populates movie title, poster, and summary dynamically.  
   - “WATCH NOW” button redirects to the streaming URL.

---

##  Adding New Movies

1. Add a new movie card to `index.html` with appropriate URL parameters.  
2. Add the streaming link for the new movie in the `switch` statement inside `movie.html`.  
3. Upload the corresponding image to your repository’s images folder.

---

##  Future Improvements

- Implement **search functionality** for easy movie discovery.  
- Add **filtering and sorting** by categories.  
- Integrate a **backend** and database for dynamic content.  
- Add **user authentication** for personalized watchlists.  
- Enhance accessibility with **ARIA labels** and keyboard navigation.

---

##  License

This project is **open-source** and free to use for personal projects or learning purposes.

---

Filmagnet is designed to demonstrate modern web design trends, interactive UI elements, and dynamic JavaScript functionality in a movie streaming context. Perfect as a portfolio project or a base template for future streaming platforms.

