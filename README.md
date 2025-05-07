# Dhaka Metro Fare Calculator

## 🚇 Overview

This is a simple front-end web application designed to help users easily calculate fares for the Dhaka Metro Rail. Users can select their starting and destination stations, and the application will display the corresponding fare based on the official fare chart. The website also provides important information regarding ticket types, MRT Pass/Rapid Pass, discounts, and refund policies.

## ✨ Features

* **Station Selection:** Intuitive dropdown menus for selecting "From" and "To" stations, featuring names in both English and Bengali.
* **Fare Calculation:** Quick and accurate fare calculation upon button click.
* **Dynamic Fare Display:** Clearly shows the calculated fare, with messages for same-station selection or initial state.
* **Informative Sections:**
    * Detailed information on Single Journey Tickets and MRT Pass/Rapid Pass.
    * Comprehensive details about available discounts (for freedom fighters, MRT Pass users, children, persons with special needs).
    * MRT Pass refund policy.
    * Information regarding travel without a valid ticket/pass.
* **Responsive Design:** The website is designed to be accessible and usable across various devices (desktops, tablets, and mobiles).
* **Themed Interface:** Currently styled with a Cerise red theme and a light beige background for a pleasant user experience.

## 🚀 How to Use

1.  **Open the `metro_fare.html` (or the respective HTML file name) in any modern web browser.**
2.  **Select your starting station** from the "From Station (যাত্রা শুরু)" dropdown.
3.  **Select your destination station** from the "To Station (গন্তব্য)" dropdown.
4.  **Click the "Calculate Fare (ভাড়া দেখুন)" button.**
5.  The calculated fare will be displayed below the button.
    * If the same station is selected for both "From" and "To", an appropriate message will be shown.
6.  Browse the "Ticket & Pass Types" and "Discounts & Special Info" sections for additional information.

## 💻 Technologies Used

* **HTML5:** For the basic structure of the website.
* **Tailwind CSS:** For styling and responsive design.
* **JavaScript (Vanilla):** For fare calculation logic, dynamic content updates, and populating dropdowns.
* **Google Fonts (Inter):** For typography.

## 📝 Fare Data

* The fare matrix and station list are based on the Dhaka Mass Transit Company Limited (DMTCL) fare chart information available as of May 2023 (as per the provided document).
* For the most current and official fare information, always refer to the official DMTCL website: [www.dmtcl.gov.bd](http://www.dmtcl.gov.bd).

## 🎨 Customization

The visual theme (colors, fonts) can be customized by modifying the `<style>` block within the `<head>` section of the HTML file and by updating the Tailwind CSS classes used throughout the document.
