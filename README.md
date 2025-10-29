React-Redux Job Portal Application
This is a modern job portal web application built using React, Redux Toolkit for state management, Tailwind CSS for styling, and Vite as the development/build tool. The application manages user authentication, job listings, company data, and job applications seamlessly through Redux slices.

Features
User authentication and session management via authSlice

Job listings, filtering, and search managed with jobSlice

Company profile handling and CRUD operations using companySlice

Job application management with applicationSlice

Centralized Redux store managing all slices

Responsive UI styled with Tailwind CSS

Fast development and hot reload with Vite

File Structure & Description
File	Description
authSlice.js	Manages authentication state including login, logout, and user session management
jobSlice.js	Handles job listings, filters, search parameters, and asynchronous job-related actions
companySlice.js	Responsible for managing companies' data and actions
applicationSlice.js	Manages job application submissions and statuses
store.js	Configures and combines all Redux slices into a single store
constant.js	Contains constant values used throughout the application
utils.js	Utility functions supporting various features
main.jsx	Application entry point that sets up the Redux Provider and renders the React app
index.css	Global styles and Tailwind CSS imports
tailwind.config.js	Tailwind CSS configuration including custom themes and plugins
vite.config.js	Vite configuration file for React and optimized builds
Getting Started
Prerequisites
Node.js (v16+ recommended)

npm or yarn package manager

Installation
Clone the repository:

bash
git clone <repository_url>
cd <project_folder>
Install dependencies:

bash
npm install
# or
yarn install
Run the application:

bash
npm run dev
# or
yarn dev
Open your browser and visit http://localhost:5173 to use the app.

Usage
Register or log in to access personalized job features.

Browse and filter jobs by various criteria.

View detailed company profiles.

Apply to jobs and track the application statuses.

Log out when done.

Customize & Extend
Modify Redux slices (authSlice.js, jobSlice.js, companySlice.js, applicationSlice.js) to match your backend API specifics.

Extend Tailwind styling in index.css and customize the theme with tailwind.config.js.

Update Vite configuration in vite.config.js for further build customizations.

Utilize utility functions in utils.js or add new helpers as necessary.

Dependencies
React 18+

Redux Toolkit

React-Redux

Tailwind CSS & DaisyUI (optional)

Vite

Axios (for API calls, to be integrated in slices or components)
