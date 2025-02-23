Task

Overview

This project implements a dynamic homepage using React.js with reusable components, interactive state management, and CSS modules for styling.

File Structure

Homepage.js: Main container that renders the header, accordion, and footer.

Header.js: Allows navigation and displays selectable components.

Accordian.js: Handles dynamic rendering of sidebar items and content components.

Footer.js: Displays the footer section.

OurTeam.js, PersonalDetails.js, ContactUs.js: Individual components rendered based on user selection.

Features

Displays "Our Team" component by default.

Clicking an item in the header or sidebar swaps the displayed component.

Previously displayed components return to the sidebar.

State is managed using React's useState hook.

Installation

Clone the Repository:

git clone <repository-url>

Navigate to the Project Directory:

cd project-directory

Install Dependencies:

npm install

Start the Development Server:

npm start

Usage

Header Navigation: Select components from the header; selected items are removed from the sidebar.

Accordion Sidebar: Select components from the sidebar to display them in the main area.

State Management

selectedItem: Tracks the currently displayed component.

accordianItems: Stores the list of components available in the sidebar.

The handleSelection function updates both states to ensure proper swapping of components.

Technologies Used

React.js for building UI components.

CSS Modules for modular and scoped styling.

**Live link**: https://timely-pegasus-35f709.netlify.app/
