# Formula One Database Management System

## Overview

This project aims to create a relational database that captures and organizes extensive data related to Formula One racing, one of the most popular and data-driven sports globally. The database stores information from all Formula One seasons, spanning from 1950 to 2022, and offers users the ability to query and analyze various aspects of the sport, including driver and constructor performances, race results, qualifying sessions, lap times, and more.

## Project Objectives

The primary objective of this project is to develop a user-friendly application that allows Formula One enthusiasts to explore and analyze historical data. The application will enable users to:

- Track the performance of drivers and constructors over different seasons.
- Analyze race results, qualifying sessions, lap times, and pit stop data.
- Compare the performance of drivers on a per-lap basis during races.
- Save favorite drivers and constructors for quick access to their performance data.
- Conduct complex data analysis to uncover trends and patterns in Formula One history.

## Dataset

The dataset used in this project includes comprehensive information on Formula One races, teams, drivers, circuits, and results:

- **Races**: Data on over 70 years of races, including the circuit name, location, altitude, and more.
- **Drivers**: Information on all drivers who have competed in Formula One.
- **Constructors**: Data on the teams (constructors) participating in Formula One.
- **Qualifying Sessions**: Details of qualifying sessions for each race, including lap times and positions.
- **Lap Times**: Data on lap times for each driver in every race.
- **Pit Stops**: Information on pit stops made by drivers during races.
- **Standings**: Driver and constructor standings after each race in a season.

## Tools and Technologies

- **Database Management**: MySQL Workbench is used to manage the relational database and store the data.
- **Front-End Development**: The front-end is built using Java, with Java Swing used for the graphical user interface (GUI).
- **Data Analysis**: The application provides users with tools to analyze and visualize the data stored in the database.

## Features

### User Interaction

- **Login/Signup**: Users can create an account or log in to access the application.
- **Main Interface**: Once logged in, users enter the main interface, where they can select any combination of season, race, constructor, and driver to explore specific data.
- **Data Querying**: Users can query qualifying results, race results, lap times, and pit stop data based on their selections.
- **Favorite Drivers and Constructors**: Users can add, replace, or delete their favorite drivers and constructors, and quickly access their performance data.
- **Formula One Information**: For users unfamiliar with Formula One, the application provides an option to learn more about the sport.

### Data Query Options

- **Qualifying**: View the results of qualifying sessions, including lap times and starting grid positions.
- **Race**: Analyze race results, including final positions and the number of laps completed by each driver.
- **Lap Time**: Compare lap times of different drivers to understand their performance over the course of a race.
- **Pit Stop**: Examine pit stop strategies, including the timing and duration of stops for each driver.

## Rationale

The idea for this project originated from a personal interest in Formula One, inspired by the childhood memories of one of the team members watching races with his grandfather. Formula One is a sport where data analysis plays a crucial role, making it a suitable subject for a database management system project. This project not only serves as a tool for fans to explore historical data but also showcases the importance of data-driven decision-making in sports.

## UML Diagram

The project’s UML diagram illustrates the relationships between different entities in the database, such as drivers, constructors, races, and results. (Note: Include the UML diagram file if available).

## Future Enhancements

As the project progresses, additional features and enhancements may be added, including:

- **Advanced Data Visualization**: Incorporating more sophisticated data visualization techniques to help users better understand the data.
- **User Profiles**: Allowing users to customize their profiles and save more personalized data queries.
- **Mobile Version**: Developing a mobile-friendly version of the application for better accessibility.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Kr-Yan/formula1-database.git
   cd formula1-database

2. Database Setup:

Install MySQL and create a database using the provided SQL scripts in the database/ directory.
Import the dataset into your MySQL database.

3. Running the Application:

Compile and run the Java application from the src/ directory.
Ensure that your MySQL server is running and that the application is correctly configured to connect to your database.

# Author
- Kairuo Yan
- Jerry Bao

