This project is a Book Rental Web App named "Chapter & Coffee" designed to allow users to browse and rent books online with a coffee-shop-like aesthetic. 
Here's a summary of its key features and structure:

1.Project Overview
Name: Chapter & Coffee
Type: Book Rental Website
Built with: HTML, CSS, JavaScript
Primary Functions: Book browsing, rental cart, checkout

2.Core Features
a)Book Listing
A collection of popular books across genres (e.g., The Silent Patient, Educated, Atomic Habits).
b)Each book card includes:
Cover image
Title, author, genre
Rental price
“Add to Cart” or “Out of Stock” button
c)🛒 Cart System
Sidebar cart (opens from the right) and a dedicated cart section on the page.
d)Features:
Add/remove items
Quantity updates
Cart summary: Subtotal, Tax (8%), Total
“Clear Cart” and “Checkout” buttons.

3.Aesthetic & UI
Cozy, bookstore-inspired UI with warm beige and brown color schemes.
Background image slider with bookstore/café themes.
Responsive layout (mobile-friendly)

4.Checkout Handling
On clicking “Proceed to Checkout,” cart data is saved to localStorage.
Redirects to checkout.html

5.Technologies Used
Tech	Role
HTML5	Structure and semantic layout
CSS3	Custom design with variables and media queries
JS	Dynamic DOM manipulation, cart logic, book data rendering
localStorage	Temporarily saves cart items for checkout

6.Extra UI Details
Book save button (currently decorative)
Book availability toggled by available: true/false. Cart icon with item count badge
Interactive messages for “item added to cart”
Stylish hover and transition effects
