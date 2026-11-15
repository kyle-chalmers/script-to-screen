# Script to Screen Workbook

This is your step-by-step guide for the workshop and for every video after it. Part 1 is the day itself. Part 2 is finishing and posting your video at home. Part 3 is a weekly routine you can keep using.

A few words you'll see:

- **Claude desktop app**: the Claude program you install on your computer.
- **Cowork**: a tab in the Claude desktop app where Claude can open and save files in a folder you choose.
- **Chat**: the regular Claude conversation, in the app or at claude.ai in your browser.
- **Skill**: a saved set of instructions that teaches Claude one job. This workshop uses three.
- **Plugin**: a package that adds skills to Claude.
- **Dictation**: your computer or phone typing what you say out loud.
- **Take**: one short piece of your script that you record in one go.
- **Task**: what Cowork calls one conversation. "Start a new task" means the same as "start a new chat".

# Part 1: The day

## Before you start

Check these off before the workshop, or during setup at the start.

- [ ] Install the Claude desktop app and sign in. A paid plan (Pro or higher) is recommended so you can use Cowork. On the free plan you can follow along with copy and paste.
- [ ] Add the workshop tools: **Customize** > **Plugins** > **Add marketplace** > enter `kyle-chalmers/script-to-screen` > **Install**. If you're on a company Claude account and this is blocked, use a personal account.
- [ ] Test talking to type: click in Claude's message box, start dictation (Mac: press the Fn (Globe) key twice; Windows: Windows key + H), and say one sentence. If nothing happens on a Mac, open System Settings > Keyboard > Dictation and turn it on.
- [ ] Make a folder called **My Videos** on your desktop.
- [ ] On the morning of the workshop, get the newest version: **Customize** > **Plugins**, open the script-to-screen marketplace, and choose **Check for updates**.
- [ ] Write your topic in one sentence. If you're stuck, use the question customers ask you most.
- [ ] Bring a laptop and charger, a phone with room for a few minutes of video, earbuds with a mic if you have them, and something to prop your phone at eye level.
- [ ] Optional head start: answer the four questions in Step 1 out loud as a voice memo on your phone.

If the plugin won't install, you can still do everything. See "The paste path" at the end of Step 1.

## Step 1: Capture your story

You'll work with a partner. One of you talks while dictation types into Claude, then you swap.

### What you do

1. Sit facing your partner. Decide who goes first. That person is the speaker.
2. Open Claude. In Cowork, pick your My Videos folder as the folder Claude works in. In chat, start a new chat.
3. Type the words below and press send.
4. When Claude asks for your topic, type it in one line.
5. Claude asks four questions, one at a time. For each one, start dictation and answer out loud, looking at your partner. Talk the way you'd talk to a customer.
6. When you finish an answer, stop dictation and press send. Don't tidy it up first.
7. Type your answer to the last question, the words you'd never say.
8. Check what Claude shows you, and answer its question.
9. Swap, and your partner takes a turn.

### What you say to Claude

```
capture my story
```

### The four questions

Read these now so you can think ahead.

1. What problem does your customer have that this video helps with?
2. Tell me about one real time you saw it happen. No names needed.
3. What should they know or do after watching?
4. If a customer walked up right now, how would you start? Say it the way you'd say it.

Then one question you can type: What are 2 or 3 words or phrases you'd never say to a customer?

Long, messy answers work best. Leave in the "um"s and the restarts. Claude saves your answers exactly as you said them, because they're the sample of how you really talk. For question 2, tell one real time, with the detail only you would know, like what you saw when you walked in and what the customer said.

### How to dictate

- **Mac**: click in Claude's message box, then press the Fn (Globe) key twice.
- **Windows**: click in Claude's message box, then press the Windows key + H.
- **Phone**: tap the microphone on your keyboard.

Hold your earbud mic close to your mouth if the room is loud. Talk to your partner, not to the screen.

### What you should see

After your answers, Claude shows your opening line and your real story back to you, word for word, plus a suggested order. It looks like this (from the [pool service example](examples/tuesday-pool-care/)):

```
Here's what I heard. Please check it.

Your opening line (your words):
"hey, if your pool turned green right after a storm, you probably didn't do anything wrong."

Your real moment (your words):
"I get there Tuesday, that's her day, and the water is, I mean it was pea soup,
I couldn't see the bottom step. And she's standing there like, I didn't touch
anything. And she didn't! ..."

Order I suggest:
1. The opening line: you probably didn't do anything wrong
2. The real moment: pea soup, and the timer off by four and a half hours
3. What to do: check the timer, dump the skimmer basket
4. The ask: if it's already green, call me

Are these your words and your order?
```

If they're your words, say yes. If anything is off, say what to change. Claude saves nothing until you say yes.

Then it saves two files in a new folder for this video, `answers.txt` and `brief.txt`, and adds your answers to `voice.txt` in My Videos.

### If you get stuck

- **Dictation won't start, or types nonsense.** Have your partner type while you talk. If you recorded a voice memo at home and your phone made a transcript of it, you can paste that instead.
- **Claude doesn't seem to know "capture my story".** The plugin isn't installed. Use the paste path below.
- **Claude says it can't save files.** That's fine. It prints each file with its name on the line above. Copy each one into a plain text file with that name (on a Mac, TextEdit needs Format > Make Plain Text first; on Windows, use Notepad). `voice.txt` goes in My Videos, and the others go in a new folder inside it named with today's date and your topic.

### The paste path

If the plugin won't install, you can use any chat:

1. Open the skill on GitHub (the website where these files live): [capture-story](skills/capture-story/SKILL.md), [draft-script](skills/draft-script/SKILL.md), or [check-script](skills/check-script/SKILL.md).
2. Click the copy button at the top right of the file (two overlapping squares, labeled "Copy raw file").
3. Start a new chat and paste it in.
4. Then say what you want, for example "capture my story".

Do this once for each step, with the skill for that step.

## Step 2: Draft your script

### What you do

1. In Claude, type the words below. In a new chat, Claude may ask you to paste your files. Paste `brief.txt`, `answers.txt` and `voice.txt`, one at a time.
2. Claude shows an outline first. Read it. Your order wins over Claude's.
3. Say yes, or say what to move.
4. Claude writes the script in short numbered takes and saves it as `script.txt`.
5. If you see `[ask: ...]` in the script, Claude needed a fact you didn't give. Answer it out loud and Claude puts your answer in, in your words.

### What you say to Claude

```
draft my script
```

To change the order of the outline:

```
Move the story to the top, before the opening line.
```

### What you should see

The outline comes first, and nothing else is written until you say yes:

```
Here's the plan before I write anything.

1. Open: "hey, if your pool turned green right after a storm, you probably
   didn't do anything wrong."
2. The real moment: the pea-soup pool and the timer off by four and a half hours.
3. What to do: check the timer, dump the skimmer basket.
4. The ask: if it's already green, call me.

Is this the order you want? Say yes, or tell me what to move.
```

After your yes, the script arrives as Take 1, Take 2 and so on, about 40 words each, 120 to 170 words in all. That's 60 to 90 seconds out loud. The word count is at the bottom. See the [example script](examples/tuesday-pool-care/script.txt).

### How to ask for changes

Name the lines you want changed. Claude changes only those lines and shows you before and after.

```
change these lines: take 3 sounds stiff. I'd say "those old timers just stop when the power goes out."
```

You can also open `script.txt` (a double-click opens it), type a note in square brackets starting with `me:` next to the line, save it, then tell Claude "change these lines". For example: `[me: I'd never say "ensure", I'd say "make sure"]`.

### If you get stuck

- **The script is over 170 words.** Say "cut one take". Claude tells you which one it would cut and asks first.
- **Claude made something up.** Name the line and say "I never said that, take it out."

## Step 3: Check it in a fresh chat

### Why a fresh chat

The chat that wrote your script reads right past its own habits, the same way it's hard to proofread your own email. A brand-new chat reads your script cold and catches what the first one missed.

### What you do

1. Open a new chat. In Cowork, start a new task. Don't use the chat that wrote the script.
2. Type the words below. If Claude asks, paste `script.txt`, `answers.txt` and `voice.txt`, one at a time.
3. Read the report.
4. Decide what to do with each finding.
5. Make your changes.

### What you say to Claude

```
check my script
```

### What you should see

A short report, saved as `check.txt`. Here's part of the one from the pool example:

```
Check: 2026-08-12 green pool after a storm
Verdict: Close. One promise to confirm and three lines that sound written.

1. "Already green? Call Tuesday Pool Care today for a free post-storm checkup."
   Question: The script says you offer a free post-storm checkup. True? ...

2. "It's not your chemicals. It's your timer."
   What it is: a this-not-that turn, and choppy. ...
   Try this, from your own words: "You think you messed up the chemicals,
   and usually you didn't. ..."

Read it aloud once more before you record.
```

### How to read the report

- The top line is the verdict: how close the script is to sounding like you.
- Then up to 7 findings, the most important first. Each one quotes your line, says what's wrong in plain words, and offers a fix built from your own answers.
- When a line might not be true, the report asks you a question instead. Answer it honestly. If it isn't true, cut it, because you'd be saying it on camera.
- The check never flags something you actually said. Your own way of talking always wins.

### You decide each finding

For every finding, you can keep your line, take the suggestion, or write your own. The check never changes your script. To make the changes, either:

- open `script.txt` and edit the lines yourself, or
- go back to the chat that wrote the script and say "change these lines", naming each one.

### If you get stuck

- **Claude says it helped write this script.** You're in the drafting chat. Open a new chat and try again.
- **You're running out of time.** Skip the check and go to Step 4. Getting your video recorded comes first.

## Step 4: The out-loud test

Your script was written to be heard, so test it by ear.

### What you do

1. Open the stopwatch on your phone.
2. Start it and read the whole script to your partner, the way you'd say it to a customer.
3. Stop the stopwatch at the end. Aim for 60 to 90 seconds.
4. Ask your partner where you stumbled or sounded like you were reading. Mark those lines.
5. Tell Claude only those lines, in the chat that wrote the script.
6. Read it to your partner once more.

### What you say to Claude

```
change these lines: take 4, I keep tripping on "the way the little arrow points". I'd say "turn it the way the arrow goes".
```

### What you should see

Claude changes only the lines you named, shows before and after, and gives the new word count.

### If you get stuck

- **You ran over 90 seconds.** Say "cut one take".
- **You trip on the same line twice.** Look away from the screen and tell your partner what you meant. Dictate what you just said into Claude and ask it to use those words for that line.

## Step 5: Record

### Set up

1. Prop your phone at eye level. Decide upright or sideways, and keep it the same for every take.
2. Put your laptop, with the script open, directly behind the phone. Your eyes stay close to the lens while you read.
3. Face a window or a light, so the light is on your face.
4. Plug in earbuds with a mic if you have them.
5. Have your partner sit right beside the phone. They're your audience.

### Record

1. Record one numbered take at a time.
2. Say it to your partner, not to the lens.
3. If you flub a line, keep going to the end of the take. Then redo only that take.
4. When every take is done, try one full run from start to finish.

### What you should see

One short clip per take in your phone's photos, plus a full run if you tried one. The clips for each take count as your finished piece. Joining them is Part 2.

### If you get stuck

- **The room is noisy.** Hold the earbud mic close to your mouth and face a wall.
- **Your phone is out of space.** Delete a few old videos you've already saved somewhere else, or record on your partner's phone and have them send you the clips.
- **Nerves.** Record Take 1 three times and keep the best. Your first try is usually the stiffest one.

## What you have now

- [ ] `voice.txt` in your My Videos folder
- [ ] `answers.txt` in your video's folder
- [ ] `brief.txt` in your video's folder
- [ ] `script.txt` in your video's folder
- [ ] `check.txt` in your video's folder, if you got to the check
- [ ] One clip per take on your phone
- [ ] One full run on your phone, if you tried one

# Part 2: Finish and post

Do this at home when you have about 30 minutes. Use the free video editor already on your phone or computer. You don't need to buy anything.

1. **Gather your clips.** Keep them on your phone, or move them to your computer if you'd rather edit on a bigger screen.
2. **Join your takes.** Open your video editor, start a new project, and add the clips in order: Take 1, Take 2 and so on. Use `script.txt` as your list. If your full run came out well, you can use that one clip instead.
3. **Trim the start and end.** Cut the second before you start talking and the moment you reach for the phone at the end. Do this for every clip, so the takes flow into each other.
4. **Add captions.** Captions let people follow along with the sound off. If your editor can make captions for you, check every word against `script.txt`, especially your business name and any local place names. If it can't, type them in. Your script is already the caption text.
5. **Export.** Save the finished video at the highest quality your editor offers. Watch it once all the way through on your phone before you post.
6. **Post.** Put it where your customers already see you. In the post text, write one or two sentences in your own words about what to do after watching. The "What to do after" part of `brief.txt` is a good start.

Kyle's own process does this part (editing, captions and uploading) with Claude Code, the version of Claude that works with files on your computer. That's beyond today's session.

# Part 3: The weekly loop

Once you've done it once, a video takes about 30 minutes a week. Pick a regular time and keep it.

1. **Pick a question (2 minutes).** Think of a question a customer asked you this week. Write it as one line. That's your topic.
2. **Capture (10 minutes).** Say "capture my story". Answer the four questions out loud. Approve your words and your order.
3. **Draft (5 minutes).** Say "draft my script". Approve the outline, then read the script.
4. **Check (5 minutes).** Open a new chat and say "check my script". Decide each finding.
5. **Read it aloud (3 minutes).** Read it out loud to someone, or to yourself, with a timer. Change only the lines that sound stiff.
6. **Record (5 minutes).** Record one take at a time, then try a full run.

Edit and post when you have time, using Part 2.

### Why it gets easier each week

Every time you say "capture my story", Claude adds your newest answers to `voice.txt` and updates its notes on how you talk. It keeps your newest five sets of answers, so the file stays short and keeps up with how you talk now. Your "never say" words carry over too, and you can add to them each time.

The more you talk, the more of your voice Claude has to work with. Keep a note on your phone of the questions customers ask you. That's your list of topics for the next few months.

## Where to find this again

Everything from today lives at [github.com/kyle-chalmers/script-to-screen](https://github.com/kyle-chalmers/script-to-screen): the three skills, this workbook, and the [pool service example](examples/tuesday-pool-care/).
