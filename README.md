# Matrix HAR Automation System

## Overview

The Matrix HAR Automation System is a sophisticated tool designed to streamline the process of gathering and utilizing real estate listings from the Matrix HAR platform. Developed with Node.js, this automation system is tailored for macOS users, providing a seamless experience for real estate professionals or individuals interested in real estate market trends. The system automates the process of fetching announcements with specific filters, extracting relevant details, and sending personalized emails to a curated list based on the filtered announcements.

### Features

- **Web Scraping**: Automatically opens the Matrix HAR website and fetches announcements based on predefined filters.
- **Data Extraction**: Extracts crucial information from the listings, including address, square footage, cost, and the contact name.
- **Email Automation**: Sends personalized emails to the extracted list, using customizable templates that support variables such as `{{address}}`, `{{sqft}}`, `{{cost}}`, and `{{name}}`.
- **User Interface**: Offers a clean and intuitive UI with functionalities to view logs, adjust settings, and set filters for scraping.
- **macOS Compatibility**: Developed specifically for macOS users, ensuring compatibility and smooth operation.

### How It Works

1. **Setting Up Filters**: Users can set their desired filters through the UI, specifying what type of listings they are interested in.
2. **Scraping and Extraction**: The system then visits the Matrix HAR website, applies the filters, and extracts listing information.
3. **Email Dispatch**: Using the extracted information, the system generates and sends out personalized emails to the relevant contacts.

### Technology

This project is built using Node.js, leveraging various libraries for web scraping, data extraction, and email automation. The UI is developed with an emphasis on user experience, providing a straightforward and effective tool for real estate monitoring and outreach.

## Note

This project is showcased for portfolio purposes only and is not available for direct download or deployment. It demonstrates my ability to automate complex web interactions, data extraction, and communication processes within a specific real estate platform context.
