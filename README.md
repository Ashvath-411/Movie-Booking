# Movie Ticket Booking System

A responsive, multi-page frontend application designed to handle the end-to-end user journey of a cinema reservation system. This project demonstrates modular frontend architecture and client-side state management using vanilla JavaScript.

[**Live Demo**](https://ashvath-411.github.io/Movie-Booking/)

## Technical Implementation

*   **State Management:** Utilizes the Web Storage API (`sessionStorage`) to maintain booking data (movie title, seat count, price) across the four-stage user flow.
*   **Theme Persistence:** Implements `localStorage` to store user theme preferences (Dark/Light mode), ensuring a consistent UI experience across browser sessions.
*   **Data Passing:** Leverages `URLSearchParams` to pass context-specific data, such as Movie IDs, between the catalog and the reservation interface.
*   **Responsive Architecture:** Built with a Mobile-First approach using the Bootstrap 5 grid system and custom CSS3 media queries.
*   **Client-Side Validation:** Includes JavaScript-based form validation for seat selection and payment inputs to ensure data integrity before final confirmation.

## Project Structure

*   `index.html`: Entry point featuring a responsive movie catalog and featured content carousel.
*   `booking.html`: Context-aware reservation page that retrieves movie metadata via URL parameters.
*   `payment.html`: Dynamic payment interface supporting multiple transaction methods (Card, UPI, Net Banking).
*   `payment_success.html`: Terminal page that parses session data to generate a booking confirmation summary.

## Core Technologies

*   **Languages:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+)
*   **Frameworks:** Bootstrap 5
*   **APIs:** Web Storage API (sessionStorage/localStorage), URLSearchParams API
*   **Deployment:** GitHub Pages

## Developer Features

*   Asynchronous-ready script structure to prevent DOM-blocking during page initialization.
*   Modular CSS with a focused color palette and consistent visual hierarchy.
*   Efficient asset management utilizing lazy loading for image components.
*   Semantic HTML5 markup for improved document structure and accessibility.
