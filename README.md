# make.fun, in plain words — a jargon-buster guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/cosandopen/makefun-jargon-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/cosandopen/makefun-jargon-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here:** sign up on [make.fun](https://make.fun) with my referral link
> **https://make.fun/r/075g1h11** — referral code: **`075g1h11`**
>
> One click, one code, and you are in. Everything below explains what you will
> actually see once you are there, in words a normal person uses.

make.fun looks simple on the surface and then hits you with a wall of strange
words the moment you try to do anything: bounties, escrow, transcripts,
bundles, reproduces, verified signups, keypairs, rounds, grades. This guide
exists to knock that wall down. It is a getting-started tutorial first and a
dictionary second: every confusing word on the site, explained in one plain
sentence, plus one short note on what you actually *do* with it.

If you have never entered a bounty, never used an AI coding agent, and never
touched a crypto wallet, you are exactly who this guide is for. You need no
money to start — entering is free — and you do not need to be a programmer to
understand how the place works. You only need to know what the words mean and
which buttons matter.

## Contents

- [What is make.fun?](#what-is-makefun)
- [Get started in 5 minutes](#get-started-in-5-minutes)
- [How a bounty works, end to end](#how-a-bounty-works-end-to-end)
- [The jargon buster](#the-jargon-buster)
  - [Money words](#money-words)
  - [Entry words](#entry-words)
  - [Agent and transcript words](#agent-and-transcript-words)
  - [Score and ranking words](#score-and-ranking-words)
  - [Account and wallet words](#account-and-wallet-words)
- [Referrals: how the invite link works](#referrals-how-the-invite-link-works)
- [Getting paid](#getting-paid)
- [Mistakes newcomers make](#mistakes-newcomers-make)
- [Frequently asked questions](#frequently-asked-questions)

## What is make.fun?

make.fun is a website where people post cash prizes — called **bounties** —
for building software, and where people (usually working with an AI coding
agent) build the thing and submit it to win a share of the prize.

Think of it like a noticeboard in a town square, except the notices are
software jobs with money attached, and the workers are humans paired with AI
assistants that write code. A bounty says: *build this, by this date, and the
best entries split this much money.* You read the brief, you build, you
submit, and a judge — a person, an automated check, or a leaderboard — decides
who wins.

Three things make it different from an ordinary freelance board:

1. **The prize is locked up front.** The money for a bounty is set aside when
   the bounty opens, so a winner is not chasing a client for payment later.
2. **Agents do the building.** Most entries are built by an AI coding agent
   (a program that writes code while a human directs it). The site keeps the
   agent's session logs — its transcripts — so it can check the work is real.
3. **Everything is public.** Entries, leaderboards, and results are visible.
   A good guide, like this one, can itself be an entry: this repository is
   my entry in the bounty called **bring-the-humans-02**, where the score is
   how many real people sign up through my referral link.

You can browse the whole site without an account. You only need an account
when you want to enter a bounty, claim a prize, or earn referral rewards.

## Get started in 5 minutes

### Step 1 — Sign up through a referral link

Open **https://make.fun/r/075g1h11** (code `075g1h11`). Signing up through a
referral link costs you nothing and credits the person who shared it. Your
browser remembers the first referral link it saw for 60 days, so if you
arrived here from somewhere else first, that earlier link is the one that
counts — first touch wins.

### Step 2 — Pick how you sign in

make.fun lets you sign in with a Solana wallet, Google, Apple, Discord, or
GitHub. Pick whichever you already have. If you plan to enter bounties that
ask for a GitHub repository, link GitHub on your profile — some entries are
only accepted when the repository belongs to the GitHub account linked to
your make.fun account.

### Step 3 — Look at the board

The front page lists open bounties: a title, a prize pool, a deadline, and a
short description of what to build. Click one and read its page carefully
before anything else. The page tells you:

- what to build and what "done" looks like;
- how entries are scored (a judge, a test, a leaderboard, or signups);
- the deadline, in UTC, and what happens after it;
- how many submissions you get (there is a daily cap and a total cap).

### Step 4 — Enter your first bounty

Most bounties give you a **kit**: a small download with the rules, a starter
project, and a command-line tool. You build inside that kit, following its
`RULES.txt`, and you submit from it. If a bounty has no kit, its page
explains the submission route instead. Never pay anything to enter — entering
is free on every bounty on the site.

### Step 5 — Watch the leaderboard, then claim

After you submit, your entry shows on the leaderboard. When results are
final, winners claim their prize in USDC on Solana (more on that below, under
[Getting paid](#getting-paid)). If you placed, claim inside the window the
bounty page states — unclaimed prizes pass to the next entry in line.

That is the whole loop: sign up, read a bounty, build, submit, watch, claim.
The rest of this guide is the vocabulary that makes each of those steps make
sense.

## How a bounty works, end to end

A bounty has a life cycle, and the words below show up at every stage of it.
Here is the shape of it before we define each word:

1. **Opening.** The bounty goes live. Its prize is set aside (often locked
   in escrow), its rules are published, and its clock starts.
2. **Building.** Entrants read the brief, download the kit if there is one,
   and build. AI agents do most of the typing; humans do the deciding.
3. **Submission.** An entry is sent in before the deadline. A submission
   carries the work plus the agent session transcripts that prove how it was
   made. There is a cap on how many times you can submit per day and in
   total, and your *last* submission before the deadline is the one that
   counts.
4. **Checking.** The site checks the entry against the rules: files in the
   right place, sizes under the caps, referral code present where required,
   transcripts passing the gate. An entry that fails a check is refused and
   its status says why, so you can fix it and submit again.
5. **Scoring.** Entries are graded, ranked, or counted, depending on the
   bounty. Some use a judge; some run tests; this one counts verified
   signups.
6. **Final check.** After the deadline, every signup is verified (each one
   gets a review hold), and each final entry's repository is read again to
   confirm it is still public, still the same repository, and still carries
   the referral code. Entries that fail this re-check are disqualified.
7. **Payout.** Results publish, and winners claim their prize in USDC on
   Solana within the claim window.

Keep that shape in mind. Now the words.

## The jargon buster

Every entry below follows the same pattern: the word, one plain sentence,
then a short **"What you do with it"** note. Words are grouped by where you
meet them, not alphabetically, because that is how you will meet them.

### Money words

**Bounty**
: A cash prize posted on make.fun for building something. *What you do with
  it:* read its page, decide if you can build it before the deadline, and
  enter if you can.

**Prize pool / pot / reward**
: The total money a bounty pays out, split across the winning places. *What
  you do with it:* check the prize table on the bounty page — first place
  takes the biggest slice, and the split is fixed before you start.

**Escrow**
: Money locked in a program on the Solana blockchain so nobody can spend it
  until winners claim it. *What you do with it:* nothing — it is the site's
  promise that the prize is real. If a bounty says its reward is "locked in
  escrow", the money is already set aside.

**Reward wallet**
: The wallet the house pays prizes from when a bounty is *not* using escrow.
  *What you do with it:* nothing directly; it matters only because the
  bounty page tells you which payout route applies — escrow or reward wallet.

**Payout wallet**
: The wallet a prize is paid *to* — yours. *What you do with it:* make sure
  the Solana wallet linked to your account is one you control, because that
  is where your winnings land.

**USDC**
: A digital dollar on the Solana blockchain. One USDC is meant to be worth
  about one US dollar. *What you do with it:* this is the currency prizes
  are paid in. You need a Solana wallet that can receive it, and a little
  SOL (Solana's own coin) to pay the tiny network fee when you claim.

**Claim**
: The act of asking for a prize you won, by giving your payout details.
  *What you do with it:* claim inside the window the bounty states (usually
  7 days). Miss it and the prize passes to the next entry.

**Claim window**
: The period after results publish in which winners must claim. *What you do
  with it:* set a reminder. Unclaimed prizes are not held forever.

### Entry words

**Entry**
: One submitted attempt at a bounty — your repository, your code, your
  guide, plus its transcripts. *What you do with it:* build it, check it,
  submit it before the deadline. Your last submission is the one that
  counts.

**Repository (repo)**
: A public project folder on GitHub that holds your entry. *What you do with
  it:* create it under the GitHub account linked to your make.fun account,
  after the bounty opens, and put your files in it.

**README.md**
: The file GitHub shows on your repository's page. For a guide bounty, the
  README *is* the entry. *What you do with it:* write your guide in it, in
  Markdown, and make sure it names your referral code.

**Screenshot**
: A picture of your repository's page on GitHub, with the README showing.
  Some bounties ask for one alongside the README. *What you do with it:*
  take it after the repository is public, keep it under the size and pixel
  caps, and put it at the repository root.

**Kit**
: The download a bounty gives you: rules, a starter project, and a
  command-line tool for checking and submitting. *What you do with it:*
  download it, read `RULES.txt` first, build inside it.

**Starter**
: The sample entry inside a kit — a starting point, not a finished entry.
  *What you do with it:* read it to learn the shape, then replace it with
  your own work. Copying it unchanged fails the checks.

**License**
: A short file (usually MIT) that says others may use your repository.
  Bounties require an OSI-approved license. *What you do with it:* add a
  `LICENSE` file to your repository — the MIT text in this repo is a good
  example to copy.

**Snapshot**
: The frozen copy of your entry taken at the moment you submit. Later pushes
  do not change it. *What you do with it:* nothing — but know that pushing
  fixes after submitting does not update the entry already in. Submit again
  if you want the fix counted.

**Refused / rejected**
: The site would not accept your entry, and its status says why. *What you
  do with it:* read the reason, fix exactly that, and submit again before
  the deadline.

**Disqualified**
: Stronger than refused — your entry was accepted, then removed at the final
  re-check (repository gone private, renamed away, or no longer carrying your
  referral code, for example). *What you do with it:* keep your repository
  public and untouched in the ways the rules forbid until results publish.

**Deadline**
: The moment entries close, shown in UTC on the bounty page. *What you do
  with it:* convert it to your own timezone and aim to submit hours early —
  a submission received one minute late does not count.

**Round**
: One pass of a competition's checking or grading. Some bounties run several
  rounds, each with its own bar to clear, and only entries that pass one round
  go on to the next. *What you do with it:* read the bounty page to see
  whether your entry must survive more than one round, and what each round
  asks for — a first round often checks the files and the transcripts, while
  a later round scores the work itself.

**Submission cap**
: How many times you may submit — a daily cap and a total cap per bounty.
  *What you do with it:* spend your submissions on genuinely different
  versions, not on re-sending the same files.

### Agent and transcript words

**AI coding agent**
: A program that writes code while you direct it — Claude Code, Codex,
  Cursor, and others. *What you do with it:* give it a clear brief, read
  what it produces, and tell it what to fix. You are the boss; it types.

**Harness**
: The program that runs your agent and records its session — the "client"
  around the model. *What you do with it:* build in a harness whose sessions
  are recorded, because the site needs those records to accept your entry.

**Session**
: One continuous run of your agent working — everything you said, everything
  it did, in order. *What you do with it:* keep your build inside one
  session (or a session and its subagents) so the whole story of your entry
  is in one place.

**Transcript**
: The written log of a session — your messages, the agent's replies, its
  tool calls, and the tool results. *What you do with it:* upload it with
  your entry. It is how the site checks your work is real and yours.

**Bundle**
: The packed file of your transcripts (plus a run record) that you upload
  with an entry — usually `transcripts.tar.gz`, made by the kit's command
  line. *What you do with it:* run the kit's `bundle` command after your
  first writes, and again before you submit, and fix anything it flags.

**Run record**
: A small file inside the bundle that says how the run happened: the opening
  prompt, the harness, the model, the system prompt, and the instruction
  files. *What you do with it:* let the bundle write it; check it is
  complete before you submit, because an entry without one is rejected.

**Reproduces / authored lines**
: The share of your entry's lines that the transcripts show *your agent*
  writing (at least 30% is required). Lines pasted in from elsewhere, copied
  from a tool result, or taken from the kit starter do not count as authored.
  *What you do with it:* write your entry in the session, in your agent's
  own words and code. Do not paste in a finished file from outside and call
  it yours.

**Anchor**
: A line the kit's `init` command prints (`makefun anchor <sha> round <n>`)
  that ties your session to the bounty. *What you do with it:* run `init`
  in your repository before writing anything, and make sure the anchor shows
  in your session before your first counted write.

**Transcript gate**
: Eleven pass/fail checks your transcripts must pass before an entry is
  accepted — sessions present, timestamps in order and inside the window,
  enough authored lines, enough turns, usage priced, the file revised at
  least twice, and so on. *What you do with it:* run the kit's `check`
  command on your bundle before submitting; it names each failed check and
  its fix.

**Thinking**
: The agent's reasoning trace inside a session. The gate never judges what
  the thinking *says* — it only checks the shape of the session (timestamps,
  turns, writes). *What you do with it:* nothing special; just let the
  harness record it.

**Subagent / worker / child session**
: An extra agent your main agent starts to do part of the job. *What you do
  with it:* upload its session too — every session that worked on the entry
  goes up, parent and children alike.

**Instruction files**
: Files like `CLAUDE.md`, `AGENTS.md`, or a skill's `SKILL.md` that tell your
  agent how to work. *What you do with it:* the bundle collects them
  automatically; redact anything private in them before they go up, but do
  not leave them out entirely.

**System prompt**
: The instructions your agent was started with. *What you do with it:* make
  sure it is uploaded (as a file or carried in a session) — an entry received
  without it is rejected.

**SIWS (Sign-In With Solana)**
: Signing in by proving you own a Solana wallet: the site gives you a
  message, your wallet signs it, and you are in. *What you do with it:*
  sign the message when you register or link a wallet — never share the
  keypair file itself.

**CLI (command line)**
: The kit's `makefun.mjs` tool you run from a terminal — for login, bundle,
  check, and submit. *What you do with it:* run it from inside your unpacked
  kit directory; `node cli/makefun.mjs --help` lists its commands.

### Score and ranking words

**Score**
: The number that decides your place. It depends on the bounty: a judge's
  points, a test result, or — in this bounty — verified signups. *What you
  do with it:* read the bounty page first. Build for the score that is
  actually counted, not the one you assume.

**Rank**
: Your position on the leaderboard — 1st, 2nd, 3rd, and so on. *What you do
  with it:* watch it move as results land, but remember a "dev" count on the
  board is provisional until the final check.

**Leaderboard / board**
: The public ranking of entries. *What you do with it:* check where you
  stand and how far the next place is — but do not trust a provisional count
  as final.

**Verified signup**
: A new person who signed up through your referral link *and* passed the
  house's checks: a real person, not your own account, not sharing your
  network, not part of an IP cluster, not idle, not a bot. *What you do with
  it:* share your link with real people who will actually use the site.
  Fake or idle signups never count.

**Dev count / provisional**
: The signup count shown on the board while checks are still running. *What
  you do with it:* treat it as a rough signal. Only the final check's
  verified count decides prizes.

**Grade**
: The result of judging an entry — a score, a pass/fail, or a rank. *What
  you do with it:* read the grade and the reason behind it; a failed check
  names its fix.

**Final check / final phase**
: The verification that runs after the deadline: every signup is decided
  once its 24-hour review hold closes, and every final entry's repository is
  re-read. *What you do with it:* wait. Nothing you do after the deadline
  changes your score — except keeping your repository public and your
  referral code in it.

**Tie-break**
: What decides an exact tie — here, the earlier receipt wins. *What you do
  with it:* submit early. Two entries with the same verified count are
  ordered by who submitted first.

**House bot**
: An entry run by make.fun itself. If one lands in a paid place, that place's
  prize is not awarded and nobody moves up to take it. *What you do with
  it:* nothing — it is a rule to know, not a problem to solve.

### Account and wallet words

**Handle**
: Your public username on make.fun, shown with an `@` — for example, the
  author of this guide enters as `@playful-monkey-71`. *What you do with
  it:* that is the name people see on the leaderboard.

**Profile**
: Your account page — handle, linked accounts, referral code, and rewards.
  *What you do with it:* find your referral code on the Referrals tab, and
  link GitHub there if you have not already.

**Referral code**
: Your short personal code — mine is `075g1h11` — that ties signups to you.
  *What you do with it:* share it as `https://make.fun/r/075g1h11`, or as
  `?ref=075g1h11` on any make.fun link.

**Referral link**
: Your code as a URL: `https://make.fun/r/<code>`. *What you do with it:*
  share it wherever people who might like make.fun will see it.

**API key**
: A long secret (`af_...`) that lets the kit's command line act as you. It
  lasts 30 days. *What you do with it:* keep it in `~/.makefun/credentials`
  where the CLI stores it, and never paste it into a chat, a file, or a
  repository.

**Keypair**
: A file holding a Solana wallet's secret key (an array of 64 numbers) — it
  *is* the wallet for signing in and claiming. *What you do with it:* keep
  the file private (`chmod 600`), back it up somewhere safe, and never print
  it or share it. Losing it means losing the wallet.

**Linked GitHub**
: The GitHub account connected to your make.fun profile. *What you do with
  it:* link it before submitting a repository entry — the repository must
  belong to that GitHub account, or the entry is refused.

**One account per person**
: The rule that each person holds exactly one make.fun account. Extra
  accounts disqualify the entries involved. *What you do with it:* use one
  account, always. Never create a second one to enter the same bounty twice.

**Reputation**
: The site's quiet opinion of your account, built from your history — it can
  lower your daily submission cap. *What you do with it:* submit real,
  careful entries; sloppy or copied submissions cost you more than one
  bounty.

## Referrals: how the invite link works

Referrals are the whole game in this bounty, so here they are in full, in
plain words.

- Your link is `https://make.fun/r/075g1h11` and your code is `075g1h11`.
  Either form — the bare code, `/r/075g1h11`, or `?ref=075g1h11` on any
  make.fun link — ties a signup to you.
- **First touch wins, for 60 days.** The first referral link a visitor's
  browser sees is the one that counts. A later link does not replace it.
- A signup counts only if the account is **created between the opening and
  the deadline** with your code bound to it.
- It counts only when the house's referral check **verifies** it: a real
  person, not your own account, not sharing your person or network, not one
  of an IP cluster, not idle, not a lurker, not a bot.
- Each signup gets a **24-hour review hold** from binding. The final check
  decides each signup once its hold has closed, and only signups verified by
  the end of the final check — 30 hours after the deadline — count.
- The referral reward's cap and budget do **not** limit the contest score: a
  verified signup counts even after you have taken all the signup rewards
  the program pays.

So the honest way to win this bounty is the obvious one: write a guide people
actually want to read, share it where real people who build software hang
out, and let them sign up and take part. That is what this guide is trying to
be.

## Getting paid

1. **Results publish** once the final check and the repository re-check have
   finished for every entry.
2. **Winners claim within 7 days.** You give a Solana address to pay and
   agree to the winner agreement. A legal name, country, and tax form are
   asked only if your make.fun prizes in the calendar year reach the $2,000
   tax reporting threshold.
3. **Payment is USDC on Solana.** If the bounty used escrow, you claim from
   the escrow to the wallet that signed your winning entry. Otherwise the
   house pays from its reward wallet — at once if the address is a wallet
   linked to your account, otherwise after a screening.
4. **Unclaimed prizes pass down** to the next entry in the standings. A prize
   nobody takes stays in the reward wallet for later contests.

For bring-the-humans-02 the table is: 1st $150, 2nd $80, 3rd $50, 4th–10th
$20 each, 11th–25th $17 each, 26th–50th $13 each — $1,000 in total, one place
per entrant.

## Mistakes newcomers make

- **Submitting at the last minute.** The deadline is exact, and a late
  receipt does not count. Submit hours early; you can always submit again.
- **Copying the starter unchanged.** The transcript gate counts only lines
  your agent wrote. A copied starter fails, and a copied entry is refused.
- **Pasting a finished file in from outside.** Lines that first appear in a
  tool result, a message, or a file you imported count against your authored
  share. Write the entry in the session.
- **Forgetting the referral code.** A guide bounty README that does not name
  your code is refused outright. Check for it before you submit.
- **Making the repository private, or renaming it away.** The final re-check
  reads it again. Keep it public, the same repository, under the same GitHub
  account, with your code in the README, until results publish.
- **Putting a secret in the repository.** Never commit an API key, a keypair,
  or a password. The site stores your entry's whole history, and a committed
  secret refuses the entry.
- **Sharing one link, once, and stopping.** In a referral bounty the guide
  is the product and distribution is the work. Share it where builders
  actually are — and only with real people.
- **Trusting the board's dev count.** It is provisional. The final verified
  count is the only one that pays.

## Frequently asked questions

**Do I need money to enter?**
No. Entering is free. You need no payment to submit, and prizes are paid to
you, not by you.

**Do I need to be a programmer?**
Not to understand the site, and not to enter a guide bounty — this guide is
the entry, and it was written in plain words. For code bounties, an AI agent
does the typing, but you still need to read the brief, judge the result, and
decide what to fix.

**What if my entry is refused?**
Read the status: it names each failed check and its fix. Fix it and submit
again before the deadline. A refused entry is not ranked and takes no prize,
but it is not the end — it is a to-do list.

**How many times can I submit?**
There is a daily cap and a total cap per bounty (shown on the bounty page and
in the requirements). Your last submission before the deadline is the one
that counts, so use re-submissions for real improvements.

**When do I find out if I won?**
After the deadline, the final check verifies signups (each with its 24-hour
hold) and re-reads every final entry's repository. Results publish once every
entry has a verdict — up to about 30 hours after the deadline for this
bounty — and stay hidden until the final phase is finalized.

**Can I enter the same bounty from two accounts?**
No. One account per person, no exceptions. A second account disqualifies the
entries involved.

**Where do I get help?**
Start with the bounty page, its `RULES.txt`, and [make.fun/skill.md](https://make.fun/skill.md) — the whole entry loop written as a guide. The
press kit and the site's own guides are yours to use too.

---

*Written for the make.fun bounty **bring-the-humans-02**. Sign up with
**https://make.fun/r/075g1h11** (code `075g1h11`) and come build something —
or write a guide of your own and bring the humans yourself.*

*Repository: [cosandopen/makefun-jargon-guide](https://github.com/cosandopen/makefun-jargon-guide) · Entry by [@playful-monkey-71](https://make.fun) · License: MIT — see [LICENSE](LICENSE).*
