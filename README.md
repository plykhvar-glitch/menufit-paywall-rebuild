# Paywall Audit — MenuFit

**Live:** https://plykhvar-glitch.github.io/menufit-paywall-rebuild/

Five changes to the MenuFit paywall, the screen right after "Congratulations!", fed by what the onboarding already asks. The paywall is rebuilt in MenuFit's own design: the bag logo and Restore, the bold centred headline, the phone in the middle, the faded ring of restaurant logos, "No Payment Due Now" and the blue "Try for $0.00" pill. Flip **Today / Proposed** above the phone to compare, and change the onboarding answers under it to watch the paywall rewrite itself.

| # | Change | Potential outcome |
|:-:|:--|:--|
| 1 | Say their goal and their restaurants in the headline | CR +15–20% |
| 2 | Put your 4.8 from 55K ratings above the button | CR +10–15% |
| 3 | Show their per-meal target, in your own "My preferences" bar | CR +5–10% |
| 4 | Show their restaurant in the phone, not Carbone | CR +5–10% |
| 5 | A second chance when they close it: Premium without a trial | ARPU +10–15% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for MenuFit.

**Grounding.** The rating, chart position and price come from MenuFit's US App Store listing; 1.5 million users from menufitapp.com; paywall copy, meals, the Subway cards and the preferences bar from the MenuFit iOS app.

**Run locally**

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/ (add `?open=pw` to land on the paywall).
