# UBCProfPeek

UBCProfPeek is a Chrome extension that helps UBC students make smarter course registration decisions by displaying professor ratings (from RateMyProfessors) and course GPA data (from UBCGrades) directly within the Workday registration interface.

## Status

Work in Progress (WIP)  
This project is still under development. Currently supports professor rating display after expanding a course section in Workday.  
UBCGrades integration and improved UI are planned.

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

- Vanilla JavaScript / Chrome Extension API
- DOM mutation observer to detect expanded sections
- Unofficial RateMyProfessors API (or scraping fallback)
- UBCGrades data integration (planned)

## License

This project is licensed under the Business Source License 1.1.  
See the [LICENSE](./LICENSE) file for full terms.

You may use this project for personal and non-commercial purposes only.  
Commercial use is not permitted without written permission from the author.  
On April 17, 2029, the license will automatically convert to Apache 2.0.

## Author

Developed by [Kohei](https://github.com/kohei-swb)  
Built to solve a real problem I encountered during course registration.  
If it's useful for you too, feel free to use it and contribute.

## Feedback

If you have suggestions, ideas, or want to contribute, feel free to open an issue or contact me via GitHub.
