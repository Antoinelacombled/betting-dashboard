# Sports Betting Dashboard

## Overview

This Sports Betting Dashboard is a React-based web application designed to help sports bettors track their bets, analyze their performance, and make informed decisions. The dashboard provides a comprehensive view of your betting history, calculates key metrics, and offers tools like the Kelly Criterion calculator to optimize your betting strategy.

## Features

- **Bankroll Tracking**: Visualize your bankroll evolution over time.
- **Bet Management**: Easy input and tracking of individual bets.
- **Performance Metrics**: 
  - Win Rate
  - Return on Investment (ROI)
  - Performance trends over the last 6 days
- **Kelly Criterion Calculator**: Helps determine optimal bet sizes.
- **Data Persistence**: Uses local storage to save your data between sessions.
- **Responsive Design**: Fully functional on both desktop and mobile devices.

## Technology Stack

- React.js
- recharts for data visualization
- CSS for styling
- Local Storage API for data persistence

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/sports-betting-dashboard.git
   ```

2. Navigate to the project directory:
   ```
   cd sports-betting-dashboard
   ```

3. Install dependencies:
   ```
   npm install
   ```

4. Start the development server:
   ```
   npm start
   ```

5. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Usage

### Adding a New Bet

1. Navigate to the "Add New Bet" section.
2. Enter the date, stake, and odds for your bet.
3. Click "Add" to save the bet.

### Updating Bet Results

1. Find the bet in the "List of Bets" section.
2. Check the box in the "Won" column to mark a bet as won.

### Using the Kelly Criterion Calculator

1. Go to the Kelly Criterion Calculator section.
2. Enter the probability of winning and the decimal odds.
3. Click "Calculate" to see the recommended stake size.

### Viewing Performance Metrics

- The top of the dashboard displays current Bankroll, Win Rate, and ROI.
- Each metric shows the percentage change:
  - For Bankroll: Change from the initial bankroll.
  - For Win Rate and ROI: Change over the last 6 days compared to the previous period.

## Code Structure

- `src/components/Dashboard.jsx`: Main dashboard component
- `src/components/KellyCalculator.jsx`: Kelly Criterion calculator component
- `src/components/ui/`: Contains reusable UI components (Card, Button, Input, etc.)
- `src/Dashboard.css`: Styles for the dashboard

## Data Persistence

The application uses the browser's Local Storage to persist data. This means:
- Your data is saved locally on your device.
- Data will persist between page reloads and browser sessions.
- Clearing your browser data will erase this stored information.

## Limitations

- Data is stored locally and not synced across devices.
- Local Storage has limited capacity (usually around 5-10 MB).

## Future Enhancements

- Implement user accounts and cloud storage for data.
- Add more advanced statistical analysis tools.
- Integrate with sports betting APIs for real-time odds and results.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

- React.js community for the excellent documentation and resources.
- recharts library for the powerful charting capabilities.

## Contact

If you have any questions or suggestions, please open an issue in this repository.

---

Happy betting and remember to gamble responsibly!
