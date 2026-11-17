# Rumora: Free Room Finder (Wireframe and UX Design)

A cross-platform mobile app design that helps university students find an empty room quickly. This repository holds the Figma wireframes, style guide and design write-up for my **CO2404 Cross Platform Development** coursework (BSc Software Engineering, 2026/2027).

## Status

| Stage | State |
|---|---|
| Style guide (logo, colour palette, dark and light themes) | Done |
| 13 wireframe layouts in Figma | Done |
| Annotations, Android vs iPhone thinking, design rationale | Done |
| Flutter app | Planned |

## The idea

Students often cannot tell which rooms are free. Rumora lets a student pick a date and a time period, optionally filter by building, and see which rooms are free. Room data comes from the university room booking service.

## Screens

| # | Screen | Purpose |
|---|---|---|
| 1 | Welcome | Explains the app before login |
| 2 | Log in | University email and password, with show password and remember me |
| 3 | Find a Room | Date, time period and building, with a Today shortcut |
| 4 | Server Responding | Loading and offline messages |
| 5 | Results | Free and booked rooms for the chosen period |
| 6 | Room Details | Status now plus the whole day for one room |
| 7 | Search Rooms | Search by room code, with recent searches |
| 8 | Settings | Dark mode, text size, log out |
| 9 | Help & About | How it works and where the data comes from |
| 10 | Filters | Building, minimum seats and show booked rooms |
| 11 | No Rooms | Explains an empty result and suggests nearby periods |
| 12 | Favourites | Saved rooms, checked for right now |
| 13 | Basic Layout | The shared top bar and structure used across screens |

## Design decisions

**Usability**
- One clear action per screen, with a Today shortcut and time chips that show the clock time.
- Loading, offline and no-result states explain what happened and what to do next.
- Shortcuts for repeat users: Favourites, recent searches and Filters.

**Accessibility**
- Free and booked rooms use a tick or cross plus a word, never colour alone.
- Touch targets of at least 48 × 48 dp.
- Dark mode, a text size slider and a show password option.

**Consistency**
- One style guide for both themes.
- Same top bar, room card and chip across screens.
- Labels such as Date, Time Period and Building are named the same everywhere.

## Android vs iPhone

The wireframes are drawn in iPhone style. The design notes cover the differences for Android: back navigation, title alignment, switches, the loading spinner and touch target size. See the report for the full table.

## Style guide

- **Themes:** dark and light, from one shared palette.
- **Logo:** purple house-and-computer icon.
- **Tool:** Figma.

## Repository contents

```
/
├── README.md
├── report/        Wireframe and write-up report (PDF)
├── figma/         Exported wireframes and style guide (images or PDF)
└── images/        Screenshots used in this README
```

## Built with

- Figma for wireframes and the style guide
- Flutter (planned for the app)

## Academic note

This is my own coursework, shared as part of my portfolio. Please do not copy it for your own submission.

## Author
**Tharushi**, second-year Software Engineering student
