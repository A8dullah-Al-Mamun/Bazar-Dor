# BazarDor(বাজার দর)

BazarDor is a responsive web application that helps users explore and compare the prices of essential products across different markets in Bangladesh. It provides daily price updates, product details, category-based browsing, and secure user authentication to make shopping easier and more convenient.

## Features

- **Daily Price Updates:** View products whose prices have increased or decreased.
- **Product Browsing:** Explore essential products with their names, prices, units, and price-change indicators.
- **Market Price Comparison:** View minimum, maximum, and average prices, along with market-based price information.
- **Category Filtering and Sorting:** Browse products by category and sort them by price from low to high or high to low.
- **Product Details:** View detailed information about individual products through dedicated detail pages.
- **Secure Authentication:** Sign up, sign in, and authenticate using email/password and supported social login providers.
- **Protected Routes:** Restrict access to product details and other protected pages to authenticated users.
- **Profile Management:** Update personal information through the user profile.
- **Responsive Design:** Enjoy a consistent experience across mobile, tablet, and desktop devices.
- **Loading and Notifications:** Display skeleton loaders and toast notifications for loading states, authentication, and errors.

## Technologies Used

- **Next.js:** Building the web application and user interface.
- **Next.js App Router:** Managing page navigation, layouts, and dynamic routes.
- **TypeScript:** Writing maintainable and type-safe code.
- **Tailwind CSS:** Creating responsive layouts and custom styling.
- **DaisyUI:** Building reusable UI components.
- **Better Auth:** Managing authentication, social login, and user accounts.
- **React Hot Toast:** Displaying success, error, and authentication notifications.
- **Programming Hero BazarDor API:** Fetching product, category, and market price data.

## API Endpoints

Base API URL: `https://openapi.programming-hero.com/api/bazardor`

Alternative API URLs:

- `https://api.api-store.workers.dev/api/bazardor`
- `https://api.abcz.workers.dev/api/bazardor`

| Endpoint | Description |
|---|---|
| `/products` | Fetch all products |
| `/products?category=chal` | Fetch products by category |
| `/products/1` | Fetch details of a specific product |
| `/categories` | Fetch all categories |
| `/categories/chal` | Fetch details of a specific category |

## Getting Started

### Prerequisites

Make sure you have Node.js, npm, and Git installed on your system.

### Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project directory:

```bash
cd bazardor
```

Install the dependencies:

```bash
npm install
```

Create a `.env.local` file in the root directory and configure the required environment variables for Better Auth and any other necessary services.

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

## Deployment

BazarDor can be deployed on Vercel, Netlify, Cloudflare Pages, or another compatible hosting platform.

For deployment:

1. Push the project to GitHub.
2. Import the repository into your preferred hosting platform.
3. Configure the required environment variables.
4. Deploy the application.
5. Verify that all routes, authentication features, API requests, and dynamic pages work correctly after deployment.

## Live Demo

**Live Link:** __________

## GitHub Repository

**GitHub Repository Link:** ____________


