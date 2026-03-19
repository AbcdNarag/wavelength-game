# Wavelength — The Spectrum Guessing Game for Language Learners

A free, browser-based adaptation of the board game Wavelength, designed specifically for English language learning classrooms. No account, no app, no internet connection required after the page loads.

---

## What Is Wavelength?

Wavelength is a social guessing game where one player (the Psychic) secretly sees where a target lands on a spectrum between two opposing concepts. The Psychic gives a single clue out loud, and the rest of the group debates and drags a needle to where they think the target sits.

Example: the spectrum is **"Boring" vs "Exciting"** and the Psychic says *"tax returns."* The team then argues about how boring tax returns really are and places the needle accordingly.

This version was built for language classrooms because it naturally generates vocabulary practice, oral production, comparisons, and opinion-sharing without students realising they are doing a language exercise.

---

## How to Play

1. Choose a vocabulary level and set up your teams on the start screen.
2. The Psychic looks at the screen privately — the dial shows the secret target position.
3. The Psychic gives **one clue out loud**. No typing needed during gameplay.
4. The Psychic passes the device to the team.
5. The team debates and drags the needle to their best guess, then locks in.
6. Points are awarded based on how close the needle lands to the target.
7. Teams take turns being the Psychic. Play as many rounds as you like — there is no round limit.

---

## Scoring

| Zone | Points |
|------|--------|
| Bullseye | 4 pts |
| Close | 3 pts |
| Near | 2 pts |
| Far | 1 pt |
| Miss | 0 pts |

---

## Vocabulary Levels

The game has three difficulty levels, each with 50+ pre-loaded spectrum pairs.

### Easy
Simple, everyday word opposites. Great for A1–A2 learners or younger students. Examples:
- Cold vs Hot
- Boring vs Exciting
- Bad habit vs Good habit
- Tiring walk vs Relaxing walk

### Moderate
Nuanced everyday concepts with some context-dependent vocabulary. Great for B1–B2 learners. Definition hints are available for select pairs. Examples:
- Overrated vs Underrated
- Awkward silence vs Comfortable silence
- Avoiding conflict vs Addressing things directly
- Overthinking everything vs Trusting your instincts

### Advanced
Rich vocabulary and full-phrase concepts designed to generate deeper discussion. Great for B2–C1 learners. Most pairs come with definition tooltips. Examples:
- Mundane vs Extraordinary
- A life that looks good from the outside vs A life that feels good from the inside
- Performing confidence vs Actually feeling confident
- A career that impressed everyone except you vs A career that fulfilled you even when nobody noticed

---

## Features

- **Three vocabulary levels** with 50+ pairs each, randomised every round
- **Definition helpers** — a small ? button appears next to unfamiliar words so students can check the meaning without interrupting the game
- **Editable spectrum labels** — the Psychic can change either side of the spectrum before each round, or type in completely custom ones. The dial updates automatically as they type
- **Shuffle button** — instantly loads a new random pair if the current one is not suitable
- **Save your favourites** — any pair can be saved and reloaded in future sessions
- **Flexible team setup** — supports 1 to 6 teams, or Solo/Pair mode which tracks a running total score without team competition
- **Change level mid-game** — tap the Change Level button at any time to switch difficulty without losing scores
- **Works offline** — once the page is loaded, no internet connection is required
- **No account needed** — open and play immediately

---

## Classroom Tips

**For vocabulary practice:** Ask students to explain their clue using a full sentence or situation rather than just a single word. For example, instead of saying "coffee," they should say "something you drink every morning that makes you feel like a functioning human being." This pushes them from recall into actual production.

**For rapport building:** Let students argue their case before locking in. The disagreements are where the best language happens.

**For mixed levels:** Use Easy pairs for the spectrum labels but encourage Advanced-level explanations. The difficulty is not just in the words but in how students justify their reasoning.

**For 1-on-1 coaching:** Use Solo/Pair mode. The student acts as the Psychic, you guess, then swap. Works particularly well for interview preparation and professional vocabulary.

---

## Customising the Game

You can add your own spectrum pairs directly in the game without touching the code. Just type into the Left End and Right End fields on the Psychic screen before each round. To keep them for future sessions, tap Save.

If you want to permanently add pairs to a specific level, open the `index.html` file and find the `const PAIRS` object in the JavaScript section. Each pair follows this format:

```javascript
['Left label', 'Right label', 'Optional left definition', 'Optional right definition']
```

Definitions are optional. If you add them, a ? button will automatically appear next to that label on the team screen.

---

## Technical Details

- Single file application — everything runs in one `index.html` file
- No frameworks, no dependencies, no build steps required
- Saved spectrums are stored in `localStorage` and persist across sessions
- Works on desktop and mobile browsers
- Fonts loaded from Google Fonts (Syne and Space Grotesk) — requires internet on first load for correct typography

---

## Inspiration

Based on the original Wavelength board game by Wolfgang Warsch, Alex Hague, and Justin Vickers. This is a fan-made educational adaptation built for language learning classrooms and is not affiliated with the original game or its publishers.

---

## Built By

Designed and developed for English language teaching by a Language and Culture Assistant based in Madrid, Spain.
