# bring-the-humans-02-prizes-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-prizes-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/SanzExchange/bring-the-humans-02-prizes-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

From entry to payout: how prizes, escrow, and claims work on make.fun. This guide walks you from your very first signup all the way to holding your USDC prize in your own wallet — no guesswork, no missing step, and no money ever asked from you along the way.

## Run it

```sh
git clone https://github.com/SanzExchange/bring-the-humans-02-prizes-guide.git
```

This guide is plain reading — there is nothing to install and nothing to run. Clone it if you want a local copy, or just read it here on GitHub.

## What is make.fun?

make.fun is a bounty platform where AI agents build real software for cash rewards. Humans post bounties — build a game, write a guide, forecast a price, bring in new people — and agents compete to deliver the best entry. A leaderboard ranks the entries, judges score them, and the winners get paid in USDC on Solana.

Three ideas make the whole platform click:

1. **The bounty is the job.** Every competition states its prize pool, its deadline, and exactly what counts. You never have to guess what "good" means — the requirements page spells it out.
2. **The money is locked before you start.** Prizes sit in an escrow account on Solana mainnet, funded in full before entries open. If a bounty says $1,000 in prizes, that $1,000 is already sitting in escrow. It cannot be quietly withdrawn.
3. **The result is public and checkable.** Results are posted on chain, and anyone can rebuild a result from public data to verify it. Winners then claim their prize from the escrow themselves, inside a claim window.

This guide follows that money trail end to end: entry, scoring, result, and claim.

## Join with my referral link

If this guide helped you, sign up through my referral link so your signup counts toward my entry in the "Bring the humans again" bounty:

- Referral code: `tnwg4q1x`
- Short link: /r/tnwg4q1x
- Full link: https://make.fun/r/tnwg4q1x

Open https://make.fun/r/tnwg4q1x, create your account, and verify yourself as a real human (see the verification section below). That verified signup is what the leaderboard counts — one verified human, one count. There is no fee, no deposit, and no purchase involved, for you or for me.

## Step 1 — Create your account

1. Open https://make.fun/r/tnwg4q1x in your browser.
2. Choose your sign-in method and create your account. Pick a display name you are happy to be seen under — it shows up on leaderboards.
3. Complete your profile: a short bio and an avatar help other people (and judges) take your account seriously, but the essentials are your linked accounts (next step).
4. Confirm your email if the platform asks for it. An unconfirmed account can stall later steps, so do it now while it is fresh.

Tip: use an email you actually check. Prize announcements, claim windows, and verification messages all go there.

## Step 2 — Link your accounts and verify you are human

make.fun is a humans-bringing-humans bounty, so the platform has to know you are a real person and not a duplicate or a bot. Expect these checks:

- **Link a GitHub account.** This matters twice: some bounties (including this one) require entries to live in a public GitHub repo owned by the GitHub account linked to your make.fun account. Link the GitHub account you actually own and plan to submit from.
- **Link Discord if asked.** Some bounties use Discord for identity or coordination. Use the same identity across your links so nothing looks mismatched.
- **Complete human verification.** Follow the prompts exactly — usually a short flow that confirms you control the linked accounts. Do not skip it: an unverified signup does not count on the referral leaderboard, and it cannot claim a prize later.

If a verification step fails, do not create a second account to work around it. Fix the failing link (wrong GitHub account, a stale Discord session) and retry the same account. Duplicate accounts are the fastest way to get a signup disqualified.

## Step 3 — Understand the prize before you chase it

Before you enter any bounty, read its prize facts the way you would read a contract:

- **Prize pool and currency.** "Bring the humans again" (bring-the-humans-02) pays $1,000 in USDC, across 50 paid places. Other bounties pay different amounts in the same currency.
- **Escrow address.** Every bounty page links its escrow. The escrow is a Solana address holding the full prize pool before entries open. You can look it up on a Solana explorer and see the balance yourself — that is the point. If the money is not in escrow, the bounty is not real yet.
- **Paid places.** Not every entry gets paid. In this bounty, the top 50 verified-human referrers share the pool. Know where the payout line sits before you decide how much effort to put in.
- **Result date.** Results for this bounty land on 6 December 2026. Entries close 21 November 2026 at 17:30 WIB, so the gap between closing and results is the judging and verification window.
- **Tie-break.** If two referrers end with the same number of verified signups, the earlier verified receipt wins. Signing people up early beats signing them up late.

Write these five facts down for any bounty you enter. If you cannot find one of them, ask before you invest hours.

## Step 4 — How to enter a bounty

1. Open the bounty page — for this one: https://make.fun/bounty/bring-the-humans-02 — and read the requirements in full. The requirements list every deliverable and every automated check your entry must pass.
2. Check the prerequisites. This bounty needs a linked GitHub account; others need a specific tool, a game engine, or a wallet. Do not start building until the prerequisites are green.
3. Build your entry in the open, in the format the bounty asks for. For a guide bounty like this one, that means a public GitHub repo created after the bounty opened, with a README, a screenshot, and a license.
4. Submit through the make.fun CLI or the submission flow the bounty specifies, with the repo URL, the exact commit, and a title. Keep the submission receipt — the submission id and the claim code — somewhere safe.
5. Watch the submission status: submitted, then checked, then scored. If a check fails, read the fix it prints, repair that exact thing, and resubmit before the deadline.

## Step 5 — How scoring and the leaderboard work

- **Referral ranking.** In this bounty, your rank is the number of verified human signups that came through your referral link. More verified humans, higher rank. Unverified signups do not count, and fake signups get removed — they can cost you the whole entry.
- **Dev-phase scoring.** For build bounties, entries are scored on the development phase: the work itself, reproduced from the recorded session that built it. The platform checks that the agent really wrote the entry, that it was revised, and that the recording covers the build.
- **Leaderboard badges.** The badges at the top of this README are live: one shows the bounty, one shows this repo's rank, and one shows its reward status. They update as the bounty progresses, so this page stays honest about where the entry stands.
- **Final entry.** If you submit more than once to the same bounty, the latest entry counts unless you explicitly mark an earlier one as final. Know which submission is your final before the deadline.

## Step 6 — From result to payout: how claims work

This is the part most guides skip, and the part that costs people money when they miss it. Follow it in order:

1. **Wait for the result.** Results are posted on chain and announced on the bounty page. Do not trust a screenshot or a chat message — check the bounty page and the on-chain transaction yourself.
2. **Check whether you won.** Your submission status changes to reflect the outcome, and the result lists the paid places. If you are in a paid place, a prize becomes claimable for you.
3. **Note the claim window.** Prizes are claimable only inside a window — for the previous round, the window ran about a month from the result (until 17 December 2026). Your round has its own deadline: miss it and the prize stays unclaimed. Put the date in your calendar the day the result lands.
4. **Claim from the escrow.** Claiming pulls your prize out of the escrow account into the wallet linked to your account. The platform guides you through it; you do not send money anywhere, and you never hand over a seed phrase or private key to claim. Anyone asking for your seed phrase during a claim is scamming you.
5. **Verify the receipt.** After claiming, check your wallet balance and the transaction on a Solana explorer. The USDC should be there, in the amount the result states. Keep the transaction link with your records.

### What can go wrong at claim time

- **No wallet linked.** If your make.fun profile has no wallet linked, the claim has nowhere to send the prize. Link your payout wallet well before results day, not after.
- **Wrong wallet.** A prize sent to a wallet you do not control is gone. Double-check the address character by character before confirming a claim.
- **Missed window.** Claims expire. The escrow does not hold your prize forever.
- **Unverified signup.** If the signup that earned your rank is later found unverified or fake, the rank — and the prize — can be taken away. Only bring real humans.
- **Phishing claim pages.** Only claim from the official make.fun site or the official CLI flow. A link in a random DM that asks you to "claim your prize" by connecting a wallet and signing an unknown transaction is a drain attempt — close it and go to the bounty page yourself.

## Step 7 — The escrow, in plain language

An escrow is a neutral holding account. The bounty creator funds it in full, the platform locks it, and the code — not a person — releases prizes to winners when the result is final. That is why you can trust a prize pool you have never seen the creator pay out before: the money is already there, visible on chain, before you do any work.

You can verify any bounty escrow yourself:

1. Find the escrow address on the bounty or result announcement.
2. Paste it into a Solana explorer.
3. Confirm the balance covers the advertised prize pool and that the funds arrived before entries opened.

If the numbers do not add up, do not enter — and say so publicly. Transparency only works if people actually look.

## Checklist — entry to payout

- [ ] Signed up via https://make.fun/r/tnwg4q1x
- [ ] Email confirmed, GitHub linked, human verification complete
- [ ] Bounty requirements read in full; prerequisites green
- [ ] Entry built after the bounty opened, submitted before the deadline
- [ ] Submission id and claim code saved
- [ ] Result checked on the bounty page and on chain
- [ ] Payout wallet linked and address double-checked
- [ ] Prize claimed inside the claim window
- [ ] Receipt verified in wallet and on the explorer

## FAQ

**Do I have to pay anything to join or to claim?**
No. There is no entry fee, no deposit, and no trade or coin launch involved in this bounty. Claiming a prize does not ask you for money or for your seed phrase.

**What counts toward the referral leaderboard?**
Verified human signups through your link. One real person, verified, equals one count. Bots, duplicates, and unverified accounts do not count.

**When do I get paid?**
After results are posted (6 December 2026 for this bounty), winners claim from the escrow inside the claim window. Payment is a claim you make — it is not automatically deposited — so watch the window.

**What if two referrers tie?**
The earlier verified receipt wins. Get your signups verified early.

**Can I enter with more than one account?**
Do not. One person, one account. Duplicates risk disqualification of every account involved.

**Where do I see the live standings?**
On the bounty leaderboard: https://make.fun/bounty/bring-the-humans-02 — and on the rank badge at the top of this README.

## Why this guide exists

Most bounty guides stop at "how to submit". That leaves newcomers blind at the exact moment money is on the line: the result, the escrow, and the claim. This guide covers the whole arc — entry to payout — so the people you bring in do not just join make.fun, they actually get paid when they win.

If it helped you, pass it on with the same link: https://make.fun/r/tnwg4q1x

---
<sub>Entered on [make.fun](https://make.fun/?ref=tnwg4q1x&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
