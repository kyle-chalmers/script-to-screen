# Script to Screen

Script to Screen is three small skills for Claude that help you make a short video script that sounds like you. A skill is a saved set of instructions that teaches Claude one job. The idea is talk first, AI second: you tell your story out loud, and Claude builds the script from your own words, then a fresh chat checks the draft for writing habits that don't sound like you. Kyle Chalmers ([kclabs.ai](https://kclabs.ai)) built it for the Script to Screen workshop.

## What you end up with

One folder on your computer, with one folder inside it per video:

```
My Videos/
  voice.txt                      notes on how you talk, plus your newest spoken answers
  2026-12-04 why your AC freezes/
    answers.txt                  your answers, exactly as you said them
    brief.txt                    the plan: your opening line, your story, the order
    script.txt                   the script, in short numbered takes
    check.txt                    the check report on your script
```

Every file is a plain `.txt` file, so it opens with a double-click on any Mac or PC.

## Install

Pick the path that matches how you use Claude. A plugin is a package that adds skills to Claude, and a marketplace is a list of plugins someone shares.

### Path A: Claude desktop app or claude.ai (Cowork and chat)

Cowork is a tab in the Claude desktop app where Claude can open and save files in a folder you choose. Chat is the regular Claude conversation, in the app or in your browser.

1. Open the Claude desktop app, or go to claude.ai in your browser, and sign in.
2. Go to **Customize**, then **Plugins**.
3. Choose **Add marketplace**.
4. Enter `kyle-chalmers/script-to-screen` and confirm.
5. Find **script-to-screen** in the list and choose **Install**.

Good to know:

- A paid Claude plan is recommended.
- If you sign in with a company Claude account, your company may block adding a marketplace. Use a personal account instead.
- If adding the marketplace doesn't work, download these files as one ZIP file instead. Go to the [project page on GitHub](https://github.com/kyle-chalmers/script-to-screen) (the website where these files live), choose **Code**, then **Download ZIP**. Then in **Customize** > **Plugins**, choose **Add** > **Upload plugin** and pick the ZIP file.

### Path B: Claude Code

Claude Code is the version of Claude that works with files and folders on your computer, in the Code tab of the desktop app or in a terminal.

1. Type this and press Enter:
   ```
   /plugin marketplace add kyle-chalmers/script-to-screen
   ```
2. Type this and press Enter:
   ```
   /plugin install script-to-screen@script-to-screen
   ```
3. Start a new session so the skills load.

### Path C: No install (any chat app)

1. Open the skill you need on GitHub:
   - [capture-story](skills/capture-story/SKILL.md)
   - [draft-script](skills/draft-script/SKILL.md)
   - [check-script](skills/check-script/SKILL.md)
2. Click the copy button at the top right of the file (two overlapping squares, labeled "Copy raw file").
3. Open a new chat in any AI app and paste it in.
4. Then say what you want, for example "capture my story".

If the chat can't save files, Claude prints each file with its name on the line above. Copy each one into a plain text file with that name. `voice.txt` goes in My Videos, and the others go in a folder inside it named with today's date and your topic.

## Use it

Say these three things, in this order:

1. **"capture my story"**: Claude asks four questions, one at a time, and you answer out loud with dictation (your computer typing what you say). It shows your opening line and your real story back to you word for word. You approve them before anything is saved.
2. **"draft my script"**: Claude shows an outline first. You approve the order, then it writes the script in short numbered takes you can record one at a time.
3. **"check my script"**, in a NEW chat (or a new task in Cowork): Claude reports lines that don't sound like you, each with a suggested fix from your own words. It never changes your script. You decide each one.

Then read the script out loud with a timer and record it one take at a time.

## Learn more

- [WORKBOOK.md](WORKBOOK.md) walks through the whole process step by step, from setup to posting.
- [examples/tuesday-pool-care](examples/tuesday-pool-care/) shows every file for one made-up pool service, including a first draft and the check that caught its problems.

## Your files and your privacy

Your files save on your computer. What you say or paste is sent to the AI app you are using, like any chat, so leave out customer names and anything you would not want to share. These skills send nothing anywhere else.

## License

MIT. See [LICENSE](LICENSE).
