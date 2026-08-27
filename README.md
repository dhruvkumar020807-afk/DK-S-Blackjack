# DK-S-Blackjack
# DK's Blackjack — The Green Room

A browser-based blackjack game with hit/stand/double/split, dealer AI, sound effects, and a global leaderboard powered by Firebase Firestore.

**Play it live:** https://dksblackjack.netlify.app

## Features

- Full blackjack gameplay: hit, stand, double down, and split
- Dealer AI that stands on 17
- Betting system with a running bankroll
- Sound effects via the Web Audio API
- Persistent global leaderboard — best scores are saved and ranked across sessions using Firebase Firestore

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Firebase Firestore (leaderboard storage)

## Running locally

Clone the repo and open `index.html` in your browser:

\`\`\`bash
git clone https://github.com/dhruvkumar020807-afk/DK-S-Blackjack.git
cd DK-S-Blackjack
open index.html
\`\`\`

The live leaderboard requires a Firebase project connection, so leaderboard scores may not save when run purely offline/locally — gameplay itself works fully offline.

## Author

Dhruv Kumar — [GitHub](https://github.com/dhruvkumar020807-afk) · [LinkedIn](https://www.linkedin.com/in/dhruv-kumar-84740533b)
