# Org Quest Deluxe — Kingdom Rescue

A colourful, fully browser-based learning game for Diploma in Accounting: Business Organisational Structures & Design.

## Publish on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `script.js` and `README.md` to the repository root.
3. Open **Settings → Pages → Deploy from a branch**, select `main` and `/(root)`, then save.
4. Open the GitHub Pages URL after deployment.

## Controls and scoring
- Click/tap balloons or use keyboard keys 1–4.
- 10 points for a correct first attempt. Incorrect attempts can be retried with no time pressure.
- Read explanation and click Continue.
- Music and sound effects use Web Audio, so no external audio files or internet are required. Click Start Adventure to unlock audio in browsers; use the Music On/Off button to mute.
- Progress, world changes, confetti, four badges and final question review are included.

## Edit learning content
Edit the `QUESTIONS` array at the top of `script.js`. Each question has `level`, `q`, `options`, `answer` (zero-based: 0=A, 1=B, 2=C, 3=D), and `why` explanation. The last question is a transfer challenge.

The included question bank uses general subject knowledge and is not claimed to be strictly derived from a specific lecturer's notes. No personal data is collected or stored.

## Dancing characters
A small animated parade of four dancing cartoon animal emoji appears along the bottom of the screen. The main fox mascot also dances. Motion is disabled for users requesting reduced motion.

## Bonus arcade games
After questions 4, 8, and 12, players enter three interactive mini-games: Star Catcher (mouse, touch, arrow keys), Build-a-Tower (click/tap numbered bricks in order), and Treasure Hunt (click/tap bushes). All are untimed and do not affect academic scores.

## Subject-integrated mini-games
1. Finance Department Dash: catch finance-related tasks (budget, invoice, accounts), avoid marketing and cooking tasks.
2. Build the Reporting Chain: select CEO, Department Manager, Supervisor, Employee in reporting order.
3. Decision Detective: four scenarios distinguishing centralised and decentralised authority.
All three are untimed and do not change the 15-question learning score.

## October 2026 bug fix
Fixed disabled Continue Learning button after mini-game completion. Added Skip Mini-Game to continue directly to the next question.
