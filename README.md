# Stellar Gallery: Responsive Image Gallery

A responsive image gallery built using plain HTML, CSS (minimal), and vanilla JavaScript. This project features image categorization, a full-screen lightbox modal for viewing, and client-side CSS filter controls for image adjustment.

## 🌟 Features

* **Responsive Grid Layout:** The gallery adapts elegantly to various screen sizes using CSS Grid.
* **Category Filtering:** Easily filter images by predefined categories (**Nature, City, People, Abstract**).
* **Lightbox Modal:** Click any image to open a full-screen viewer.
* **Image Navigation:** Navigate between visible images using the "Previous" and "Next" buttons or the keyboard's arrow keys ($\leftarrow$ / $\rightarrow$).
* **Client-Side Image Filters:**
    * **Lightbox Adjustments:** Fine-tune the current image using range sliders for **Blur, Saturation, Brightness, Contrast**, and simulated **Grain**.
    * **Global Presets:** Apply quick, site-wide filter presets like **Black & White**, **Warm**, or **Cool** to all gallery thumbnails.
* **Accessibility:** Includes keyboard controls (Esc to close lightbox, arrow keys for navigation) and ARIA attributes.
* **Subtle Animations:** Features smooth hover effects and a subtle fade-in animation on page load.

## 🚀 Getting Started

This project is a single-file application, making deployment extremely simple.

### Prerequisites

You need a modern web browser to view the gallery.

### Installation

  **Open the file:** Simply open the `index.html` file in your preferred web browser.

Alternatively, since it's a single HTML file, you can copy the contents of `index.html` and use it directly on any web server or GitHub Pages.

## 💡 Usage

### Gallery Filtering

Use the control buttons at the top of the page to organize the view:

* Click **All** to show every image.
* Click **Nature**, **City**, **People**, or **Abstract** to filter the display.

### Lightbox Controls

When an image is opened in the lightbox:

1.  **Close:** Click the **✕** button, click outside the image frame, or press the **`Esc`** key.
2.  **Navigate:** Use the **◀** / **▶** buttons, or the **$\leftarrow$ / $\rightarrow$** arrow keys on your keyboard to move through the *currently visible* images.
3.  **Adjust Filters:** Use the range sliders in the right-hand panel to apply real-time CSS filters to the displayed image. Click **Reset** to return the image to its original state.

### Global Presets

Use the **"Filter style"** dropdown menu to apply a filter (e.g., Black & White) to *all* images in the main gallery view.

## 📂 Project Structure

The entire project is contained within a single file:└── index.html # Contains all HTML markup, CSS styles, and JavaScript logic.

## 🖼️ Customizing Images

The gallery uses placeholder images from `images.unsplash.com`. To add your own images:

1.  Locate the `<section class="gallery" id="gallery">` in `index.html`.
2.  Each image is defined by an `<article class="card">` block.
3.  Update the **`src`** attribute of the `<img>` tag with your image URL.
4.  Update the **`data-category`** (e.g., `"nature"`) and **`data-title`** (e.g., `"Misty Lake at Dawn"`) attributes to categorize and title your image correctly.
