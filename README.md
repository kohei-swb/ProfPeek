# UBCProfPeek

UBCProfPeek is a Chrome extension that helps UBC students make smarter course registration decisions by displaying professor ratings (from RateMyProfessors) and course GPA data (from UBCGrades) directly within the Workday registration interface.

## Status

Work in Progress (WIP)  
Currently supports displaying professor ratings from RateMyProfessors after a section is expanded.  
Planned improvements include UBCGrades integration and a more polished UI.

## Features (MVP)

- Automatically detects professor names once a course section is expanded
- Fetches RateMyProfessors data (Overall rating, Difficulty, Would Take Again %)
- Planned: GPA statistics from UBCGrades
- Planned: Clean UI with badges or tooltip-style info cards

## Preview

Coming soon – screenshot or GIF of the extension in action

## Target Audience

- UBC students using Workday to register for courses
- Anyone who wants professor insights without leaving the registration page

## Tech Stack

- JavaScript (Vanilla)
- Chrome Extension API
- MutationObserver for DOM changes
- Unofficial RateMyProfessors GraphQL API (with fallback)
- UBCGrades (CSV/JSON parsing or static bundle)

## Architecture (Planned Overview)

- `content.js`: DOM parsing and injection
- `rmp.js`: Handles RateMyProf API fetching and caching
- `gpa.js`: (planned) Integrates GPA info from UBCGrades
- GitHub Actions (optional): For updating static data if scraping is not viable

## License

This project is licensed under the Business Source License 1.1.  
See the [LICENSE](./LICENSE) file for full terms.

You may use this project for personal and non-commercial purposes only.  
Commercial use is not permitted without written permission from the author.  
On April 17, 2029, the license will automatically convert to Apache 2.0.

## Author

Developed by [Kohei](https://github.com/kohei-swb)  
As a UBC student, I was frustrated by the time-consuming process of switching tabs just to check professor reviews during course registration.  
This extension solves that problem by integrating key information directly into Workday.

## Feedback

Suggestions, feedback, or contributions are welcome.  
Feel free to open an issue or contact me on GitHub.
