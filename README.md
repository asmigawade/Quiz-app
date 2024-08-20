

# Trivia Quiz App

This is a React-based trivia quiz app that dynamically fetches multiple-choice questions from the Open Trivia Database API. The app features a quiz structure with a timer, a money pyramid system, and a high score tracker stored in the browser's local storage.

## Features

- **Dynamic Questions:** Fetches 12 multiple-choice questions from the Open Trivia Database API.
- **Money Pyramid:** Progresses through increasing levels of monetary rewards.
- **Timer:** Adds a time constraint for each question.
- **High Score:** Tracks and saves the highest score locally.
- **Responsive Design:** A visually appealing UI with a game show-style layout.

## Technologies Used

- React
- JavaScript (ES6+)
- CSS (for styling)
- Open Trivia Database API

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/trivia-quiz-app.git
   cd trivia-quiz-app
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the App:**
   ```bash
   npm start
   ```

4. **Build for Production:**
   ```bash
   npm run build
   ```

## Usage

1. **Start the Game:** Enter your username to begin the game.
2. **Answer Questions:** Answer the questions within the time limit. The app will move to the next question if the correct answer is selected or if the time runs out.
3. **Track Your Earnings:** The app will display the amount earned based on the number of correct answers.
4. **High Score:** If you exceed your previous high score, it will be updated in local storage.

## API

This app uses the [Open Trivia Database API](https://opentdb.com/api_config.php) to fetch trivia questions.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Replace `yourusername` with your GitHub username when pasting into your repository.
