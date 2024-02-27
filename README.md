# Weather Microservice

## What it is?

The Weather Microservice is a python service that takes a requested location and returns key weather data about that location using the OpenWeatherMap.org API.

## How to Request Data

To request data from the Weather Microservice, the user must provide a string in `City, State, Country` format, or in cases where state isn't valid (e.g. Paris, France), the user must utilize `City, Country` format. Currently, the provided string is written in the `location.txt` file and to update the call, the `location.txt` file must simply be updated (e.g. Seattle, WA, US).

## How to Receive Data

To receive data, the user's program should read from the `data.json` file. At this time, the file is overwritten each time a request is sent to include:
- Current Temp
- Humidity
- Weather Description
- Icon (the icon can be rendered into the user's app by following the instructions outlined at: https://openweathermap.org/weather-conditions#Icon-list)

## UML Sequence Diagram

