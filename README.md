![image](https://github.com/user-attachments/assets/875c6b9e-4226-451d-b28c-45cfc1069512)

Investment Calculator
Overview
The Investment Calculator is a web application that helps users calculate their investment growth over time. By entering initial investment details, expected returns, and investment duration, users can visualize how their investments grow year by year.
Features
- Input fields for:
  - Initial investment
  - Annual investment
  - Expected return rate
  - Investment duration (in years)
- Dynamic results table displaying:
  - Yearly investment value
  - Yearly interest earned
  - Total interest accumulated
  - Invested capital
- Responsive design with a clean and modern interface.
Technologies Used
- React.js: Frontend framework for building the user interface.
- CSS: Custom styling for responsive and appealing design.
- JavaScript: Core logic for investment calculations.
- Google Fonts: Fonts for typography enhancements.
Installation and Setup
Follow these steps to run the project locally:
1. Clone the repository: git clone https://github.com/your-username/investment-calculator.git
2. Navigate to the project directory: cd investment-calculator
3. Install dependencies: npm install
4. Start the development server: npm start
5. Open your browser and visit: http://localhost:3000
Usage
1. Enter the required investment details in the input fields.
2. View the results in the dynamic table that updates automatically.
3. Analyze the yearly breakdown of your investments, including:
   - Total value
   - Interest earned
   - Total interest
   - Invested capital.
src/
│
├── components/
│   ├── Header.jsx         # Displays the header section
│   ├── UserInput.jsx      # Handles input fields for user investment data
│   ├── Results.jsx        # Displays the results table
│
├── util/
│   ├── investment.js      # Logic for investment calculations
│
├── App.jsx                # Main application component
├── index.js               # Entry point
├── styles.css             # Custom styling for the app
Future Enhancements
- Add support for multiple investment strategies.
- Enable data export to CSV or Excel.
- Improve data visualization with graphs.
Contact
If you have any questions or feedback, feel free to reach out at:
- Email: yosipovnoa@gmail.com
