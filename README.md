# 🍊 SustainAbite - Food Waste Reduction Platform

**SustainaBite** is a mobile-first web application designed to bridge the gap between food surplus and food scarcity. It connects restaurants and households with nearby NGOs to facilitate quick and easy food donations.

> *"Snap a pic, share the meal!"*

## 📱 Project Overview

This application focuses on speed and ease of use. It allows donors to upload details about leftover food in under 30 seconds and notifies nearby registered NGOs for pickup.

**Key Features:**
* **Dual Login System:** Separate workflows for Donors and NGOs.
* **Smart Donation Flow:** Visual categorization, freshness slider, and quantity icons.
* **👨‍🍳 Chef AI:** A feature for donors to find recipes for leftover ingredients (mockup).
* **NGO Dashboard:** Real-time feed of available food donations.
* **Zero-Backend Demo:** Uses `localStorage` to simulate data transfer between Donor and NGO views without a server.

## 🚀 Live Demo

[Link to your Vercel deployment goes here]
https://sustain-abite-app.vercel.app/

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Properties for theming), Vanilla JavaScript.
* **Logic:** Browser `localStorage` for state management.
* **Design:** Mobile-First, Responsive, High-contrast UI (Orange/Green theme).

## 📂 File Structure

The project consists of 4 main files:

1.  **`index.html` (formerly login.html):** The entry point. Handles authentication simulation for Users and NGOs.
2.  **`dashboard.html`:** The main Donor interface. Includes camera upload, freshness slider, and recipe finder.
3.  **`results.html`:** Displays a list of nearby NGOs (Indian context) after a donation is submitted.
4.  **`ngo-dashboard.html`:** The Recipient interface. Automatically displays the donation data submitted by the user.

## ⚙️ How to Run Locally

1.  **Clone or Download** this repository.
2.  Open the folder on your computer.
3.  **Double click `index.html`** to open the app in your browser.

**To simulate the full flow:**
1.  Open the app and log in as a **Donor**.
2.  Fill out the donation details and click "Find NGOs".
3.  Once you reach the results page, open **`ngo-dashboard.html`** in a **separate browser tab**.
4.  You will see your donation appear there automatically!

## 🎨 Design Highlights

* **Color Psychology:** * 🟠 **Harvest Orange:** Used for Donor actions (warmth, food).
    * 🟢 **Leaf Green:** Used for NGO actions (eco-friendly, fresh).
    * 🔴 **Urgent Red:** Used for "Eat Soon" warnings.
* **Indian Context:**
    * Input placeholders optimized for Indian names and mobile formats (+91).
    * Dummy data includes NGOs like *Robin Hood Army* and *Feeding India*.

## 🔮 Future Improvements (Roadmap)

* [ ] **Backend Integration:** Connect to Firebase/Node.js for real-time database storage.
* [ ] **Map Integration:** Use Google Maps API to show live locations.
* [ ] **OpenAI API:** Connect the "Chef AI" button to a real GPT model for actual recipe generation.
* [ ] **Push Notifications:** Enable browser service workers for real alerts.

## 📄 License

This project is open-source and available for educational purposes.

---
*Made with ❤️ for a hunger-free world.*
