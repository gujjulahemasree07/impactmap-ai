# ImpactMap AI

A multilingual project guide that helps students and community groups explore, compare, and plan AI and GIS projects for social impact.

## Problem

People may care about issues in their community but not know how to turn them into a practical technology project. They may also be unsure which tools, data sources, and first steps to use.

## Our solution

ImpactMap AI provides starter project ideas and beginner-friendly plans. Users can describe a cause, choose their experience level and available time, enter a district or town, and explore related projects.

## Features

- Starter ideas for flooding, agriculture, health access, heat, food access, and air quality
- Project comparison for up to three ideas
- Step-by-step plans, software suggestions, and official data/tool links
- English, Telugu, and Hindi interface options
- District or town field to help users plan around a chosen area
- Saved projects and browser-based progress tracking
- Demo sign-in and registration

## Technology

- HTML
- CSS
- JavaScript
- Browser localStorage for demo saves and progress

## Run locally

1. Download and extract the project folder.
2. Keep `index.html` and `login.html` in the same folder.
3. Open the folder in Visual Studio Code.
4. Open `index.html` in a browser, or use the Live Server extension.

The opening screen leads to `login.html`. The demo sign-in returns to the project website.

## Project files

- `index.html` — introduction, idea finder, project guide, plans, and comparison
- `login.html` — demo sign-in and registration page
- `README.md` — project information and setup instructions

## Prototype limitations

This is a front-end demo. The project guide uses local keyword matching; it is not connected to a live AI service. Sign-in is not connected to a real account system. The district/town field helps label a plan, but the prototype does not geocode locations, load local GIS layers, or produce real risk predictions. Add and verify local data before using any project for real-world decisions.

## Data and tool references

Data sources and official software links are provided inside the relevant project plans. Check each source’s terms and license before using or redistributing its data.

## AI-use disclosure

AI assistance was used during project ideation and code drafting. The team should review the code and disclose its AI use in the final submission.

## Team

Add the names and roles of all team members here.

## License

Choose a license with the whole team and add its license file here before public submission.
