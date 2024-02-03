# AirBnB Clone version 4

## Overview
This project is an extension of the AirBnB Clone series, focusing on web dynamic features. It utilizes Flask for the backend and JQuery for dynamic front-end interactions.

## Authors
- Goodness Akoma
- Elizabeth Nna

## Project Structure
- web_dynamic: Contains Flask web application and dynamic web pages.
  - static: Static files including styles and scripts.
  - templates: HTML templates for different pages.
- api: Flask application for the API.
- tests: Test cases (if applicable).
- README.md: Project documentation.

## Getting Started
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required dependencies:
   ```bash
   sudo apt-get install -y python3-lxml
   sudo pip3 install flask_cors
   sudo pip3 install flasgger
   ```
3. Start the Flask application:
   ```bash
   HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_dynamic.0-hbnb
   ```

## Tasks Overview
- Task 0: Set up the project repository and Flask application.
- Task 1: Implement basic Flask routes and templates.
- Task 2: Make the filters section dynamic using JQuery.
- Task 3: Check API status and display it dynamically.
- Task 4: Fetch places dynamically using the HBNB API.
- Task 5: Implement filtering places by Amenities.
- Task 6: Extend filtering to include States and Cities.
- Task 7: Add a feature to show and hide reviews dynamically.

## Additional Information
- Use [Flasgger](https://github.com/flasgger/flasgger) for API documentation.
- Ensure proper CORS configuration in `api/v1/app.py`.

## Contributing
Contributions are welcome! Please follow the project structure and coding standards.

## Acknowledgement
All thanks to ALX community.
