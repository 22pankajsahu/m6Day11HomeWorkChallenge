# m6Day11HomeWorkChallenge

# Tip Generator Web Application

This is a simple web application that allows users to generate tips based on the bill amount, service quality, and the number of people sharing the bill.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Screenshots](#screenshots)
- [How it Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Demo

Check out the live demo of the Tip Generator application [here](https://22pankajsahu.github.io/m6Day11HomeWorkChallenge/).

## Features

- Generate tips based on bill amount, service quality, and number of people sharing the bill.
- Display the calculated tip amount.

  ## Screenshots

Include relevant screenshots of the application here.

![image](https://github.com/22pankajsahu/m6Day11HomeWorkChallenge/assets/135128502/5589b7a8-54b1-4c2f-ae26-38c66e1d73b0)

![image](https://github.com/22pankajsahu/m6Day11HomeWorkChallenge/assets/135128502/70a59055-a157-4ded-a1ea-df36f3dfd04a)



## How it Works

The Tip Generator application is built using HTML, CSS, and JavaScript. Here's a brief overview of how each component contributes to the functionality:

### HTML (index.html)

The HTML file sets up the structure of the web page and includes the following elements:

- Input fields for entering the bill amount, selecting service quality, and specifying the number of people sharing the bill.
- A button to calculate the tip.

### CSS (style tag)

The CSS file provides styling to the different elements of the Tip Generator application:

- Styling for the container, input fields, and button is defined to provide a visually pleasing user interface.

### JavaScript (script tag)

The JavaScript file provides the interactivity and functionality of the Tip Generator application:

1. **Event Listener**
   - The `cal` button is set to listen for the `click` event, which triggers when the user clicks the button.

2. **Tip Calculation**
   - When the button is clicked, the event handler retrieves the values entered by the user for bill amount, service quality, and number of people sharing.
   - The tip is calculated based on the formula: `(bill * quality) / sharing`, where `quality` is a multiplier based on the selected service quality.

3. **Display Tip**
   - The calculated tip amount is displayed in the designated `<p>` element.

## Installation

To run the Tip Generator application locally, follow these steps:

1. Clone this repository: `git clone https://github.com/22pankajsahu/m6Day11HomeWorkChallenge.git`
2. Navigate to the project directory: `cd tip-generator`
3. Open `index.html` in your web browser.

## Usage

1. Open the Tip Generator application in your web browser.
2. Enter the bill amount, select service quality, and specify the number of people sharing the bill.
3. Click the "Calculate" button.
4. The application will display the calculated tip amount.

## Contributing

Contributions are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`
3. Make your changes and commit: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature/new-feature`
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Name: [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu)
- Email: [22pankajsahu@email.com](mailto:22pankajsahu@gmail.com)
- GitHub: [22pankajsahu](https://github.com/22pankajsahu)
