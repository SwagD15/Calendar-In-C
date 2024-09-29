# Calendar Generator

A simple C program that generates a calendar for any specified year using Zeller's Congruence algorithm. The program displays the calendar month by month, taking into account leap years.

## Features

- Displays the full calendar for a specified year.
- Utilizes Zeller's Congruence algorithm to determine the first weekday of January 1st of that year.
- Correctly handles leap years, ensuring February has 29 days when appropriate.
- Clear formatting for easy readability.

## How It Works

The program calculates the first day of the week for January 1st of the given year using a modified version of Zeller's Congruence. It then iterates through each month, printing the days aligned with the correct weekdays.

### Zeller's Congruence

Zeller's Congruence is a well-known algorithm used to calculate the day of the week for any given date in the Gregorian calendar. The formula accounts for leap years and adjusts the day count accordingly.


