Reference: Tweeting for max impact (X ranking model)

How the X ranking stack works — Phoenix retrieval (embedding-based candidate sourcing) + Thunder in-network delivery — and how to write tweets for it. Use this for the company X account and the founder's personal X posts during a launch or funding announcement; pair it with references/linkedin-launch-playbook.md (the LinkedIn/X social rows) and references/linkedin-algorithm-2026.md (the LinkedIn counterpart).

Source: internal reference notes (@lessin-style playbook). No live URL.


1. Optimize for the full action surface, not just likes

The scorer rewards 11 positive actions. A like is one weight; dwell + profile-click + reply + photo-expand stacked is many. Tweets that get all of these crush like-bait.


Dwell → write tweets that take >2s to read. Long-form, threads, screenshots of text, charts that require reading.
Photo expand → attach an image worth tapping (chart, screenshot, meme with text). Don't waste the slot.
Profile click → write things that make people wonder "who is this." First-person stakes, contrarian claim, identity hook.
Reply → ask a real question or stake a contestable position. Polls are cheap replies but they count.
Quote → leave a clear handle to argue with. Bold claim + clean phrasing = quotable.
Follow → tweet should imply "there's more like this." A series, a beat, a recurring frame.


2. Avoid the negative four at all costs

Block / mute / report / not-interested carry negative weights. They don't just zero you out, they suppress you to that user's whole cluster (because Phoenix retrieval is embedding-based, similar users get demoted too). Outrage-bait, ragefarming at out-groups, and aggressive politics cost more than they earn in the new model than in the old one.

3. Topic consistency compounds out-of-network reach

Phoenix retrieval is similarity-search over a frozen embedding space. If your last 20 tweets cluster cleanly (VC/tech/markets, or politics, or memes), Phoenix has a sharp vector for you and serves you to users with matching history. Mixed topics = blurry vector = weaker out-of-network distribution. Pick a lane per account.

4. The 127-history rule for distribution

Anyone who's engaged with you in their last ~127 actions has you in their personal context. You'll surface easier to them next time. The first hour after posting is when you collect those slots. Replying to early engagers, quote-tweeting reactions, keeping a thread alive = you re-enter their history fresh.

5. Each tweet is scored alone, no momentum inside a session

This kills the "post 10 things and one will pop" strategy at the ranking layer. Volume doesn't help score; it only helps lottery odds across users. Better: one high-action-surface tweet per day than five thin ones (which also risk the duplicate/recently-served filters cutting each other).

6. In-network gets you a guaranteed shot; out-of-network is where scale lives

Followers see you via Thunder regardless of score. Non-followers see you only if Phoenix retrieves you AND the scored probability beats their other candidates. To break out: hit actions that non-followers do — photo expand, dwell, profile click, follow. Likes from existing followers don't expand you.

7. Things that get you filtered before scoring even happens


Reposting identical content (kills the repost)
Posting too frequently (dedup + "recently served" cuts later tweets)
Generic phrasing that hashes near existing content
Trigger words in lots of users' mute lists ("crypto," slurs, common spam markers)



Practical playbook (@lessin style)


Lead with a contrarian claim (drives quote + reply).
Include a chart/screenshot (photo expand + dwell).
2–4 sentences, not a one-liner (dwell).
One tweet, not a thread, unless the thread itself is the asset (profile click + follow).
Post once in your sweet spot, then engage replies for 60–90 min to seed history embeddings.
Stay topically coherent across a week so Phoenix has a sharp vector on you.
Never punch in a way that earns mutes from the same cluster that likes you.


How this maps to a launch / funding post


The founder's launch tweet should be a single high-action-surface post (contrarian claim + chart/screenshot + 2–4 sentences), not a thin one-liner or a link dump.
No bare link in the tweet body — it suppresses reach; put the link in a reply (mirrors the LinkedIn "link in first comment" rule).
Block the first 60–90 minutes post-publish to reply to engagers and quote reactions — that's the window that seeds the 127-history slots and keeps the post alive.
Brief investors/friendlies to quote-tweet with a true sentence, not just like — quotes and replies are heavily weighted and pull in their out-of-network clusters.
Keep the company account topically coherent in the weeks around launch so Phoenix has a sharp vector when the big post lands.
