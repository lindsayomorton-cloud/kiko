# Wildkind kids screen rules

These rules come from the Ecosystem Builder pond game. Every new screen, game or realm follows them.

## 1. Every screen is either READING or DOING

**Reading screens** (story, facts, plant/critter cards, workbench)
- Card fills the screen. Kiko swims in the top-right corner, behind the words and never over them.
- Show one sentence at a time. The current line is big, earlier lines are smaller and faded to 60%.
- Pictures from the story show in a row of cards under the text:
  - the card for the current line has a yellow border and lifts up
  - cards already read are in full color
  - cards still to come are faded with a dashed border
  - tapping a card jumps to that line
- A Next button sits under the text.

**Doing screens** (drag, tap the spot, pick the answer)
- No story card. No Kiko button.
- Top left: a tilted yellow **"Your turn!"** badge.
- Below it: one instruction in a solid dark teal pill (#2f5f58), white heading font, 30–48px, ending in an arrow (⬇) toward the action.
- Below that: the things you can use, as big pictures. Each has its name in a cream pill under it.
- For choosing and quizzes, grey the background slightly (rgba(70,70,62,.28) plus grayscale .7) so only the choices are bright.
- For drag and tap-the-spot, the water or spot stays bright, with no grey.

## 2. Text never moves
- The left edge and the top of the reading line stay in the same place from line to line.
- On warnings, show only the current line. Its box keeps a fixed height, so nothing shifts when the next line is shorter or longer.
- Pictures sit to the right of the text or below it. They never sit in front of the text.
- When a picture appears or changes, it swaps into the same spot instead of adding a new row.

## 2b. Type
- Story lines: 40–68px, weight 700, near-black #111111, line-height 1.4–1.45, letter-spacing .02em.
- Workbench lines: up to 72px. Card lines: 24–40px.
- Titles: Figtree 500 in sage #4a5a35, with a small sage line and dot under them. HELP titles are red #8f1f17.
- Labels never go under 18px. Toasts are 24–34px.
- Text sits on a solid surface (cream, white or dark teal), never straight on top of a painting.

## 3. Yellow follow-along highlight
- A yellow highlight (#ffd400 with a 5px glow) moves word by word through the line being read.
- Default speed is 750ms per word. It stays longer on long words and pauses at punctuation.
- Tapping any word moves the highlight back to it. It runs on stories, workbench lines, cards, Snack Shack and the water test.
- Tweaks: Follow along (on/off) and Read pace (ms per word).

## 4. Pictures, not emoji
- No emoji anywhere. Use the watercolor paintings.
- If there's no painting yet, show words only and add the missing art to Art Request List.md.
- Pictures are big, 110–280px. Picture cards are white, rounded 24–32px, with a soft tan border (#ecdcbc).

## 5. Buttons
- No black outlines or hard black shadows.
- Main button: sunny #ffd166, text #4a2e0a, golden shadow `0 6px 0 #e3a92e`. Lifts 3px on hover, presses down 4px when tapped.
- Second button: cream #fffaf1, tan border #ecdcbc, shadow `0 5px 0 #e4d0a6`.
- Green button: #8fb36a with white text, shadow `0 6px 0 #5f8a45`.
- Buttons are at least 64px tall and use the heading font.

## 6. Feedback
- Toasts appear where the child last tapped or dropped. Cream with a yellow border, in front of everything.
- "New fish friend" style banners pop up near the top of the water, not the middle.
- Celebrations and "Uh oh…" sit near the top of the screen: a big Kiko (240–420px wide) and 40–80px text.
- The garden background always stays in full color.

## 7. Never
- Never show audio, read-aloud or speaker buttons.
- Never show two ideas at once on a reading screen.
- Never show the same painting twice in one row.
- Never cover text with an animation.


## 8. Patterns from the pond game (Nov 2026)
- **Story card:** a teal card across the top with the garden still visible under it. Kiko's round picture sits beside it with the speech tail pointing at Kiko. Lines are in the rounded display font, one sentence per line, at most two sentences per slide. The second sentence fades in once the first has been read.
- **Warning card:** a red 8px border and a hazard stripe across the top. A badge names the problem type ("Slime alert!", "Leak alert!", "Poison alert!"). It pulses on the first slide, then calms down. No title label.
- **Pictures:** beside the text (on the right) when they're animated scenes, and under the text when they're paintings or charts. No frame, as big as the space allows. Never let them push the Next button off the card.
- **Charts:** a centered row of round picture circles with "+", "=" and "→" signs and pill labels (Sun + Fish poop = Lots of algae!). Meters run green to red with a marker.
- **Next:** a cream "Next →" button, always in the card's bottom-right corner. It glows yellow once the line has been read. Auto-advance moves on 2 seconds after the highlight finishes, and stops on doing screens.
- **Your turn! (choices):** greyed background, a teal instruction pill, and big white picture cards at the bottom of the screen. Never put the instruction on the land as well.
- **Not quite!:** an orange-bordered pop-up with the wrong picture crossed out in red. Hint lines in the display font. A "Try again →" button.
- **Messages:** only from a tap, shown next to the finger. Journal notes never pop up on their own.
- **Kiko:** never happy or hopping before he's in the pond. Show the bucket until then.
