# Use Cases

## Player Creating a Game
1. Player logs in and selects "Create Room"
2. Player configures room settings (public/private, max players, rounds, AI assistance level)
3. System generates room code
4. Player shares code with friends or waits for public joining

## Regular Gameplay Round
1. System randomly selects a player to draw
2. System offers drawer 3 word choices with varying difficulty
3. Drawer selects a word and begins drawing
4. Other players view the drawing in real-time and submit guesses
5. AI analyzes the drawing progression
6. AI provides incremental hints at specific time intervals
7. Players who guess correctly receive points based on speed
8. Round ends when time expires or all players guess correctly
9. System displays the word, artist, and results

## AI Hint Generation
1. Round begins, AI initializes with word knowledge
2. After 25% of time: AI provides category-level hint
3. After 50% of time: AI generates hint based on drawing content
4. After 75% of time: AI provides more specific hint based on drawing and previous guesses
5. Hints are displayed to all guessing players

## Optional Drawing Assistance
1. Drawer opts-in to drawing assistance
2. As drawer creates their illustration, AI analyzes clarity
3. If drawing might be difficult to recognize, AI suggests additions
4. Drawer can accept/reject suggestions
