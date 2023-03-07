# Weather-App
A weather app that checks multiple cities for outlook

## User Story

```
AS A traveler
I WANT to see the weather outlook for multiple cities
SO THAT I can plan a trip accordingly
```

## Acceptance Criteria

```
GIVEN a weather dashboard with form inputs
WHEN I search for a city
THEN I am presented with current and future conditions for that city and that city is added to the search history
WHEN I view current weather conditions for that city
THEN I am presented with the city name, the date, an icon representation of weather conditions, the temperature, the humidity, and the wind speed
WHEN I view future weather conditions for that city
THEN I am presented with a 5-day forecast that displays the date, an icon representation of weather conditions, the temperature, the wind speed, and the humidity
WHEN I click on a city in the search history
THEN I am again presented with current and future conditions for that city
```

## Acceptance Criteria Simplified

In this project you'll create a webpage that allows people to perform searches for the weather report in various cities.

You will need to complete the following subtasks:

* Create a page with the following:
    * A text input for entering a city
    * A button to perform the search
    * A section for showing previous searches
    * A section for showing the fetched weather data
    * The input and button should be inside a form so that pressing "enter" on the input field will cause the search to trigger
* When the user enters a city and performs the search (the form is submitted):
    * Fetch the weather data from the openWeatherMap API (the 5 day forcast)
        * A 5 day forecast can contain today as one of the days. This should be perfectly fine as long as you're showing 5 days of data
    * Put the city into the saved searches list (persist this to localstorage)
    * Show the fetched weather data in the appropriate section. Make it look pretty!
* The saved searches should load from localstorage when the page is loaded
* When clicking on a saved search, that search data should be fetched and displayed
* The page should look pretty! You can use the mockup as an example or make your own version. It must "resemble" the mockup, but you can use your own creative liberties.
