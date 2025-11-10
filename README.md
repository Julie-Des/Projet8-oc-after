# Nina Carducci: SEO Optimization for a Photographer’s Website 📸

## 🎯 Project Objective

The objective of this project was to **improve the SEO, performance, and accessibility** of a photographer’s portfolio website.  

This project is part of the Web Integrator training course – OpenClassrooms.

---

## 🧠 Skills Developed

- **SEO Optimization** – Application of technical SEO strategies, structured data, and metadata for search engine visibility.  
- **Performance Enhancement** – Optimization of images, scripts, and CSS to achieve faster page loading times.  
- **Accessibility Improvement** – Implementation of accessibility standards (WCAG 2.1) and use of auditing tools.  
- **Semantic HTML & Code Quality** – Reorganization of HTML structure for better readability, maintainability, and accessibility.  
- **Tool-Based Analysis** – Use of **Google Lighthouse**, **Wave**, and **Color Contrast Analyser** to evaluate performance, SEO, and accessibility.  
- **Technical Documentation** – Creation of a detailed report summarizing technical improvements and measurable results.

---

## ⚙️ Technical Stack

- **Languages:** HTML5, CSS3, JavaScript  
- **Frameworks & Libraries:** Bootstrap  
- **Tools Used:**  
  - **Lighthouse** (performance and SEO audit)  
  - **Wave** (accessibility audit)  
  - **Squoosh** (image optimization)  
  - **Color Contrast Analyser** (contrast validation)  
  - **Google Rich Results Test** (Schema.org validation)  
- **SEO Standards:** Schema.org, Open Graph, Twitter Cards  
- **Technical performance:** Lazy loading, deferred script loading, minification, preloading fonts and CSS  

---

## 🚀 Optimizations Performed

### 🖼️ Image Optimization
- Conversion of all images to **WebP format**.  
- Creation of multiple image sizes with **`srcset`** and **`sizes`** attributes to ensure responsive loading.  
- Reduction of total image weight from **29.4 MB to 2.07 MB** (≈93% lighter).  
- Implementation of **lazy loading** for off-screen images.  
- Optimization carried out with **Squoosh**.

### ⚡ Head and Resource Loading
- Deferred loading of JavaScript files using the **`defer`** attribute.  
- Minification of CSS and JS files.  
- Use of **`preload`** for fonts and CSS to prioritize critical resources.  
- Reorganization of resource loading order for improved render time.

### 🧩 Semantic and Structural Improvements
- Added missing **`<title>`** and **`lang="fr"`** attributes.  
- Structured content with **`<header>`**, **`<main>`**, **`<footer>`**, and **`<nav>`** elements.  
- Ensured proper **heading hierarchy (H1 > H2 > H3)**.  
- Replaced or removed non-semantic tags for more accurate markup.

### 🏷️ Meta Tags and SEO
- Added essential **meta tags** (`description`, `robots`).  
- Improved **title** structure for relevance and local SEO.  
- Implemented **Open Graph** and **Twitter Card** metadata for better visibility on social media platforms.

### ♿ Accessibility Enhancements
- Added **alt descriptions** for all images.  
- Linked form labels with inputs using the **`for`** attribute and enabled **autocompletion**.  
- Corrected **contrast ratios** to meet **WCAG 2.1** standards.  
- Verified improvements with **Wave** and **Color Contrast Analyser**.

### 📍 Local SEO
- Added **city name (Bordeaux)** in the title and implemented **JSON-LD structured data** following **Schema.org**.  
- Validated structured data with **Google Rich Results Test**.  
- Provided recommendations for further SEO enhancement, including **Google Business Profile creation**, **local backlinks**, and **directory listings**.

### 📣 Social Media Metadata
- Integrated **Open Graph** tags for Facebook and LinkedIn.  
- Added **Twitter Cards** for optimal link previews on X (formerly Twitter).

---

## 📊 Results

- Significant improvement in **Lighthouse scores** (Performance, SEO, Accessibility).  
- All major **Wave accessibility errors** resolved.  
- Enhanced visibility and structure for **search engines and social platforms**.  
- Noticeable improvement in **loading speed** and **user experience**.

---

## 📦 Getting Started / Setup Instructions

### Prerequisites

*   A web browser (e.g., Chrome, Firefox, Safari)
*   A text editor or IDE (e.g., VS Code, Sublime Text, Atom)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Julie-Des/Projet8-oc-after
    ```

2.  Navigate to the project directory:

    ```bash
    cd Projet8-oc-after
    ```

**No specific installation steps are required.** The project consists of static HTML, CSS, and JavaScript files.

### Running Locally

**Open `index.html` in your web browser.**  You can do this by simply double-clicking the file or by right-clicking and selecting "Open with" followed by your browser.

## 🌍 Deployment

The project is deployed on GitHub:
https://julie-des.github.io/Projet8-oc-after/

## 📂 Project Structure

```
.
├── index.html
├── assets
│   ├── images
│   │   ├── gallery
│   │   │   ├── ... (Gallery images)
│   │   ├── photo.jpg
│   ├── maugallery.min.js
│   ├── scripts.js
│   └── style.min.css
└── README.md
```
## 📬 Contact

Deshayes Julie - julie.deshayes14@gmail.com

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💖 Thanks

This is partly written by [readme.ai](https://readme-generator-phi.vercel.app/) to help developers create beautiful documentation.
