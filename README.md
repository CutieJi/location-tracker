
Built by https://www.blackbox.ai

---

```markdown
# Location Tracker

**Location Tracker** is a web application designed to generate shareable links that allow users to track and share their locations effortlessly. Ideal for coordinating meetups, deliveries, or simply keeping track of friends and family, this project offers a simple and user-friendly interface.

## Project Overview

The **Location Tracker** web application consists of three main pages:
- **Home Page**: Generate unique tracking links.
- **Track Page**: Access and display the user's current geographical location when the generated link is opened.
- **Dashboard**: View and manage all tracked locations with options to search, view details, and delete entries.

## Installation

This project does not require any specific setup or configuration. You can run it directly in your web browser by downloading the project files or cloning this repository. Just open `index.html` in your preferred browser.

### Steps to Run:

1. Clone the repository or download the files.
2. Open the `index.html` file in a web browser.

## Usage

1. Navigate to the **Home Page** to generate a tracking link by providing an optional name for the link.
2. The generated link can be shared with others. When opened, it will request location access from the user.
3. Users must allow location access for the application to function correctly. Once granted, it captures their latitude, longitude, and timestamp, and displays this information on the page.
4. Access the **Dashboard** to view all tracked locations, filter by name, and delete unwanted locations.

## Features

- Generate a unique tracking link that users can share.
- Request and access the user's geographical location with their consent.
- Display location details including latitude, longitude, and timestamp.
- Manage tracked locations through a user-friendly dashboard.
- Clear all tracked locations with a single click.

## Dependencies

The project relies on the following libraries:
- **Tailwind CSS** for styling.
- **Font Awesome** for icons.
- **Google Fonts** for typography.

Dependencies are linked via CDN in the HTML files and do not require any additional installation.

## Project Structure

The project consists of the following files:

```
/LocationTracker
│
├── index.html         # Home page for generating tracking links
├── track.html         # Page to display the user's location when the link is opened
└── dashboard.html     # Dashboard page to manage tracked locations
```

### File Descriptions

- **index.html**: Contains the frontend for tracking link generation. Includes the link generator and styling.
- **track.html**: Displays the user's current location and details after accessing the tracking link.
- **dashboard.html**: Manages and displays a list of previously tracked locations with functionalities to search, delete, and view them on a map.

## Conclusion

**Location Tracker** is a simple yet effective solution to share and track locations via unique links. It aims to facilitate easier coordination without compromising user experience. Feel free to explore and contribute to the project!
```