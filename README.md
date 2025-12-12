
# 🐧 Penguin Fashion ❄️

## 🧥 Stylish Winter Jackets Landing Page

This project is a clean, responsive landing page for a fictional fashion brand specializing in stylish winter jackets. It features a modern design, a clear product showcase for both men's and women's collections, and a prominent call-to-action (CTA) section.

## ✨ Features

  * **Hero Section:** A captivating main hero area with a unique headline and a strong "Buy Now" CTA button.
  * **Responsive Navigation:** A standard desktop navigation that collapses into a Font Awesome icon for mobile view.
  * **Product Showcase:** Dedicated sections for **Women's Jackets** and **Men's Jackets**, displaying three distinct products for each.
  * **Product Cards:** Clean, individual product cards featuring an image, title, description, price, and a "Buy Now" button.
  * **Value Proposition/Promo Section:** An attractive section highlighting key selling points (e.g., "Find the Perfect Fit") with engaging icons and hover effects.
  * **Modern Styling:** Utilizes Google Fonts (`Bebas Neue` for headings and `Roboto` for body text) and utility-first CSS for a professional look.

## 🛠️ Technologies Used

This project is built using standard web technologies with a focus on modern development tools:

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Structure** | `HTML5` | The core content and structure of the landing page. |
| **Styling** | `Tailwind CSS (@4)` | Utility-first CSS framework for rapid and responsive design. |
| **Custom Styling** | `CSS3` | Custom styling for font definition, button hover effects, and transitions. |
| **Typography** | `Google Fonts` | Used for the `Bebas Neue` (display) and `Roboto` (body) fonts. |
| **Icons** | `Font Awesome` | Used for the mobile menu icon and the shopping cart icon. |

## 🚀 Quick Start

To view this project locally, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/atonu-a/Penguin-Fashion]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd penguin-fashion
    ```
3.  **Open the HTML file:**
    Open the `index.html` file in your preferred web browser. Since the project uses the `@tailwindcss/browser@4` script, Tailwind CSS will be compiled directly in the browser, and no separate build step is needed.

## 🎨 Design and Styling Notes

  * **Color Palette:** The design utilizes a cozy, modern palette:
      * **Primary Accent (Text/Price):** `#FABE4C` (Orange/Yellow)
      * **Secondary Accent (CTA/Button):** A gradient from `#A4BC46` to `#85A019` (Green Tones)
      * **Headings/Main Text:** `#363958` and `#3c3c3c` (Dark Blue/Grey)
      * **Backgrounds:** `#FFFBF0` (Header) and `#3E5E5E5` (Body - light off-white)
  * **Hover Effect:** The custom CSS ensures that all primary buttons have a subtle, professional hover effect:
    ```css
    button:hover {
        border: 1px solid #000;
        opacity: 0.9;
        transition: all 0.3s ease-in-out; 
    }
