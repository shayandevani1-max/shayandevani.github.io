# shayandevani.github.io
Built GOAT Court, a sports trivia and philosophy web game for friends and classmates to test their knowledge. Players answer football and basketball trivia from Easy to Impossible, draft all-time NFL/NBA rosters to chase 17-0 and 82-0 seasons, and spot logical fallacies in sports hot takes
Games
Football Trivia and Basketball Trivia: four levels each (Easy, Medium, Hard, Impossible). Harder levels give less time and multiply your points. Get three or more right in a row for streak bonuses.
17-0 mode (NFL) and 82-0 mode (NBA): pick any of the 32 NFL or 30 NBA franchises. Each roster slot asks for a real player from that team's history at a position and era (pre-1995, 1995–2009, or 2010+), like "Name a Ravens quarterback from 1995 to 2009." Type the name to sign him. You get three tries per slot and one Scout per draft that shows every player who fits. Your roster's rating then decides how an 82- or 17-game season plays out. Can you go undefeated?
Guess the Fallacy: read a real-sounding sports hot take and name the logical fallacy behind it (straw man, post hoc, slippery slope and more).
Guess the Player: clues are revealed one at a time, from hardest to easiest. Type your guess. The fewer clues you need, the more points you get.
The fallacy rulebook: 12 common fallacies, each with a sports example.
Why I built it

I love sports, and some of my favorite times are playing trivia games with my friends. I wanted a way for us to keep testing our knowledge against each other, so I built one. Now my friends and classmates can play the same games, compare scores and records, and settle who really knows the most.

I also want to study philosophy, and sports debates are full of bad arguments. The fallacy games bring in the critical-thinking skills I care about, like spotting fallacies and weighing evidence, using something people already argue about every day.

How it works

It's a single HTML file with no frameworks or build step: HTML, CSS and vanilla JavaScript. It has over 120 hand-checked trivia questions and a scouting database of about 1,350 player stints across every NFL and NBA franchise, each tagged by position, era and a rating. Best scores and records are saved in the browser with localStorage. It adapts to light and dark mode and works on phones.
