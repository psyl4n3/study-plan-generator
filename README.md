# Generate Study Schedule Script for Google Sheets

Leveraging the insights on effective long-term memorization by Pete Zerger, this Google Apps Script automates the creation of a study schedule in Google Sheets. It's designed to prompt users for a start date and the total number of chapters or sections for study, then it crafts a schedule that incorporates spaced repetition intervals for optimized learning and review.

## Features

- **Custom Schedule Creation**: Generates a new, uniquely timestamped schedule sheet within your Google Spreadsheet.
- **Input-Driven Customization**: Asks for the study's start date and the total number of chapters to tailor the schedule to your specific plan.
- **Spaced Repetition Based on Expert Insights**: Adheres to Pete Zerger's recommended intervals for spaced repetition, targeting enhanced long-term memorization.
- **Automated Sheet Formatting**: Automatically applies sorting, filtering, and column adjustments for enhanced readability.

## Installation

1. Open your desired Google Spreadsheet.
2. Click on `Extensions` > `Apps Script`.
3. Erase any present code in the script editor and paste the provided script.
4. Save the script, ideally with a descriptive name like `GenerateStudySchedule`.

## How to Use

1. After saving the script, refresh your spreadsheet page. A new menu item titled `Generate Study Schedule` will appear.
2. Select `Generate Study Schedule`, then click on `Generate`.
3. Follow the prompts to input the start date (in MM/DD/YYYY format) and the total number of chapters.

### Input Details

- **Start Date**: The commencement date for your study, which anchors the schedule.
- **Number of Chapters**: The count of chapters or sections you plan to study, defining the schedule's span.

## Schedule Layout

The script populates the schedule with columns for:

- **Chapter**: Identifies the chapter number or title.
- **Learn/Review**: Marks the entry as a learning day or a review day.
- **Date**: The planned date for the study or review activity.
- **Notes**: Provides additional details, like the repetition count in the spaced repetition cycle.

### Spaced Repetition Strategy

Incorporating Pete Zerger's method for effective memorization, the schedule includes intervals as follows:

- **First Repetition**: Right after learning.
- **Second Repetition**: 20-30 minutes following the learning session.
- **Third Repetition**: One day later.
- **Fourth Repetition**: After 2-3 weeks.
- **Fifth Repetition**: Approximately 2-3 months later.

## Customization Tips

Feel free to modify the script to adjust intervals or add repetitions, tailoring it to your learning needs.

## Important Notes

- Make sure your spreadsheet's locale settings are correct to prevent potential issues with date formats and script execution.
- If you encounter errors, double-check the start date format and ensure the chapter number is positive.
