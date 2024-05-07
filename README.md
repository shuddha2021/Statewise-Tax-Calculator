# Tax Calculator

The Tax Calculator is a web application that allows users to calculate their federal and state taxes based on their income and state of residence. This project uses modern web technologies to provide a user-friendly interface and accurate tax calculations.

## Key Features

- **State Selection**: Select from all 50 U.S. states to get accurate state tax calculations.
- **Federal Tax Brackets**: The app uses predefined federal tax brackets to calculate the federal tax for the given income.
- **Dynamic Calculation**: Calculates taxes in real-time as the user enters their income and selects a state.
- **Reset Functionality**: Users can reset the form to start a new calculation.
- **Responsive Design**: The app is designed to work on various screen sizes, including desktops, tablets, and mobile devices.
- **Tooltips**: Informative tooltips guide users to understand the income field and other elements.
- **Animations and Transitions**: Smooth animations for a better user experience.


<img width="1147" alt="Screenshot 2024-05-07 at 10 42 23 AM" src="https://github.com/shuddha2021/TaxCalculatorAllStates/assets/81951239/35f2b9fd-34c8-482f-ae2f-111dfe475013">

<img width="1124" alt="Screenshot 2024-05-07 at 10 41 32 AM" src="https://github.com/shuddha2021/TaxCalculatorAllStates/assets/81951239/480c2521-14a3-42cc-9bb7-8731ae594f95">


## Core Logic

The core logic of the Tax Calculator involves computing the federal and state taxes based on user input. Here's an overview of the core components:

- **Federal Tax Calculation**: The `calculateFederalTax` function uses a predefined set of tax brackets to compute the federal tax based on the given income.
- **State Tax Calculation**: The `calculateStateTax` function uses a dictionary of state tax rates to compute the state tax for the selected state.
- **Input Validation**: The app ensures the income is positive and handles errors gracefully when input is invalid.
- **Result Display**: The results section displays the calculated federal tax, state tax, total tax, and after-tax income, with smooth transitions and animations.

## Technologies Used

- **HTML5 and CSS3**: For building the structure and styling of the web application.
- **JavaScript**: The core language used for logic and interactions.
- **Bootstrap**: Used for responsive design and modern styling.
- **Font Awesome**: Provides icons for the user interface.
- **Animate.css**: For animations and transitions.

## Getting Started

To run the Tax Calculator locally, follow these steps:

1. Clone the repository: `git clone <your-repo-url>`
2. Navigate to the project directory: `cd <your-project-directory>`
3. Open the index.html file in your browser to start using the application.

## Contributing

Contributions to the Tax Calculator are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request. When contributing, please ensure you follow the existing code style and add appropriate tests for any new functionality.

## License

This project is licensed under the MIT License. For more information, see the LICENSE file in the repository.

## Acknowledgments

- **Bootstrap**: For providing a comprehensive framework for responsive design.
- **Font Awesome**: For the icon library used in the project.
- **Animate.css**: For animation and transition effects.
- **Open-Source Community**: For enabling collaboration and innovation.
