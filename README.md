# Captcha Image Display Tool

This is a simple, single-page web application designed to display a captcha image fetched from a URL provided as a query parameter. It serves as a client-side demonstration for viewing captcha images in a dedicated interface.

## Features

*   **URL Parameter Integration:** Dynamically loads a captcha image from the `?url=` query parameter.
*   **Responsive Design:** Built with Tailwind CSS for a clean and adaptable user experience across various device sizes.
*   **User-Friendly Interface:** Provides an input field for solving the captcha, along with clear instructions and feedback.
*   **Error Handling:** Informs the user if no URL is provided or if the image fails to load.

## How to Use

1.  **Save the file:** Save the provided `index.html` content as `index.html` on your local machine.
2.  **Open in Browser:** Open `index.html` using your web browser (e.g., `file:///path/to/your/index.html`).
3.  **Provide Captcha URL:** Append `?url=` followed by the URL of your captcha image to the browser's address bar and press Enter.

    **Example:**
    `file:///path/to/your/index.html?url=https://example.com/your-captcha-image.png`

    Replace `https://example.com/your-captcha-image.png` with the actual URL of the captcha image you wish to display.

4.  **Interact:** The captcha image will appear in the designated area. You can then use the input field to type what you see. Note that the "Submit Captcha" button and input field are for demonstration purposes only; this application does not perform server-side captcha validation.

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For all styling and responsive design.
*   **JavaScript:** For parsing URL parameters and dynamic image loading.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.