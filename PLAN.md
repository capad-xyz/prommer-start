# prommer-start

Two-door start page for https://prommer.net. Empty of product copy until the assessment clock starts.

Window: open until Tue 29 Sep 2026, 17:01 UTC (22:31 IST).

## Locked

One static page. Two doors.

- Booker: 4 talk topics and 4 proof links.
- Operator: 3 things he has actually run, each with a real URL.
- Contact: link to the contact already on prommer.net. No invented email.
- `links.json` holds the same URLs as the page.

Plan B, only if the 8 questions are long: ship the booker door alone.

## Rules

- Every line comes from a prommer.net or press URL opened during the clock.
- A line with no source does not go in the file.
- Not a second homepage, not a race calculator, not a searchts demo, not capad.fyi.
- One writer. The checker does not ship a second copy.

## Who

| Role | Does | Does not |
|---|---|---|
| Aadarsh | Begin, leave the test tab open, paste the 8 question titles, rewrite the reflection, Submit | Write the page |
| Grok Build | Read the site, write `index.html` and `links.json`, push, re-fetch every link, delete a dead line | Click Begin, invent a fact, turn on Pages |
| Tess | After the live URL exists, click every link on her computer and send pass/fail | Edit the copy |

## Checklist

### Before the clock

- [x] Public repo `capad-xyz/prommer-start`
- [x] Branch `master`
- [x] GitHub Pages: `master` / root. Saved.
- [x] This plan in the repo
- [ ] Test tab open on the laptop
- [ ] Begin not clicked yet

### After Begin

- [ ] 8 question titles pasted. Scope cut: two doors, or booker only.
- [ ] Sources opened. Unsourced lines excluded.
- [ ] `index.html` and `links.json` pushed to `master`
- [ ] Live URL opened: https://capad-xyz.github.io/prommer-start/
- [ ] Grok re-fetches every outbound link. Failures removed and pushed again.
- [ ] Tess clicks the same URL. Pass/fail only.
- [ ] One fix pass if she fails a link. She walks once more, then stops.
- [ ] Approach, URL, and reflection drafted. Reflection rewritten in Aadarsh's words.
- [ ] 8 answers filled. Submit while the test tab is still open.

## If Pages does not serve

Tess deploys the same repo to a `pages.dev` URL. Not capad.fyi. Then she does the click pass on that URL.
