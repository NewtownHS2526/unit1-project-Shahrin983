# My Fan Page - HTML/CSS Lab Project

## Overview
This is a static HTML/CSS educational project for students to create a fan page. It's a simple website consisting of HTML and CSS files served by a Python HTTP server.

## Project Structure
- `index.html` - Main HTML file (currently has basic skeleton)
- `style.css` - CSS styling for the page
- `U1LAB1.md` - Lab instructions and requirements
- `server.py` - Python HTTP server to serve static files

## Recent Changes
- **2025-10-06**: Initial Replit setup
  - Installed Python 3.11
  - Created simple HTTP server on port 5000
  - Configured workflow to run the server
  - Added .gitignore for Python files
  - Set up deployment configuration

## How to Run
The project runs automatically via the configured workflow. It serves the static HTML/CSS files on port 5000 using Python's built-in HTTP server.

## Lab Information
This is Unit 1 Lab 1 - a student assignment to build a fan page website including:
- Header section with name, quote, and image
- About Me section
- Achievements section with nested divs
- Other/Links section

Students should edit `index.html` to add content and can modify `style.css` for styling.

## Architecture
- **Frontend**: Static HTML/CSS files
- **Server**: Python SimpleHTTPServer (development only)
- **Port**: 5000 (frontend)
- **No backend**: This is a pure static site project
