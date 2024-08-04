# Dynamic OG Image Generation

## Overview

The Dynamic OG Image Generation project is a web application that allows users to create and share posts with dynamically generated Open Graph (OG) images. These images are tailored based on the content of the post, including the title, content, and an optional image. The project includes both a React front-end and a Node.js back-end for image generation.

## Features

- **Create Posts:** Allows users to input a title, content, and an optional image.
- **Generate OG Images:** Dynamically generates OG images based on the post content.
- **View and Share:** Automatically includes the OG image meta tag in the HTML for proper display on social media.

## Project Structure
```
dynamic-og-image/
├── node_modules/ # Node.js modules
├── public/ # Public assets
├── src/ # React source files
│ ├── App.css
│ ├── App.js
│ └── components/
│ └── PostPage.js
├── server/ # Node.js server files
│ ├── node_modules/ # Node.js modules for the server
│ ├── index.js # Server entry point
│ ├── package.json # Server dependencies
│ └── public/ # Public assets for the server
├── .gitignore # Git ignore file
├── README.md # Project documentation
└── package.json # React project dependencies
```

## Getting Started

### Prerequisites

- Node.js and npm (or Yarn) installed.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/dynamic-og-image.git
   cd dynamic-og-image

Usage
Create a Post:

Enter a title and content in the provided fields.
Upload an optional image.
Click "Submit" to generate the OG image and view the result.
Testing OG Image Generation:

Use tools like Facebook Debugger, Twitter Card Validator, and LinkedIn Post Inspector to test how your OG images appear when shared on social media.
Troubleshooting
Blank Page on Localhost:
Ensure you are running both the React front-end and Node.js back-end servers.
Check browser console and server logs for errors.
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.


