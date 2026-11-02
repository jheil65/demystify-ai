# SPARK AI Intro: How to Use and Edit It

*For Jeff. Plain steps, no coding knowledge needed.*

**Live page:** https://jheil65.github.io/demystify-ai/spark-intro/

A reusable, interactive session page for nanopreneurs and micropreneurs. It works on phones and on a projector, and it keeps working if the Wi-Fi drops after it loads. Nothing a learner types is saved or sent anywhere.

## Languages

- **EN** (default): English with a little Taglish in the game examples and sample posts.
- **Taglish:** the whole page in Taglish.
- Learners tap **EN | Taglish** at the top. The page remembers their choice.
- To open straight in Taglish, use this link: `https://jheil65.github.io/demystify-ai/spark-intro/?lang=tl`

## Presenting over Zoom

1. Open the page in Chrome and click **▶ Present** (or press **P**).
2. In Zoom, share that browser tab or window.
3. Use the **arrow keys** (or the ◀ ▶ buttons, bottom right) to move between sections. Press **Esc** to exit.
4. Learners scan the QR code (large on the title section, small in the corner after that).

Tip: `https://jheil65.github.io/demystify-ai/spark-intro/?present` opens straight into Present mode.

## The 6 sections

1. You are already using AI (tap the apps you used this week)
2. What is AI? (Finish the Sentence, 3 rounds)
3. Why use AI? (4 benefits; "AI is your helper, you are still the bida")
4. How to use AI (4-part prompt builder, a clearly labeled practice preview, and links to Gemini, ChatGPT, Claude, and Copilot)
5. When to use AI (Safe or Not Safe, 7 situations, with RA 10173 and RA 8293)
6. What's next? (try it tonight, PTTC certification, SPARK AI course, AI Playground)

## How to make a small text change yourself

1. Go to https://github.com/jheil65/demystify-ai, open the `spark-intro` folder, and click `index.html`.
2. Click the **pencil icon** (Edit).
3. Press **Cmd+F** and find the words you want to change. All the text lives in the `<script>` section near the bottom:
   - `T` holds the page text, with an `en:` part and a `tl:` part. Change the matching line in both if needed.
   - `APPS` (section 1), `ROUNDS` (section 2), `BIZ`, `TASKS`, `TONES`, `PROMPT`, `PREVIEW` (section 4), and `CASES` (section 5) each have `en:` and `tl:` versions.
   - In `ROUNDS`, `probs` are [word, example percentage]. In `CASES`, `best` is the experts' answer (`safe`, `if`, or `no`) and `also` lists other answers that count as good.
4. Change only the words inside the quotation marks.
5. Click **Commit changes** twice, wait 1 to 2 minutes, and refresh the live page.

If something breaks, open the file, click **History**, and restore the previous version. Or ask Claude to make the change.
