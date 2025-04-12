# ✨ Full-Screen Variable Dimension Card Slider ✨

This repository contains the HTML, CSS, and JavaScript code for a full-screen slider component. It's designed to display different "cards" (like course previews or content blocks), centering each one individually while allowing them to maintain their unique dimensions and aspect ratios. Navigation arrows are fixed to the screen edges for easy browsing.

This project was iteratively developed with AI assistance (based on user prompts and refinements) to demonstrate different card layouts and a specific slider behavior.

**(Optional: Add a Screenshot/GIF Here)**
![Screenshot of the Slider](placeholder-screenshot.png)
*Replace `placeholder-screenshot.png` with an actual screenshot or GIF of your slider in action.*

---

## Features

*   **Full-Screen Display:** The slider container occupies the entire browser viewport.
*   **Variable Card Dimensions:** Each slide (card) can have its own width and height, determined by its content or specific CSS rules.
*   **Centered Active Slide:** The currently active card is always centered horizontally and vertically within the viewport.
*   **Fade Transition:** Smooth fade-in/fade-out transition between slides.
*   **Fixed Navigation:** Previous/Next arrow buttons are fixed to the left and right edges of the screen.
*   **Keyboard Navigation:** Users can navigate using the left and right arrow keys.
*   **Responsive Constraints:** Cards have `max-width` and `max-height` set using viewport units (`vw`/`vh`) to prevent them from becoming excessively large on big screens.
*   **Multiple Card Layouts:** Demonstrates both standard vertical cards and a horizontal layout (Card 6).
*   **Dynamic Content Elements:** Includes examples of tags, overlays, ratings, status indicators, etc.
*   **Author Credit Overlay:** A fixed link/credit is displayed in the top-right corner.
*   **AI Creator Attribution:** Each card includes sample text indicating the AI model associated with its example content.
*   **Single File Implementation:** All HTML, CSS, and JavaScript are contained within a single `.html` file for simplicity.

---

## Technology Stack

*   **HTML5:** For the structure and content of the cards.
*   **CSS3:** For styling, layout (Flexbox, Absolute Positioning), transitions, and responsiveness.
*   **JavaScript (Vanilla):** For handling slide navigation logic, event listeners (clicks, keyboard), and toggling CSS classes.

---

## How to Use

1.  **Clone or Download:** Clone this repository or download the `index.html` file (or the final HTML file you saved).
    ```bash
    git clone <your-repo-url>
    ```
2.  **Open in Browser:** Navigate to the downloaded directory and open the `index.html` file directly in a modern web browser (like Chrome, Firefox, Edge, Safari).

That's it! The slider should be functional.

---

## Customization

*   **Card Content:** Modify the HTML content within each `<div class="slide card-X">...</div>` block to change text, details, buttons, etc.
*   **Images:** Replace the placeholder image URL (`https://images.pexels.com/...`) in each `.card-image` element with your desired images.
*   **Styling:** Adjust the CSS rules within the `<style>` tags in the `<head>` section. You can change:
    *   Colors (background, text, buttons, tags)
    *   Fonts
    *   Spacing and Padding
    *   Border radius and shadows
    *   Transition speeds (`transition` properties)
    *   Maximum/specific dimensions for cards (`max-width`, `max-height`, `.card-X` rules)
*   **AI Creator Names:** Update the text inside each `<div class="ai-creator-info">...</div>`.
*   **Author Credit:** Modify the link (`href`) and text within the `<div class="designer-credit">...</div>` element in the `<body>`.
*   **Slider Behavior:** Modify the JavaScript in the `<script>` block at the end of the `<body>`:
    *   Change transition logic (e.g., implement a sliding effect instead of fade).
    *   Enable looping by modifying the boundary checks in the `showSlide` function.
    *   Adjust event listeners or keyboard navigation.

---

## Credits

*   **Concept & Refinements:** Bolívar Alencastro ([bolivaralencastro.com.br](https://www.bolivaralencastro.com.br))
*   **Code Generation & Assistance:** Developed with assistance from AI models.
*   **Example Card Content Inspired By:** Claude, Mistral, DeepSeek, Grok, Gemini, ChatGPT.

---

## License

This project is open source and available under the [MIT License](LICENSE). (Consider adding a `LICENSE` file with the full MIT license text to your repository).