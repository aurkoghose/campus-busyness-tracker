# Campus Busyness Tracker

A Java program that helps Purdue students check how busy campus parking lots and study spaces are using student-submitted ratings.

## Project Goal

Students often waste time searching for available parking or study spaces on campus. This project aims to help students make better decisions by allowing them to report and view busyness levels at different campus locations.

## MVP Features

- Display a list of campus study spaces and parking lots.
- Allow users to submit busyness ratings (Empty, Moderate, Busy, or Full).
- Allow users to view the most recent busyness rating for each location.

## Future Plans

- Use historical data to identify peak hours.
- Combine multiple student reports to estimate crowd levels.
- Suggest nearby locations based on busyness levels.

## Tech Stack

- **Language:** Java
- **Libraries:** Scanner, LocalDateTime, ArrayList, HashMap, FileReader, BufferedReader, and FileWriter
- **Data Storage:** Local CSV file for storing locations, ratings, and timestamps
- **Interface:** Command-line menu
- **External Data Sources:** None

## Development Plan

1. Set up the project and GitHub repository.
2. Create a list of campus study spaces and parking lots.
3. Create a menu to display locations and allow users to select one.
4. Allow users to submit busyness ratings.
5. Save submitted ratings to a CSV file.
6. Read the CSV file and display the latest busyness rating for each location.
