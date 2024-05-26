# Converter Application

This repository contains a simple web-based converter application that includes various converters for temperature, units, currency, and a world clock. The application consists of five main HTML files: `home.html`, `temperature.html`, `units.html`, `worldclock.html`, and `currency.html`.

## Table of Contents

- [Home Page (home.html)](#home-page-homehtml)
- [Temperature Converter (temperature.html)](#temperature-converter-temperaturehtml)
- [Units Converter (units.html)](#units-converter-unitshtml)
- [World Clock (worldclock.html)](#world-clock-worldclockhtml)
- [Currency Converter (currency.html)](#currency-converter-currencyhtml)
- [How to Use](#how-to-use)
- [Installation](#installation)
- [License](#license)

## Home Page (home.html)

The `home.html` file is the main landing page of the converter application. It provides navigation to the different converters through clickable boxes.

### Features:
- Displays the application title with a gradient effect.
- Four clickable boxes that redirect to different converters:
  - World Clock
  - Temperature Conversion
  - Units Conversion
  - Currency Conversion
- Responsive design to ensure proper display on various devices.

## Temperature Converter (temperature.html)

The `temperature.html` file allows users to convert temperatures between Celsius, Fahrenheit, and Kelvin.

### Features:
- Input field to enter the temperature value.
- Dropdown menu to select the input temperature unit.
- Button to trigger the conversion.
- Displays the converted values in all three units.
- Responsive design for different screen sizes.

### Conversion Logic:
- Converts the input temperature to the selected unit and displays the results for all units.
- Validates input to ensure a valid number is entered.

## Units Converter (units.html)

The `units.html` file provides functionality to convert between various units of length, weight, and volume.

### Features:
- Dropdown menus to select the input and output units.
- Input field to enter the value to be converted.
- Button to perform the conversion.
- Displays the converted value.
- Responsive design for different screen sizes.

### Conversion Logic:
- Supports conversions for length, weight, and volume units.
- Uses functions to handle conversions between different unit types.

## World Clock (worldclock.html)

The `worldclock.html` file displays the current time in various time zones.

### Features:
- Dropdown menu to select a time zone.
- Button to display the current time in the selected time zone.
- Displays the current time in the selected time zone.
- Responsive design for different screen sizes.

### Time Display Logic:
- Uses Moment.js and Moment Timezone.js libraries to handle time zone conversions.
- Populates the time zone dropdown with available time zones.

## Currency Converter (currency.html)

The `currency.html` file provides a simple interface to convert between different currencies.

### Features:
- Input field to enter the amount to be converted.
- Dropdown menus to select the input and output currencies.
- Button to trigger the conversion.
- Displays the converted value.
- Responsive design for different screen sizes.

### Conversion Logic:
- Placeholder for conversion logic which could be implemented using an API for real-time exchange rates.

## How to Use

1. Open the `home.html` file in a web browser.
2. Click on the desired conversion type (World Clock, Temperature Conversion, Units Conversion, or Currency Conversion).
3. Use the provided interface in the selected converter to perform conversions.

## Installation

To run the application locally:

1. Clone this repository to your local machine.
   ```sh
   git clone https://github.com/yourusername/converter-application.git
   ```
2. Navigate to the cloned directory.
   ```sh
   cd converter-application
   ```
3. Open the `home.html` file in your preferred web browser.

