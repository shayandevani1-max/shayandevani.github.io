# shayandevani.github.io
GOAT Court

Sports trivia meets philosophy. A browser game for sports fans who like to argue.

Play it:

Games
Daily Challenge: 10 new questions every day (NFL and NBA from Easy to Impossible, plus two fallacies), the same for everyone. One try per day, with a day streak, a shareable 🟩🟥 result grid and a daily leaderboard.
NFL Trivia and NBA Trivia: four levels each (Easy, Medium, Hard, Impossible), with 8, 12 or 16 rounds. Harder levels give less time and multiply your points. Get three or more right in a row for streak bonuses.
17-0 mode (NFL) and 82-0 mode (NBA): pick your franchise, then draft a roster. Each slot asks for a real player from a random team and era (pick an era mode: random mix, 2010–present, 1995–2009 or pre-1995), and three any-era slots take any player at that position from the team shown, from any era. Type the name to sign him, with name suggestions as you type. You get one shot per slot (misspellings don't count), one Scout that shows every player who fits, and a 60- or 90-second draft clock. Your roster's rating then decides how the 17- or 82-game season plays out. Can you go undefeated?
Guess the Fallacy: read a real-sounding sports hot take and name the logical fallacy behind it (straw man, post hoc, circular reasoning and more).
Guess the Player: clues are revealed one at a time, from hardest to easiest. Type your guess. The fewer clues you need, the more points you get.
Challenge a friend: create a code before you play, or get one after any game (like D-NFL-PIT-M-A-61690). It rebuilds the exact same draft or question set, so friends can go head-to-head.
Leaderboards: post your score to public top-25 boards for every mode.
The fallacy rulebook: 16 common fallacies, each with a sports example.
Why I built it

I love sports, and some of my favorite times are playing trivia games with my friends. I wanted a way for us to keep testing our knowledge against each other, so I built one. Now my friends and classmates can play the same games, compare scores and records, and settle who really knows the most.

I also want to study philosophy, and sports debates are full of bad arguments. The fallacy games bring in the critical-thinking skills I care about, like spotting fallacies and weighing evidence, using something people already argue about every day.

How it works

It's a single HTML file with no frameworks or build step: HTML, CSS and vanilla JavaScript. It has about 150 hand-checked trivia questions and a scouting database of about 3,500 player stints across the 1960s to today, from legends to current players, across every NFL and NBA franchise, each tagged by position, era and a rating. Personal bests are saved in the browser with localStorage, challenge codes use a seeded random number generator so the same code always builds the same game, and the leaderboards are stored in Google Firebase (Firestore). It adapts to light and dark mode and works on phones.
