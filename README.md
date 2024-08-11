# Pricewise: eCommerce Price Tracker

<p align="center">
  <img src="https://github.com/user-attachments/assets/a9aa17d4-bc1b-4c95-8a33-54df7b35d023" alt="Web Datascraping">
</p>
<p align="left">
  Source: <a href="https://gcore.com/learning/what-is-web-scraping/">GCORE</a>
</p>

## Introduction

Welcome to the eCommerce price tracking project: Pricewise, a powerful tool built using Next.js and Bright Data's webunlocker. This project aims to assist users in making informed purchasing decisions by monitoring product prices and availability on popular platforms like Amazon. By utilizing web scraping, users can be notified of price drops or out-of-stock alerts, allowing them to optimize their shopping experience.

Web scraping is the process of automatically extracting data from websites. It enables us to gather information at scale, which would be impractical to do manually. In this project, we use web scraping to collect product details, such as pricing and stock status, which are then presented to users through a visually appealing interface.

This project is particularly important for consumers who want to stay ahead of price changes and for businesses looking to keep an eye on competitor pricing. By automating the data collection process, users save time and gain valuable insights to make strategic decisions.

## Tech Stack

<p><a target="_blank" href="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="42" height="42" /></a> <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="42" height="42" /></a> <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="42" height="42" /></a> <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="42" height="42" /></a> <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="42" height="42" /></a> <a target="_blank" href="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" style="display: inline-block;"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="42" height="42" /></a> <a target="_blank" href="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" style="display: inline-block;"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="42" height="42" /></a></p>

## Features

 **Header with Carousel**: Features a visually attractive header with a carousel that highlights the site's key features and benefits.
 
 **Product Scraping**: Includes a search bar where users can enter Amazon product links to initiate scraping.
 
 **Scraped Projects**: Displays information about products that have been scraped, providing insights into items being tracked.
 
 **Scraped Product Details**: Displays the product's image, title, pricing, and other relevant information gathered from the original website.
 
 **Track Option**: Offers a modal where users can input their email addresses and opt-in to track specific products.
 
 **Email Notifications**: Automatically sends alert emails to notify users of various events, such as when a product is back in stock or reaches the lowest price.
 
 **Automated Cron Jobs**: Leverages cron jobs to automate regular scraping activities, ensuring the data remains current.

## Prerequisites

**[Git](https://git-scm.com/)**

**[Node.js](https://nodejs.org/en)**

**[npm (Node Package Manager)](https://www.npmjs.com/)**

## Project Dependencies Installation using npm:

```
npm install
```
## Environment Setup

Create a new file named `.env` in the root of your project and add the following content:

```
#SCRAPER
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

#DB
MONGODB_URI=

#OUTLOOK
EMAIL_USER=
EMAIL_PASS=
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these specific websites from [BrightData](https://brightdata.com/), [MongoDB](https://www.mongodb.com/), and [Node Mailer](https://nodemailer.com/).

## Running the Project

```shell
npm run dev
```

Open [http://localhost:3000](http://localhost:3000/) in your browser to view the project.
