# AI Playground: How to Manage It

*For Jeff. Plain steps, no coding knowledge needed.*

## What's here

The Playground lives in its own folder, `playground`, so it never touches the rest of the site.

| File | What it is | Live address |
| :---- | :---- | :---- |
| `index.html` | The Playground home page (6 game tiles) | https://jheil65.github.io/demystify-ai/playground/ |
| `finish-the-sentence.html` | Game 1: Finish the Sentence | https://jheil65.github.io/demystify-ai/playground/finish-the-sentence.html |
| `ai-or-human.html` | Game 2: AI or Human? | https://jheil65.github.io/demystify-ai/playground/ai-or-human.html |
| `three-audiences.html` | Game 3: Same Message, Three Audiences | https://jheil65.github.io/demystify-ai/playground/three-audiences.html |
| `whos-missing.html` | Game 4: Who's Missing? | https://jheil65.github.io/demystify-ai/playground/whos-missing.html |
| `idea-mixer.html` | Game 5: Idea Mixer | https://jheil65.github.io/demystify-ai/playground/idea-mixer.html |
| `README.md` | This guide | (not shown on the site) |

Your homepage has one button that links here ("🎮 Try the AI Playground"). Nothing else on the homepage changed.

## Ground rules for every game

- No logins, no grades, and nothing a learner types is saved or sent anywhere.
- About 5 minutes, phone-first, works on limited data.
- Filipino and Southeast Asian examples, playful but respectful.
- Ends with one "Talk about it with your group" question and a soft link to Global Learning Access.
- Honest: games simulate how AI behaves. They are not live AI, and they say so.

## How to make a small text change yourself

1. Go to https://github.com/jheil65/demystify-ai and click the `playground` folder.
2. Click the file you want to change (for example, `finish-the-sentence.html`).
3. Click the **pencil icon** (Edit) at the top right of the file.
4. Use **Ctrl+F** (or Cmd+F) to find the words you want to change. All the game text is near the top of the `<script>` section: under the word `ROUNDS` in Finish the Sentence, and under `MESSAGES` and `FIX` in AI or Human?. Change only the words inside the quotation marks. In AI or Human?, words inside `[[double brackets]]` are the clues that get highlighted. In Same Message, Three Audiences, the text is under `AUDIENCES`; each choice is written as [text, score, why], where score 2 = great fit, 1 = okay, 0 = misses. In Who's Missing?, the numbers are under `GROUPS` (each group's `total` and `came` must add up to `TOTAL` = 400 and `ATTENDED` = 120), the reasons are under `REASONS` (1 = the right answer), and the final choices are under `DECISIONS` (2 = best, 1 = partly, 0 = misses). In Idea Mixer, the points of view are under `LENSES`, and each problem under `PROBLEMS` has a `title`, a `goal` (used inside the copyable prompt), 3 `plain` ideas, and one `mix` idea for each point of view. If you add a new point of view, add a matching idea to every problem.
5. Click **Commit changes**, then **Commit changes** again.
6. Wait 1–2 minutes, then refresh the live page.

If something breaks, open the file, click **History**, and you can see and restore the previous version.

## How to add a new game

Easiest: ask Claude, "Build Playground Game 2 (AI or Human?) and add it to my site." Claude will create the file, turn on its tile on the Playground home page, and send you the link.

## Ideas for later

- **Filipino language toggle:** worth adding once a native speaker can review the translation.
- **"Something confused me" link:** create a short anonymous Google Form, and Claude can add the link to each game's ending.
- **Course links:** link each game from the matching Foundations module in OpenLearning as an optional warm-up (Game 1 fits Module 2).
