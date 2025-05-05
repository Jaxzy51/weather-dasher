# Weathex: Weather Dashboard

## User Story

As a traveler,  
I want to see the weather forecast for multiple cities  
So that I can plan my trips effectively.

## Acceptance Criteria

- **Given** a weather dashboard with input fields:  
  - **When** I search for a city,  
    - **Then** I see the current and 5-day forecast for that city, and it gets saved to the search history.

- **When** I view a city’s current weather,  
  - **Then** I see:
    - The city name  
    - Today’s date  
    - A weather icon  
    - A description of the icon via `alt` text  
    - The current temperature  
    - Humidity levels  
    - Wind speed  

- **When** I view the city’s 5-day forecast,  
  - **Then** I see for each day:
    - The date  
    - A weather icon  
    - The forecasted temperature  
    - Wind speed  
    - Humidity  

- **When** I click on a city in the search history,  
  - **Then** the current weather and forecast for that city are displayed again.
