# Monthly Habit Tracker 📅

A simple, interactive monthly habit tracker built with vanilla HTML, CSS, and JavaScript. This project allows users to set a monthly goal and track their daily progress directly in their web browser.

## ✨ Features

* **Interactive Calendar:** Click on individual days to mark them as complete (turns white) or incomplete (turns pink).
* **Local Storage Integration:** Your progress is saved locally in your browser. If you close the tab or refresh the page, your tracked days will still be there!
* **Customizable Habit Title:** Click on the default "My New Habit" text to open a prompt and rename it to whatever specific habit you are tracking this month.
* **Smart Date Tracking:** * Automatically detects and displays the current month.
  * Automatically highlights the current day of the month.
  * Adjusts the number of clickable days based on the current month (e.g., 30 days for April, 31 for May).
* **Progress Counter:** Keeps a running tally of how many days you have completed versus the total days in the month (e.g., "5/31").
* **Reset Functionality:** A quick reset button to clear all saved progress and start the month over.

## 🛠️ Technologies Used

* **HTML5:** Page structure and layout.
* **CSS3:** Styling, grid layouts, and visual design (including a custom background pattern).
* **JavaScript (Vanilla):** DOM manipulation, date calculations, and `localStorage` management.

## 🚀 How to Run Locally

Since this is a front-end-only project, no servers or dependencies are required. 

1. Clone this repository or download the source code as a ZIP file.
2. Extract the files to a folder on your computer.
3. **Important:** Ensure that your HTML file and the background image file (`bg-pattern.jpg`) are located in the exact same folder.
4. Double-click the `.html` file to open it in your default web browser.

## 📁 File Structure

```text
├── index.html        # Contains the HTML, CSS, and JavaScript
├── bg-pattern.jpg    # The background pattern image
└── README.md         # Project documentation
