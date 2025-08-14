# Cranium Care Calendar Card (C.C.C.C)

*Version 1.0 - August 13, 2025*

A mobile-optimized, single-page web application to track a multi-week scalp care routine. Built with React, Tailwind CSS, and Shadcn/UI, this app provides a daily guide and allows for progress tracking with notes, all saved locally in your browser.

## Features

* **Daily Plan View**: Displays the specific task for each day in a scrollable, card-based interface.
* **Flexible Time Ranges**: View the schedule for today only, one week, two weeks, or four weeks.
* **Completion Tracking**: Mark days as complete to track your progress.
* **Local Notes**: Add quick notes directly on a day card or use a larger dialog for more detailed daily entries. All notes are saved to your device's local storage.
* **Search Functionality**: Quickly find days by product name (e.g., "Nizoral"), action, or tag.
* **Built-in Timer**: A 5-minute countdown timer is included on relevant days to ensure correct application time for medicated shampoos.
* **.ICS Export**: Download the schedule as an `.ics` calendar file, with optional reminders for hydrocortisone applications.
* **Responsive Design**: A mobile-first, dark-themed interface designed for ease of use on any device.

## Tech Stack

* **Framework**: React
* **UI Components**: Shadcn/UI
* **Styling**: Tailwind CSS
* **Icons**: Lucide React
* **Date Management**: date-fns
* **State Management**: React Hooks (useState, useEffect) and a custom `useLocalStorage` hook.

## Getting Started

To run this project locally:

1.  Clone the repository:
    ```sh
    git clone [https://github.com/dweebzxx/Cranium-Care-Calendar-Card.git](https://github.com/dweebzxx/Cranium-Care-Calendar-Card.git)
    ```
2.  Navigate to the project directory:
    ```sh
    cd Cranium-Care-Calendar-Card
    ```
3.  Install dependencies:
    ```sh
    npm install
    ```
4.  Start the development server:
    ```sh
    npm run dev
    ```
