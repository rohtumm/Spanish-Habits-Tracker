# Spanish-Habits-Tracker

This project is a website that allows Spanish teachers to track their students' progression on their Spanish habits outside of class and gives students an efficient way to get feedback/suggestions on them. There are multiple pages in the website, the first of which is a login screen where students select their name and enter their password. Once this is completed, each student is able to update their own habits tracking table with habits that they completed for the week. From this page, they are then able to view where they stand in the class in terms of their overall habits score. Additionaly, the feedback generation feature is linked in this same page, in which students can enter the habits they worked on and receive suggestions on what to pursue for the future.

## Cloning and Navigating to the Repository

```bash
git clone https://github.com/rohtumm/Spanish-Habits-Tracker.git
cd Spanish-Habits-Tracker
```
## Installing Dependencies

```bash
npm install
npm install @google/generative-ai
```

## Running the App
```bash
npm start
```

## Gemini API Key
Before you can run the code, you need to obtain a Gemini API Key from Google AI Studio. Once you have this, simply add the key to a .env file at the same level as the package.json file. inside of the frontend folder.

## Future Improvements
The following features could be implemented to add functonality:
* Class-wide leaderboard for points system
* Gamified components to encourage further participation in habits tracking
* Ability to attach files (pdfs, videos, etc.) to receive feedback on
