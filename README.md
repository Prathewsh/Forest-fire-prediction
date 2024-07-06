# Forest Fire Prediction Website

## Overview

Forest Fire Prediction Website is a web application that predicts the probability of a forest fire taking place based on oxygen, temperature, and humidity content. This tool aims to assist in forest fire prevention and management by providing accurate predictions.

## Features

- Predicts forest fire probability based on input parameters
- User-friendly web interface
- Utilizes machine learning models for prediction

## Installation

### Prerequisites

- Python 3.7 or higher
- Flask
- PyCharm IDE

### Steps

1. Clone the repository:

   ```sh
   git clone https://github.com/Prathewsh/Forest-fire-prediction.git
   cd Forest-fire-prediction
   ```

2. Install the required packages:

   ```sh
   pip install -r requirements.txt
   ```

3. Set up the project in PyCharm:

   - Open PyCharm and load the project from the cloned repository.
   - Ensure that the `templates` and `static` folders are correctly placed in the project directory.

4. Add the HTML file:

   - Place the `forest.html` file in the `templates` folder.

5. Add CSS and JavaScript files:
   - In the `static` folder, add the CSS and JS files for Materialize CSS.
   - You can get the necessary files from [Materialize CSS](https://materializecss.com/getting-started.html).

## Usage

1. Run the Flask application:

   ```sh
   python app.py
   ```

2. Open your web browser and navigate to `http://127.0.0.1:5000/`.

3. Enter the oxygen, temperature, and humidity values to get the forest fire probability prediction.

## How It Works

The website works by taking input values for oxygen, temperature, and humidity from the user. These inputs are then processed by a machine learning model to predict the probability of a forest fire.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your fork.
4. Create a pull request with a description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please open an issue or contact [prathewsh123@gmail.com](mailto:prathewsh123@gmail.com).
