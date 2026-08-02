# 🎓 Quality Education — SDG 4 Website

A group coursework website built for the University of Westminster's **Web Design and Development** module (2024/25). The site introduces **UN Sustainable Development Goal 4: Quality Education**, exploring why equitable access to education matters and how it drives social and economic progress.

This project was developed by a team of four students (Group 21, Subgroup D), with each member responsible for specific pages.

## 📖 About the Website

The site is a static multi-page website built with HTML and CSS (no frameworks), following a shared template, a single global stylesheet, and a consistent navigation bar.

### 🗂️ Pages

| Page | File | Assigned to |
|---|---|---|
| Splash Screen | `splash.html` | Student 1 |
| **Home Page** | `home.html` | **Student 2** |
| Volunteer | `volunteer.html` | Student 1 |
| **Table** | `table.html` | **Student 2** |
| User Profile | `profile.html` | Student 4 |
| Feedback | `feedback.html` | Student 3 |
| Sitemap | `sitemap.html` | Student 4 |
| Team | `team.html` | Student 3 |
| Content pages | `content_ST1.html` – `content_ST4.html` | All students |
| Validation pages | `validation_ST1.html` – `validation_ST4.html` | All students |

## 🌟 My Contribution — Student 2 (Hesandu Nethdula Dissanayake, w2120177)

As Student 2, I was responsible for the pages and shared infrastructure below.

### 1. 🎨 Global Stylesheet & Website Template (`CSS/styles.css`)

Since I was assigned the Website Style & Navigation role, I built the **global CSS file** that the rest of the team's pages depend on to keep the site visually consistent. It defines:

- **Typography** — Google Fonts (`Roboto`, `Outfit`, `Bellota Text`) for headings, body text, and buttons, plus a consistent heading/paragraph colour and size scale.
- **Colour palette** — a light blue/green theme (`#005ed8`, `#2baffc`, `#55c360`) used throughout the site for links, headings, and hover states.
- **Fixed header & navigation bar** — a sticky `hover-header` containing the site logo and a `nav-links` bar, with hover effects and an `.active` class to highlight the current page.
- **Footer template** — a shared multi-column footer (Website Links, Student Pages, Validation Pages, Content Pages) reused identically across every page in the site.
- **Reusable components** — `.container` for centring content, and `.card` / `.card-container` tile components (used for the Home page's content links, with hover lift and shadow effects).

### 2. 🏠 Home Page (`home.html`)

The Home Page serves as the site's central hub. It includes:

- The website identity (logo + "Quality Education" branding) and mission statement, introducing the site's focus on SDG 4.
- A hero section pairing an image with an introductory heading.
- An embedded YouTube video adding further context on the importance of education.
- A **card-based gallery** linking out to all four student content pages (`content_ST1.html`–`content_ST4.html`), each with an image, title, and "See More" link, styled with hover animations.
- The shared header, navigation bar, and footer built from the global stylesheet.

### 3. 📊 Table Page (`table.html`)

An interactive data table titled *"Key Educational Statistics by Country,"* comparing literacy rate, teacher-student ratio, digital learning access, and government education spending across countries (World, Sri Lanka, UK, USA, India, Japan, Guinea, South Sudan, Chad, Ethiopia). Key features include:

- Flag/globe icons per row using the emoji-css library, tying each row to its country.
- Colour-coded cells (`positive` / `info` / `negative` classes) to make strong vs. weak performance easy to scan at a glance.
- Styling (borders, alternating colours, hover effects) defined in `CSS/table.css`, layered on top of the shared global styles.

### 4. 📝 Content Page (`content_ST2.html`)

An individual long-form content page on the theme of quality education, following the site's shared header/footer/navigation structure and styled with `CSS/content_2.css`.

### 5. ✅ Validation Page (`validation_ST2.html`)

Evidence that the Home, Table, and Content_ST2 pages pass markup validation, checked using the **[W3C Markup Validation Service](https://validator.w3.org/)**. The page includes screenshots of the validation results for each page, with a short reflection on any warnings/errors encountered and how they were resolved.

## ▶️ How to Run

This is a static HTML/CSS site, so no build tools, servers, or dependencies are required — you just need a browser.

1. 📥 Clone or [download the repo](https://github.com/Hesanduu/Quality-Education_Web) as a ZIP and extract it.
2. 📂 Open the project folder.
3. 🖱️ Double-click `splash.html` (or `home.html`) to open it in your default browser (Google Chrome Preferred). 

Start at `splash.html` to see the intended entry point (it auto-redirects to `home.html` after a few seconds), or jump straight to `home.html` to explore the site via the navigation bar.

## 🛠️ Tech Stack

- **HTML5** — semantic structure across all pages
- **CSS3** — a shared global stylesheet plus page-specific stylesheets per section

Also Used *Google Fonts* and an emoji/flag icon library for visual polish

## 📁 Project Structure

```
├── CSS/                 # Global stylesheet (styles.css) + per-page stylesheets
├── img/                 # Images, organised by page
├── home.html             # Home Page (Student 2)
├── table.html             # Table Page (Student 2)
├── content_ST2.html       # Content Page (Student 2)
├── validation_ST*.html    # W3C validation evidence (Student 2)
├── splash.html, volunteer.html, profile.html, feedback.html,
│   sitemap.html, team.html, content_ST1/3/4.html, 
└── validation_ST1/3/4.html
```
## 👥 Contributors

Group 21, Subgroup D — 4-person team, each owning specific pages while collaborating on shared design decisions.

| 👤 Name | 🎯 Role | 🖥️ Pages Implemented |
|---|---|---|
| Tharusha Nimnath | Student 1 | Splash Screen, Volunteer, Content Page 1 |
| **Hesandu Nethdula Dissanayake (Leader)** | **Student 2** | **Website Style & Navigation (Global CSS), Home Page, Table, Content Page 2** |
| Punsith Wickramanayaka | Student 3 | Feedback, Team, Content Page 3 |
| Sandes Damunugalla | Student 4 | User Profile, Sitemap, Content Page 4 |

📌 All four members also individually completed: their Content page and Validation page, and collaborated on the site's overall look, feel, and content direction.
