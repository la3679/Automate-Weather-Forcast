
# Weather Forecast Project

## Overview
This project generates daily weather forecasts for selected cities in the UK, India, and the US. The application retrieves real-time weather data, including temperature and humidity, from the OpenWeatherMap API and visualizes it in a well-designed image. The outputs are saved as both PNG and PDF files.

## Features
- Real-time weather data retrieval for predefined cities.
- Visualization of weather forecasts in an image format with easy-to-read design.
- Outputs saved in PNG and PDF formats for sharing and archiving.

## Project Files
- `weather.py`: The main script that handles data retrieval, processing, and image generation.
- `post.png` and `story.png`: Background templates for the weather images.
- City-specific PDFs and PNGs (e.g., `2024-12-20London.pdf`, `2024-12-20New York.pdf`): Generated weather reports for the respective cities.
- `Oswald-Regular.ttf`: Font file used for text rendering in the images.

## Requirements
- Python 3.x
- Required libraries: `requests`, `json`, `Pillow`
- API key for OpenWeatherMap

## Usage
1. Install the required Python libraries:
   ```bash
   pip install requests pillow
   ```
2. Set your OpenWeatherMap API key in the `api_key` variable in `weather.py`.
3. Run the script:
   ```bash
   python weather.py
   ```
4. The generated files will be saved in the same directory as the script.

## Output
The script produces:
- A PNG image visualizing the weather forecast.
- A PDF version of the same image.

## License
This project is licensed under the MIT License.
