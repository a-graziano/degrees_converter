# Degrees and Meters Converter

A simple web application to convert between degrees of latitude and meters. This tool is useful for geographic calculations and provides a user-friendly interface for quick conversions.

## Features

- Convert degrees of latitude to meters
- Convert meters to degrees of latitude
- User-friendly interface with clear input fields and buttons
- Real-time conversion results displayed on the page

## Conversion Factor

The conversion factor used is approximately 111,320 meters per degree of latitude.

## Usage

1. **Convert Degrees to Meters:**
   - Enter the number of degrees in the input field under "Convert Degrees to Meters".
   - Click the "Convert to Meters" button.
   - The result will be displayed below the button.

2. **Convert Meters to Degrees:**
   - Enter the number of meters in the input field under "Convert Meters to Degrees".
   - Click the "Convert to Degrees" button.
   - The result will be displayed below the button.

## Code Structure

- **HTML**: The structure of the web page, including input fields, buttons, and result display areas.
- **CSS**: Styling for the web page to ensure a clean and modern look.
- **JavaScript**: Functions to handle the conversion logic and update the results on the page.

## Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Degrees and Meters Converter</title>
    <style>
        /* CSS styles here */
    </style>
</head>
<body>
    <div class="container">
        <h1>Degrees and Meters Converter</h1>
        
        <div>
            <h2>Convert Degrees to Meters</h2>
            <label for="degreesInput">Degrees:</label>
            <input type="number" id="degreesInput" placeholder="Enter degrees">
            <button onclick="convertDegreesToMeters()">Convert to Meters</button>
            <p id="degreesResult"></p>
        </div>

        <div>
            <h2>Convert Meters to Degrees</h2>
            <label for="metersInput">Meters:</label>
            <input type="number" id="metersInput" placeholder="Enter meters">
            <button onclick="convertMetersToDegrees()">Convert to Degrees</button>
            <p id="metersResult"></p>
        </div>
    </div>

    <script>
        // JavaScript functions here
    </script>
</body>
</html>


## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/degrees-meters-converter.git

2. Navigate to project directory
  ```bash
cd degrees-meters-converter

3. Open the index.html file in your web browser to use the converter.
