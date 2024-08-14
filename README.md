# Calculator Application

This project is a simple, interactive calculator application built using HTML, CSS, and JavaScript. It allows users to perform calculations and view the result in real-time.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How the App Works](#how-the-app-works)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Calculator Functionality:** Users can perform calculations using the calculator buttons.
- **Real-Time Results:** The result of the calculation is displayed in real-time as the user inputs the calculation.

## Technologies Used

- **HTML5:** For structuring the content.
- **CSS3:** For styling the application.
- **JavaScript (ES6+):** For adding interactivity and handling logic.
- **Google Fonts:** For the Poppins font used in the application.
- **Font Awesome & Boxicons:** For icons used in buttons and UI elements.

## How the App Works

### 1. **Performing Calculations**

When the user clicks the calculator buttons, the `performCalculation` function is triggered. This function takes the current value of the display and the value of the button that was clicked, and it performs the calculation based on the operator.

### 2. **Displaying the Result**

The result of the calculation is displayed in the `display` element. The `updateDisplay` function is used to update the display with the result of the calculation.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/KingZingBoss/calculator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-list
   ```

3. Open the `index.html` file in your preferred web browser:

   ```bash
   open index.html
   ```


## Usage

Simply enter a calculation by clicking the number buttons, selecting an operator (+, -, *, /), and clicking the equal sign (=) to display the result. You can also use the AC button to clear the display, the DE button to delete the last digit of the display, and the . button to add a decimal point.

## Project Structure

The project structure is as follows:

- `index.html`: The main HTML file that contains the calculator interface.
- `assets/css/style.css`: The CSS file that styles the calculator.
- `assets/js/script.js`: The JavaScript file that handles the calculator logic.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
