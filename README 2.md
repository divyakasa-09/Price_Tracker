# Price Tracker - E-commerce Product Scraping Site

Price Tracker is a dynamic e-commerce product scraping site developed using Next.js and Bright Data's webunlocker. The platform is designed to empower users with informed purchasing decisions by providing real-time alerts on product price drops . The entire system is orchestrated through automated cron jobs to ensure up-to-date data.

## ⚙️ Tech Stack
- **Next.js:** A React framework for building server-rendered applications.
- **Bright Data:** Empowering web data collection through their webunlocker service.
- **Cheerio:** A fast, flexible, and lean implementation of core jQuery for server-side scraping.
- **Nodemailer:** A module for Node.js applications to send emails.
- **MongoDB:** A NoSQL database for storing scraped product information.
- **Headless UI:** A set of completely unstyled, fully accessible UI components for React.
- **Tailwind CSS:** A utility-first CSS framework for rapidly building custom designs.

## 🔋 Features
- **Header with Carousel:** A visually appealing header featuring a carousel to highlight key features and benefits.
- **Product Scraping:** A user-friendly search bar enabling users to input Amazon product links for seamless scraping.
- **Scraped Projects:** Displays detailed insights into tracked items, showcasing information on products scraped so far.
- **Scraped Product Details:** Showcase product images, titles, pricing, details, and other relevant information scraped from the original website.
- **Track Option:** Modal for users to provide email addresses and opt-in for tracking.
- **Email Notifications:** Automated email notifications for various scenarios, such as back-in-stock alerts or lowest price notifications.
- **Automated Cron Jobs:** Utilizes cron jobs to automate periodic scraping, ensuring data is always up-to-date.

## 🤸 Quick Start
Follow these steps to set up the project locally on your machine:

### Prerequisites
Ensure you have the following installed on your machine:
- Git
- Node.js
- npm (Node Package Manager)

### Cloning the Repository
```bash
git clone https://github.com/adrianhajdin/price-tracker.git
cd price-tracker
```

### Installation
Install the project dependencies using npm:
```bash
npm install
```

### Set Up Environment Variables
Create a new file named `.env` in the root of your project and add the following content:
```env
# SCRAPER
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

# DB
MONGODB_URI=

# OUTLOOK
EMAIL_USER=
EMAIL_PASS=
```
Replace the placeholder values with your actual credentials.

### Running the Project
```bash
npm run dev
```
Open http://localhost:3000 in your browser to view the project.

## 🕸️ Snippets
- **cron.route.ts**
- **generateEmailBody.ts**
- **globals.css**
- **index.scraper.ts**
- **next.config.js**
- **tailwind.config.ts**
- **types.ts**
- **utils.ts**


Happy scraping and tracking with Price Tracker! 🚀