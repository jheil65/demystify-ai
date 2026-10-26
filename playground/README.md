# AI Playground: How to Manage It

*For Jeff. Plain steps, no coding knowledge needed.*

## What's here

The Playground lives in its own folder, `playground`, so it never touches the rest of the site.

| File | What it is | Live address |
| :---- | :---- | :---- |
| `index.html` | The Playground home page (6 game tiles) | https://jheil65.github.io/demystify-ai/playground/ |
| `finish-the-sentence.html` | Game 1: Finish the Sentence | https://jheil65.github.io/demystify-ai/playground/finish-the-sentence.html |
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
4. Use **Ctrl+F** (or Cmd+F) to find the words you want to change. In Finish the Sentence, all the game text is near the top of the `<script>` section, under the word `ROUNDS`. Change only the words inside the quotation marks.
5. Click **Commit changes**, then **Commit changes** again.
6. Wait 1–2 minutes, then refresh the live page.

If something breaks, open the file, click **History**, and you can see and restore the previous version.

## How to add a new game

Easiest: ask Claude, "Build Playground Game 2 (AI or Human?) and add it to my site." Claude will create the file, turn on its tile on the Playground home page, and send you the link.

## Ideas for later

- **Filipino language toggle:** worth adding once a native speaker can review the translation.
- **"Something confused me" link:** create a short anonymous Google Form, and Claude can add the link to each game's ending.
- **Course links:** link each game from the matching Foundations module in OpenLearning as an optional warm-up (Game 1 fits Module 2).
