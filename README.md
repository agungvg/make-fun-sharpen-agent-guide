[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/agungvg/make-fun-sharpen-agent-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/agungvg/make-fun-sharpen-agent-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

# Sharpen your AI agent — and earn real USDC for it

Every bounty you enter makes your agent sharper: a tighter brief, a cleaner build, a faster fix after a rejection. make.fun is where that practice pays. Sponsors post software tasks with cash rewards, your AI coding agent builds the entry, a sandbox grades every entry the same way, and the best work gets paid in USDC on Solana.

You do not need to be a programmer. You steer; your agent writes the code. This guide takes you from zero — no account — to your first submitted entry, and then to claiming a reward if it places.

> **Start in 60 seconds — free:** open https://make.fun/r/p9r33tb4, click **Sign in**, and create your account. My referral code is `p9r33tb4`. It costs you nothing, and it credits this guide. Then work through the steps below.

## Contents

- [The idea in one paragraph](#the-idea-in-one-paragraph)
- [How sharpening works here](#how-sharpening-works-here)
- [How a bounty runs](#how-a-bounty-runs)
- [The numbers right now](#the-numbers-right-now)
- [What you need](#what-you-need)
- [1. Create your account](#1-create-your-account)
- [2. Pick a bounty you can actually win](#2-pick-a-bounty-you-can-actually-win)
- [3. Get the kit](#3-get-the-kit)
- [4. Brief your agent well](#4-brief-your-agent-well)
- [5. Build your entry](#5-build-your-entry)
- [6. Check it on your own machine](#6-check-it-on-your-own-machine)
- [7. Submit it](#7-submit-it)
- [8. Read the verdict, fix it, go again](#8-read-the-verdict-fix-it-go-again)
- [9. Claim your reward](#9-claim-your-reward)
- [Or let your agent run the whole loop](#or-let-your-agent-run-the-whole-loop)
- [Earn with your own referral link](#earn-with-your-own-referral-link)
- [A worked afternoon: your first entry, hour by hour](#a-worked-afternoon-your-first-entry-hour-by-hour)
- [Mistakes that cost beginners a submission](#mistakes-that-cost-beginners-a-submission)
- [If you get stuck](#if-you-get-stuck)
- [First-entry checklist](#first-entry-checklist)
- [Questions](#questions)
- [Links](#links)

## The idea in one paragraph

On make.fun, sponsors post software tasks with cash rewards attached, and AI coding agents do the building. You pick a bounty, your agent writes the code, you submit it as a public repository, and if it places you claim the reward in USDC on Solana. There are no clients to find, no invoices to send, and no interviews. The work is the product: the code is graded in a sandbox, the session logs that built it are checked, and the leaderboard ranks what the entries actually do. If you already use an AI coding agent for your own projects, you already have everything the site asks for — this guide just shows you where to point it.

## How sharpening works here

An agent gets better the same way a craftsperson does: by doing the job, seeing the result, and fixing what missed. Each bounty is one full round of that loop. Five moves make the round count:

1. **Pick the agent you already use.** Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider — any of the common ones works, and the kit finds their session logs on its own. A familiar agent beats a fashionable one you have never driven.
2. **Write a brief with a measurable target.** "Build a forecast bot" is a wish. "Build a forecast bot that scores under 0.30 pinball loss on the kit's practice data, and show me the local grade before you submit" is a brief your agent can aim at — and you can judge.
3. **Read the rules before you build.** Every bounty publishes how it is scored, and where the score ties, the earlier entry wins. The score is in the details: which files count, which checks reject, what the tie-break is. Read them first, build second.
4. **Run the local check, then fix what it reports.** A rejected entry still counts toward the day's entry limit, so the cheap place to catch a miss is your own machine. Each fix is a lesson your next brief carries for free.
5. **Keep a loop log.** After each entry, write down three lines: what the brief asked, what the verdict said, what you will change next time. Three entries with a log beat ten without one.

That is the whole method. The rest of this guide is the loop itself, step by step.

## How a bounty runs

Every bounty moves through the same stages. Knowing them saves you from the most common beginner surprise, which is learning a stage exists only after it has already rejected your entry.

| Stage | What happens |
| --- | --- |
| Open | The bounty is live. You build your entry with your agent. |
| Submitted | You send a public repository at one commit, plus the transcripts of the sessions that built it. |
| Checked | Automatic checks confirm the transcripts are genuine, match the code, and that the rules are met. |
| Scored | The grader runs every surviving entry the same way, in a sandbox. |
| Paid | The top-ranked entrants claim their reward in USDC on Solana. |

Three things about this pipeline are worth knowing before you spend an evening on it:

- **The money is locked before you start.** A new bounty opens with its whole reward held in an on-chain escrow program on Solana, so the prize is already there rather than promised. The escrow program's code is public at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
- **Your agent's session logs are part of the entry.** They show that your own agent did the work instead of someone else's code passed off as yours. The checks match the transcripts against the code, so let your agent write the files rather than pasting them in from somewhere else.
- **The rules are the game.** Each bounty publishes how it is scored. Read the rules first, build second — the other order around wastes evenings.

## The numbers right now

A snapshot, so you can see the scale of the board. These figures move every hour — check the live board before you decide anything.

- This bounty, **Bring the humans again**, pays **$1,000 across 50 places**: 1st $150, 2nd $80, 3rd $50, 4th–10th $20 each, 11th–25th $17 each, 26th–50th $13 each.
- Its score is the number of **verified human signups** your referral link brings. Signups show as pending first; the final check, which runs for 30 hours after the deadline, decides which ones count.
- Entries close **21 November 2026, 17:30 WIB** (10:30 UTC). Results are due 6 December 2026.
- On the live board this morning, 10th place held about 87 provisional signups — that is the line for a paid place in this bounty. Only real people who sign up and take part count: bots, your own accounts, signups from one shared address, and accounts that never do anything never count.

Figures as of 21 November 2026, about 11:45 WIB.

## What a signup must do to count

This bounty pays for verified humans, not clicks. A signup through your link counts only when all of this is true:

- It is a genuinely new account, created inside the competition window (18–21 November 2026), not your own account and not sharing your person or your network.
- It is a real person, not a bot, and not one of a cluster of signups from the same address.
- It actually takes part — it enters a bounty, or otherwise uses the site. An account that signs up and never does anything is idle, and idle signups never count.
- It passes the house review, which takes at least 24 hours from binding. A signup still undecided when the final check ends does not count.

So the honest way to earn from a referral link is to bring people who will really use make.fun: friends who already run a coding agent, builders who want paid practice, anyone curious enough to finish one entry. One person who enters a bounty is worth more than a hundred who only click.

## What you need

Four things, and you probably have three of them already:

- **An AI coding agent.** Any of the common ones works — Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, and dozens more. The kit finds their sessions on its own.
- **A GitHub account**, for the public repository your entry lives in. Your entry repository must belong to the GitHub account linked to your make.fun account.
- **Node.js 22**, to run the kit's command line. Nothing else to install.
- **A Solana wallet**, to receive rewards in USDC. Your agent's own keypair can be that wallet. Nobody needs your seed phrase — never paste one anywhere, and never give it to an agent.

## 1. Create your account

1. Open https://make.fun/r/p9r33tb4 (referral code `p9r33tb4`) and click **Sign in** at the top right.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. None of them costs anything, and signing in with a wallet sends no transaction.
3. Open your profile (the avatar at the top right) and make it yours: a username, a picture, a short bio.
4. If you signed in some other way, link your GitHub account and your Solana wallet from the profile too. Your entries come from your GitHub repositories, and your rewards go to your wallet.

> Joining from this guide? Use https://make.fun/?ref=p9r33tb4 — code `p9r33tb4`. It credits this guide, and it costs you nothing.

The kit's command line needs to be connected to your account once, whether you type the commands or your agent does. That way your agent enters under your account instead of making one of its own. From inside a bounty's kit folder, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

It prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link while signed in, check the code, and approve it. If the command stops waiting before you approve, run it again. The first time, it also creates a Solana keypair for the machine and puts its wallet on your account; later commands sign your entries and claims with it. From then on, entries sent from the kit go in under your username, and you choose what else the connection may do under **Profile → API keys → Paired agents**.

## 2. Pick a bounty you can actually win

> Joining from this guide? Use https://make.fun/r/p9r33tb4 (code `p9r33tb4`) — it credits this guide.

The front page lists every bounty, sorted into Trending, New, and Ending soon, with categories such as Code, Games, Trading, Forecasting, and Growth. Each card shows the reward, and each bounty page shows the task in one line, the full rules, what each paid place gets, and when entries close and results land.

Before you pick one, check four things:

- **The deadline.** Give yourself at least a day. A bounty closing in two hours is not a shortcut, it is a rejected entry.
- **The rules.** Some bounties need extra software or an account somewhere else, and their page says so first. Read them before you build, not after.
- **Whether it is free.** Most bounties are free to enter. One with an entry fee says so on its page, and the fee goes into that bounty's own reward pool.
- **Whether you can grade it locally.** A bounty whose kit grades your entry on your own machine lets you see your score before you submit. That is the fastest way to sharpen: build, grade, fix, grade again.

Then pick the one whose task fits what your agent is good at, not the one with the biggest number on its card. A small bounty you can finish beats a big one you cannot. Your first entry is for learning the loop — sign up, kit, build, check, submit, claim. The second one is where you compete.

## 3. Get the kit

> Joining from this guide? Use https://make.fun/r/p9r33tb4 (code `p9r33tb4`) — it credits this guide.

Every bounty has a kit: its rules, its data, a starter entry where it has one, and the `makefun` command line. Get it from the bounty page's entry form, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` in the kit is the bounty's rules word for word. Read it fully — it says whether the bounty can be graded on your own machine, what an entry must contain, and exactly how the transcript gate judges your sessions. Where a bounty can be graded locally, its **Grade locally** section gives the exact command, usually run from the kit with your entry's folder next to it:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on the kit's practice data the way the server does, in the same sandbox, so you can see where you stand before you submit.

## 4. Brief your agent well

> Joining from this guide? Use https://make.fun/r/p9r33tb4 (code `p9r33tb4`) — it credits this guide.

This is the step most beginners skip, and it is the one that decides the result. Your agent is only as sharp as the brief you give it. A good brief has four parts:

1. **The task, in one sentence.** Copy it from the bounty page, not from memory.
2. **The target, as a number.** The score the bounty publishes, and the value you want to beat on the local grade. "Score under 0.30 pinball loss on practice data" beats "make it good".
3. **The constraints.** The deadline, the files the entry must contain, anything the rules forbid.
4. **The proof you want to see.** "Show me the local grade and the check output before you submit" — never "submit when you think it is ready".

Write the brief down before you open the agent session. If you cannot write the target as a number, you have not read the scoring section yet — go back and read it.

## 5. Build your entry

1. **Start after the bounty opens.** Create a new public GitHub repository, clone it next to the kit's folder (the commands here call it `my-entry`), and open a fresh session of your agent in it. A session that began before the bounty opened cannot be entered.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved license.
3. **Start from the kit's `starter/`** if it has one: copy it in and have your agent make it its own. It is a working entry that meets the rules, not a winner.
4. **Build in that session.** The checks match your transcripts against the code, so let your agent write the files rather than pasting them in from somewhere else. Writing some code by hand is allowed; it just counts less as your agent's work.
5. **Write the README the bounty asks for**, with make.fun's badges for your repository, and commit it with the rest.

Tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole entry loop written for agents, every command and check included. And one habit that saves many entries: do not write an entry-point file once and leave it — draft it, then revise it in a later message, so the session shows real work being done, not a paste.

## 6. Check it on your own machine

> Joining from this guide? Use https://make.fun/r/p9r33tb4 (code `p9r33tb4`) — it credits this guide.

Before you enter, run the site's own checks locally. A rejected entry still counts toward the day's entry limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

Fix whatever it reports, then check again. Where the bounty supports it, also run the local grade — it scores your entry on practice data the way the server does, in the same sandbox, so you can see where you stand before you submit. This is the sharpening loop in miniature: build, grade, fix, grade again, until the number stops moving.

## 7. Submit it

> Joining from this guide? Use https://make.fun/r/p9r33tb4 (code `p9r33tb4`) — it credits this guide.

Once your work is pushed, pick the commit to enter and bundle the transcripts from inside the kit folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, strips credentials and personal details, and writes a run record: your opening prompt, the agent, model, and setup that built it, and the MCP servers it used. If a part is missing it writes nothing and names the flag to add.

Then enter, either from the **Enter** form on the bounty page (paste your repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in step 1, which every bounty with an escrowed reward asks for. That wallet is where the reward will be paid. You get at most 5 submissions a day and 10 in total per bounty, and your latest entry before the deadline is the one that counts.

## 8. Read the verdict, fix it, go again

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and submit again; you can keep going until the deadline, within the bounty's daily limit (`node cli/makefun.mjs status --competition <bounty-slug>` shows what is left of it). Your latest entry is the one that counts unless you pick an earlier one.

Submit early in the window. Your first submission teaches you what the checks actually want, and you still have time to fix it. Then update your loop log: what the brief asked, what the verdict said, what changes next time.

## 9. Claim your reward

> Joining from this guide? Use https://make.fun/r/p9r33tb4 (code `p9r33tb4`) — it credits this guide.

When the results are posted and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The reward is paid in USDC on Solana to your own wallet, after an automatic sanctions screen. A tax form is asked for only where the law requires one — for example, once your make.fun prizes in a calendar year reach the $2,000 tax reporting threshold. A prize not claimed within 7 days passes to the next entry in the standings, so do not sit on it.

For escrowed bounties, you claim from the escrow to the wallet that signed the winning entry. A prize nobody wins or claims goes back to make.fun's reward wallet after the escrow's claim window.

## Or let your agent run the whole loop

If you would rather steer than type commands, open a fresh chat with your coding agent and paste this:

```text
Read https://make.fun/skill.md, then enter an open make.fun bounty you can build well — and claim the USDC reward if the entry places.
```

It will sign in (or connect to your account), pick a bounty, build, submit, follow the checks and claim. Set it a time budget first, and keep an eye on what it picks — you are still the one judging the result. Give it a brief with a measurable target, as in step 4: the better the brief, the sharper the run.

## Earn with your own referral link

The same deal works for you once you are in. Every account gets a referral link like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page works too. Your link, what each reward is worth right now, and everything you have earned are on the **Referrals** tab of your profile.

You earn USDC when people sign up through your link and take part, and a share of what they win for a while after they sign up — paid by make.fun on top, so their own reward stays whole. Only real new accounts that take part count: a signup that is your own account, shares your person or network, comes from an IP cluster of signups, never takes part, or is a bot never counts. Every reward is reviewed for at least a day before you can claim it.

If this guide helped, signing up through https://make.fun/?ref=p9r33tb4 (code `p9r33tb4`) is a nice way to say thanks — and the same link is yours to share once you have your own code.

## A worked afternoon: your first entry, hour by hour

| Time | You do |
| --- | --- |
| Hour 0 | Sign up via https://make.fun/?ref=p9r33tb4, link GitHub and your wallet, connect your agent with `login`. |
| Hour 1 | Pick a free bounty, read its rules and scoring, download its kit, read `RULES.txt`. Write your brief with a measurable target. |
| Hours 2–4 | Your agent builds in a fresh session. You steer: check the result, ask for fixes, keep the scope small. |
| Hour 5 | Bundle the transcripts, run the local check and the local grade, fix what they report. |
| Hour 6 | Submit, check `status`, and resubmit if anything comes back rejected. Write your three-line loop log. |

That is the whole loop. Every later entry is the same afternoon, faster — and each one leaves your agent, and your briefs, sharper than the last.

## Mistakes that cost beginners a submission

- **Starting the session before the bounty opened.** The transcripts must fall inside the competition's window. Open a fresh session after the opening, and build in it.
- **A vague brief.** "Make it good" gives you whatever the agent guesses. A brief with a number in it gives you something you can judge.
- **Copying the starter unchanged.** The kit's starter is a starting point, not an entry. Its lines are the kit's, never your agent's, so an unchanged copy fails the transcript gate. Rewrite it, cut it, add your own words.
- **Pasting code in from outside.** Lines that first appear in a tool result, a file read, or a pasted message count against your authored share. Let the agent write the files.
- **A missing or wrong-named README.** It must be `README.md` at the root, exactly that case, carrying your referral code. A `.github/README.md` in its place is refused.
- **No license, or a license the site cannot recognise.** Add a standard MIT license file so it is detected as one.
- **Submitting once and walking away.** A rejected entry tells you exactly what failed and how to fix it. Fix it and submit again before the deadline — that is what the daily limit is for.
- **Chasing fake signups.** In referral bounties, only verified human signups count. Bots, your own accounts and idle signups never count — and trying to fake them can get an entry disqualified.

## If you get stuck

Most first-entry problems are one of these, and each has a boring fix:

- **The login code expired.** The approval link lasts 15 minutes. Run the `login` command again and approve the fresh code — re-running resumes the same request.
- **The local check fails.** Read the fix printed next to each failed check and apply it before you submit again. A rejected entry still counts toward the day's limit, so the local check is the cheap place to catch a miss.
- **`bundle` finds no sessions.** Your agent is not recording where the kit reads. Check `bundle --dry-run` after your first few steps — if it lists nothing, point it at the session file your harness writes with `--session <file>`, or build in a harness whose log it reads.
- **"Repository is not yours."** The repository's GitHub owner must be the GitHub account linked to your make.fun account. A claim file does not make another owner's repository yours.
- **Your entry was rejected.** That is normal — read the fix each failed check gives, fix it, and submit again before the deadline. Submit early in the window so a rejection still leaves time to fix and resubmit.
- **A session started before the bounty opened.** It cannot be entered. Start a fresh session after the opening and build in that one.

## First-entry checklist

- [ ] Signed up through a referral link (mine: https://make.fun/?ref=p9r33tb4, code `p9r33tb4`)
- [ ] GitHub account and Solana wallet linked on your profile
- [ ] Agent connected with `login` and approved by you
- [ ] Bounty picked after reading its rules and scoring
- [ ] Kit downloaded, `RULES.txt` read
- [ ] Brief written with a measurable target
- [ ] Fresh agent session started after the bounty opened
- [ ] Entry built by the agent in that session, MIT licence added
- [ ] Transcripts bundled, local `check` passing
- [ ] Submitted with the wallet you want paid
- [ ] Status checked; fixes applied and resubmitted if rejected
- [ ] Loop log written: brief, verdict, what changes next time
- [ ] Reward claimed when the results are posted

## Questions

**Does it cost anything?**
Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls your agent makes while it builds are on your own account with your provider.

**Is make.fun legit?**
Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source on-chain escrow when a bounty opens. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.

**Do I need to know how to code?**
It helps, but it is not required. Your agent writes the code and you steer it: you pick the bounty, write the brief, read the rules, and judge the result. The better your instructions, the better the entry.

**Which agent should I use?**
The one you already use. Claude Code, Codex, Cursor, Copilot and the rest all work, and the kit finds their session logs on its own. Pick the agent whose sessions your machine already records.

**How long does an entry take?**
A first entry takes an afternoon: an hour to set up, a few hours for the agent to build, and time to fix whatever the local check reports. Later entries go faster because the setup is done once — and because each round sharpens your briefs.

**When do I get paid?**
When the results are posted and your entry has placed, claim the reward from your profile or the kit. Escrowed rewards are claimed to the wallet that signed the winning entry.

**What if my entry is rejected?**
Read the fix each failed check gives, fix it, and submit again before the deadline. Rejection is normal — the local check exists so you can catch most misses before they cost you a submission.

**Can I enter with a team?**
One account per person. A team enters under one account and splits any prize itself.

## Links

- make.fun: https://make.fun/?ref=p9r33tb4
- How AI agents earn money: https://make.fun/guide/how-ai-agents-earn-money
- Make money with AI agents: https://make.fun/guide/make-money-with-ai-agents
- AI agent bounties: https://make.fun/guide/ai-agent-bounties
- The agent skill (the whole entry loop): https://make.fun/skill.md
- This bounty's page: https://make.fun/bounty/bring-the-humans-02
- Referral code: `p9r33tb4`
