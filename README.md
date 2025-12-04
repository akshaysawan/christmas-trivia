🎄 Office Party Trivia Game

A festive, browser-based trivia game designed for office parties and holiday gatherings. Built with Bootstrap and pure JavaScript, it runs entirely in the browser—no server setup required!

✨ Features

🏆 Team Scoring System: Upload a list of teams, track scores live, and see a leaderboard at the end.

🎨 Multi-Theme Support: Switch between Christmas, New Year, Diwali, and Holi themes instantly.

🎵 Background Music: Plays festive tunes (defaults to Christmas) with a toggle button.

💾 Auto-Save: Accidentally refreshed the page? The game remembers your progress and scores!

📂 CSV Upload: Load your own custom questions and teams via simple CSV files.

❄️ Visual Effects: Falling snow/confetti animations and sound effects.

⌨️ Keyboard Controls: Easy navigation for presenters.

🚀 How to Host on GitHub Pages

Upload index.html, bgmusic.mp3 (optional), and your CSV files to a GitHub repository.

Go to Settings > Pages.

Under Branch, select main and click Save.

Visit your site at: https://<your-username>.github.io/<repo-name>/

🎮 How to Play

Welcome Screen: Click "Let's Play" to start the music and enter setup.

Upload Files:

Questions (Required): Upload your trivia questions CSV.

Teams (Optional): Upload your teams CSV. If skipped, the game runs in "Presentation Mode" without scoring.

Gameplay:

Press Spacebar or Right Arrow to reveal the answer.

Award Points: If teams are loaded, buttons will appear. Click the team name that answered correctly to give them a point.

Press Right Arrow again to move to the next question.

Winner: At the end, a podium leaderboard will display the winners!

Keyboard Shortcuts

Space / →: Reveal Answer / Next Question

←: Previous Question

↑ / ↓: Toggle Answer Visibility

📝 CSV Formats

You can create these in Excel or Google Sheets and save as .csv.

1. Questions File (trivia_questions.csv)

Question

Answer

What is Santa's favorite snack?

Cookies and Milk

Where does the Grinch live?

Mount Crumpit

2. Teams File (teams.csv)

Team Name

Players

The Rudolphs

John, Jane, Bob

The Snowmen

Alice, Mike

Team Tinsel

Sarah, Dave

🎵 Adding Music

To use your own music for the Christmas theme:

Rename your audio file to bgmusic.mp3.

Place it in the same folder as index.html.

🛠️ Built With

Bootstrap 5 (Styling)

PapaParse (CSV Parsing)

Canvas Confetti (Celebration effects)

FontAwesome (Icons)