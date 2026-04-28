GUI Sports Shop
A static e-commerce website for a sports and fitness shop, built with HTML, CSS, and vanilla JavaScript. Browse products across four categories, add items to a cart stored in localStorage, and complete a checkout with coupon support.


Features

Product catalogue across 4 categories, displayed in a responsive 3-column grid
Add to Cart — items are saved to localStorage and persist between pages
Cart page — displays all added items, quantities, and a running total (€)
Coupon code — enter kevin at checkout for a 30% discount
Checkout form — collects name, email, billing address (Eircode, street, town), and payment method
Payment options — Credit/Debit Card (with card number, CCV, expiry fields) or Apple Pay
Order confirmation popup — shows a randomly generated tracking number (e.g. GSS#83421) and total paid after submission
Clear Cart button to reset the cart at any time
Consistent navigation bar across all pages with hover effects
Deployed via GitHub Pages using the included GitHub Actions workflow


Getting Started
Run Locally
No build tools or dependencies required. Simply open index.html in your browser:
bash# Clone the repository
git clone https://github.com/your-username/GUI-ShopProject.git

# Open the homepage
open GUI-ShopProject-main/index.html
Deploy to GitHub Pages
This project includes a GitHub Actions workflow (.github/workflows/static.yml) that automatically deploys to GitHub Pages on every push to main.
To enable it:

Go to your repository Settings → Pages
Set the source to GitHub Actions
Push to main — the site will deploy automatically

 How the Cart Works
Items are stored in the browser's localStorage as a JSON array. Each item has a productName and price. The cart persists as you navigate between pages and is cleared after a successful checkout submission.

Technologies Used

HTML5
CSS3 (Flexbox, CSS Grid)
Vanilla JavaScript (localStorage API, DOM manipulation)
GitHub Actions (CI/CD for GitHub Pages deployment)


👥 Authors
Built by Cormac and Daniel as a GUI (Graphical User Interface) course project.
