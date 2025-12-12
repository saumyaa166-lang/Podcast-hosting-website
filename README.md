This README will provide an overview of the project, instructions on how to set it up, and information about the files.

🎙 PodWave - Podcast Hosting Website
Project Overview
PodWave is a simple, two-page static website designed to showcase a fictional "all-in-one podcast hosting solution."

The project consists of:

A Login Page (podcast-login.html) with basic client-side validation using JavaScript.

A Marketing/Landing Page (podcast-home.html) highlighting the service's features, about information, and contact details.

Both pages are built using HTML and CSS for structure and styling, with JavaScript used exclusively on the login page for form validation.

Files in this Repository
File Name	Description
podcast-login.html	The main login page for the PodWave dashboard. Includes hardcoded username/password for demonstration and client-side validation.
podcast-home.html	The main landing page/marketing site for the PodWave service. Features sections for Home, Features, About, and Contact.
README.md	This file.

Export to Sheets

🚀 Getting Started
To run and test this project locally, simply follow these steps:

Clone or Download: Get the podcast-login.html and podcast-home.html files.

Open Login Page: Double-click the podcast-login.html file to open it in your default web browser.

Test Login: Use the correct credentials (see Customization below) to log in and be redirected to podcast-home.html.

View Home Page: You can also directly open podcast-home.html to view the main website.

⚙️ Customization
The login logic is handled in the <script> block of podcast-login.html. You can easily change the required username and password.

In podcast-login.html, modify the following lines in the validateLogin() function:

JavaScript

      // ⭐⭐⭐ CHANGE YOUR CORRECT USERNAME HERE ⭐⭐⭐
      const correctUsername = "saumya-singh"; // Current Value
      
      // ⭐⭐⭐ CHANGE YOUR CORRECT PASSWORD HERE ⭐⭐⭐
      const correctPassword = "singh.saumya"; // Current Value

      // ⭐⭐⭐ CHANGE YOUR PODCAST WEBSITE FILE NAME HERE ⭐⭐⭐
      window.location.href = "podcast-home.html"; // Target page after successful login
Key Features of the PodWave Site
Login Page (podcast-login.html)
Modern Design: Features a gradient background and a focused login container.

Client-Side Validation: Checks if fields are empty and if the input matches the hardcoded correct credentials.

Auto-Submit: Allows form submission using the "Enter" key on the username and password fields.

Landing Page (podcast-home.html)
Responsive Layout: Uses basic CSS to create a clean, single-column layout suitable for desktop viewing.

Navigation: Features a sticky navigation bar with internal links that scroll to the relevant sections (#home, #features, #about, #contact).

Feature Showcase: Highlights key product offerings, including a fictional "Podcast Cinematic Mode."
