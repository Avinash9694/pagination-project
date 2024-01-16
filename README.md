# Pagination React Project

This React project demonstrates a simple pagination functionality for displaying followers fetched from the GitHub API.

## Live Demo

Explore the live demo: [Pagination React Project](https://pagination-react-project1.netlify.app/)

## Overview

The project utilizes React to fetch followers' data from the GitHub API and implements a basic pagination feature. Users can navigate through different pages of followers and view their details.

### Key Components

- **App.js:** The main React component that handles the pagination logic and renders the UI.
- **Follower.js:** A component responsible for displaying individual follower details.
- **useFetch.js:** A custom hook for fetching data from the GitHub API and handling pagination.
- **utils.js:** A utility function for paginating the fetched data.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Avinash9694/pagination-project.git
   cd pagination-project
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the project:

   ```bash
   npm start
   ```

Visit [http://localhost:3000](http://localhost:3000) in your browser to explore the pagination project.

## Features

- **Pagination:** Navigate through different pages of followers.
- **Loading Indicator:** Displayed while fetching data.
- **Responsive Design:** Suitable for various screen sizes.
