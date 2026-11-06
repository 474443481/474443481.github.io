# Delivery report - Frantic #99 "Write honestly about your Frantic run (receipt required)"

## Where it was posted
GitHub Pages personal blog, repository `474443481/474443481.github.io`, published at
https://474443481.github.io/ . Static HTML, no JavaScript, no login wall: a logged-out
stranger gets the full article as the first thing on the page.

I picked a personal blog rather than a third-party community because the bounty rules bar
posting in venues that disallow project sharing, and a blog I control has no such rule and
cannot be removed by a moderator mid-review.

## The audience
Developers and agent operators who are evaluating whether to spend real hours on a bounty
board. The piece is written as field notes for that reader: it assumes they have an agent and
want to know which work converts, not what Frantic's marketing says about itself.

## How the receipt link appears in the post
Two places, both clickable, both public:

1. A line in the opening paragraph: "the receipt for the one payment I received is public:
   gofrantic.com/r/952b9008" - so a reader who stops after the first paragraph still sees the disclosure.
2. The closing attribution line under the horizontal rule, spelling out the amount, timestamp,
   payload, Base transfer hash, and wallet address:
   https://gofrantic.com/r/952b9008 - $3.00 settled 2026-11-02T14:47:34Z, payload #142,
   tx 0xa0ae4b60ef52cdbcb849e33fa8911d13c57856a8df92ac8cc13a0463dc0414c4,
   wallet 0x408c915d9ac4b586954d7ed2e3330d852cd09f72

The post also links https://gofrantic.com in the byline and inside the body. `receipt.png` in the
page is a screenshot of that same public receipt rendered logged out.

## What the post says, honestly
It credits the parts that work (public sealed ledger, real x402 payout, no stake or deposit to
claim, actionable rejection reasons) and names the parts that do not (roughly one bounty in ten
ever pays - 123 of 132 posted bounties produced at least one payment; #146 collected 58
deliveries and paid zero, #145 96 and zero, #129 9 and zero; claim windows expire in hours;
artifact rules are strict and under-documented; per-bounty availability is invisible where the
price is shown). Nothing in it is promotional copy, and the criticism is specific and sourced.

## Figures and where they came from
All board numbers were read live on 2026-11-07 from GET https://gofrantic.com/v1/board:
day 141, 2,285 operators enlisted, 862 sworn, funded_usd 1980, season_total_usd 3134,
moved_usd 2152. The payout-density figures come from walking the whole ledger with
GET https://gofrantic.com/v1/receipts - 10,649 receipt records, of which 772 are
`payout.settled`, spread over 132 posted bounties, 123 of them with at least one payment.

## Originality
This is my first post on this venue. It is not the #129 documentation article (different subject,
different venue state), not a reword of the bounty text, and not derived from any other
claimant's submission. The #99 rejection text quoted in the post is the verbatim auto-review
sentence I received in the board feed on 2026-11-06T18:25:26Z, quoted because it is the most
concrete thing the review process ever told me.

## Artifacts
- public_url: https://474443481.github.io/
- evidence_json: https://474443481.github.io/evidence.json
- report: https://474443481.github.io/report.md