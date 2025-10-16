# Car Rental Website

A responsive car rental website built with HTML, CSS, and JavaScript. This project provides a seamless user experience for browsing, booking, and paying for car rentals. It features dynamic content, user authentication, and a QR code payment system.

## Features

-   **Responsive Design:** Fully responsive layout that works on all devices, from mobile phones to desktops.
-   **User Authentication:** Secure login and registration functionality using Firebase.
-   **Dynamic Car Listings:** Browse a variety of car models with detailed specifications.
-   **Search and Booking:** Easily search for available cars based on location and date, and book them through a simple form.
-   **Dynamic QR Code Payments:** Generate a unique UPI QR code for the calculated fare, including options for custom amounts.
-   **Interactive UI:** Smooth animations, tabbed content, and interactive elements to enhance the user experience.

## Technologies Used

-   **HTML5:** For the structure and content of the web pages.
-   **CSS3:** For styling, layout, and responsive design.
-   **JavaScript (ES6+):** For client-side logic, interactivity, and dynamic content.
-   **Firebase:** For user authentication and database management.
-   **QRCode.js:** For generating UPI QR codes dynamically.
-   **Remixicon:** For icons used throughout the website.
-   **Swiper.js:** For creating interactive carousels and sliders.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You need a modern web browser and a local web server to run this project. You can use the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for VS Code for a simple setup.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/Hemant-Shashikant-Yadav/Car_Rental.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd Car_Rental_12-11-24-main
    ```
3.  **Open `index.html` in your browser:**
    -   If you are using the Live Server extension in VS Code, right-click on `index.html` and select "Open with Live Server."
    -   Otherwise, you can open the `index.html` file directly in your browser.

## File Structure

```
.
├── assets/             # Images and logos
├── css/                # CSS stylesheets
│   ├── styles.css      # Main stylesheet
│   └── lstyle.css      # Login/Register page styles
├── js/                 # JavaScript files
│   ├── app.js          # Main application logic
│   └── modules/        # Modular JavaScript components
├── index.html          # Homepage
├── login.html          # Login page
├── register.html       # Registration page
├── qr.html             # Payment and booking page
└── README.md           # Project documentation
```

## Key Functionalities

-   **Homepage (`index.html`):** Displays car rental deals, company information, and a search form to initiate the booking process.
-   **Authentication (`login.html`, `register.html`):** Allows users to create an account or log in.
-   **Booking and Payment (`qr.html`):**
    -   Prefills booking details from the homepage search.
    -   Calculates the total fare based on distance and car model.
    -   Generates a dynamic UPI QR code for payment.
    -   Includes a feature to generate a QR code for a custom amount.
-   **JavaScript Modules (`js/modules/`):**
    -   `auth.js`: Handles Firebase authentication.
    -   `navigation.js`: Manages navigation and menu interactions.
    -   `tabs.js`: Controls the tabbed interface for car deals.
    -   And more for specific functionalities.

<YOUR_UPI_ID> need to change in line 1345 in qr.html