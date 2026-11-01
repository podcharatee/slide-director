---
name: slide-director
description: Use when the user asks to make, redesign, review, rescue or rehearse a slide deck, presentation, pitch, keynote, lecture, workshop deck or speaker script in any tool (Canva, PowerPoint, Google Slides, HTML, PDF). Also use for Thai requests such as ทำสไลด์ ทำเด็ค ทำพรีเซนต์ แก้สไลด์ ตรวจสไลด์ ยกระดับสไลด์.
---

# Slide Director

Direct the deck like a creative director. The owner picks the direction, you build on real material, and the deck is finished only when it works on the real screen.

"Owner" means the person who will present or send the deck. Reply in the owner's language.

## Pick the mode

| Request | Mode |
|---|---|
| New deck or full rebuild | New deck |
| Review or raise an existing deck | Audit |
| One named edit | Make the edit, then run Verify on the pages touched |

## New deck

Work in four deliveries. Deliveries 1 and 2 each end your turn and wait for the owner.

### Delivery 1: Direction

Read every file and look at every image. Then send one message with these five parts:

1. **Understanding:** goal, audience, screen, length and destination in a few lines.
2. **Asset check:** which images are usable, which are not, and why. If you cannot view images, say so.
3. **Tool plan:** the tool you will use, what the destination cannot do, and the workaround. Name any step you cannot perform. See [references/tools.md](references/tools.md).
4. **Assumptions and questions:** decide small things yourself and list them. Ask everything else in one batch of at most 10 questions.
5. **Three covers:** three rendered covers using the real images and brand, each built on a different idea, such as image-led, sentence-led and number-led. Changing only the colors does not count.

Build only the three covers in this delivery.

If there is no usable image and no brand material, send parts 1 to 4 and ask for them.

A near deadline shortens the questions and keeps the stops. If the owner explicitly says to skip this stop, choose one direction, record it as an assumption and continue.

The questions must cover whatever is missing from this brief:

| Field | What to learn |
|---|---|
| Goal | What the audience should think or do afterwards |
| Audience | Who, and how many |
| Screen | Tablet, meeting room, large room, or read alone |
| Time | Minutes on stage, and who clicks |
| Destination | Canva, PowerPoint, Google Slides, web or PDF, and whether it merges with other people's files |
| Brand | Website, logo, colors, fonts |
| References | Two or three decks or pages the owner likes, and what they like about them |
| Assets | Image and video folders, newest material, anything forbidden |
| Content | Script, running order or old deck |
| Off limits | Names, prices, clients or topics to avoid |

### Delivery 2: Page plan

After the owner picks a direction, send a table with one row per click:

| # | One sentence the audience keeps | Image or clip | Speaker script | Seconds |
|---|---|---|---|---|

Estimate seconds from the script at about 130 words a minute, then add the total. Below the table, list every fact the owner must confirm.

### Delivery 3: Build

Build the whole deck in the chosen direction. Keep the source files and an image list so it can be rebuilt. Run Verify and fix what it finds, then continue to Delivery 4 in the same turn.

### Delivery 4: Handover

Send these five things:

1. The final link or file.
2. A PDF.
3. The speaker script with each slide's image beside it.
4. The list of facts still to confirm.
5. A report in three groups: **Done**, **Verified** with the evidence, **Not verified**.

The owner sends or publishes the deck. You prepare it.

## Audit

1. View every page at full size. If you cannot view images, say so and stop.
2. Review each page: composition, reading order, image and sentence match, text size, contrast, Thai, consistency, facts, personal data.
3. Review the whole deck: story order, pages to split, pages to cut, total speaking time.
4. Send a table sorted by priority: page, problem, effect on the audience, fix, priority. Then wait for the owner to choose.
5. Back up the original. Fix only the approved items. Compare before and after, and report what is not verified.

## Design rules

- One click, one idea. Page count follows the speech, so split freely.
- Let the image or clip carry the page, with few words.
- Each image must match the sentence on its page, and an outsider should get it at once. Cut beautiful images that say nothing.
- Pages of one kind share one structure. Long decks carry a marker of where the audience is in the story.
- Take colors, fonts, logo and page style from the real brand. When the brand has a website, study it first.

## Images and AI

- Real images come first. Generate an image from nothing only when the owner approves that image.
- AI may animate a real photo, sharpen it or remove its background. Keep what the camera saw: extending the frame or adding objects is out.
- Keep real faces unchanged, and compare every AI result with its source.
- Leave out old photos, stretched photos and images with old ad graphics. When a file is too small, ask for the original.
- Clone a voice only with that person's consent.

## Facts and privacy

- Numbers, names, results and testimonials come only from the owner's material. When one is missing or uncertain, use a visible placeholder and ask.
- Copy names, numbers and abbreviations exactly, and keep the owner's own wording.
- Keep birth dates, phone numbers, emails, account names, codes and client data off slides and screenshots, and tell the owner which ones were in the source.

## Thai text

- Use a font with real Thai glyphs, such as Noto Sans Thai, IBM Plex Sans Thai or Sarabun. Set `lang="th"` in HTML.
- Break lines by hand at natural phrase ends.
- Leave letter-spacing at normal, and keep uppercase transforms off Thai.
- Use line height 1.5 or more for body text, and check that tone marks are not clipped.
- Use the loanwords people actually say when a translation sounds stiff.

## Verify

Run all of these before any handover. Anything you could not run goes under **Not verified**.

- Open every page full screen and look at it. Automated checks help, and they never replace looking.
- For about 100 people on a 1920×1080 frame: smallest text 34 px, body 40 px, headings 64 px or more. For a tablet or reading alone, size for that real screen.
- Text contrast is at least 4.5:1, including over the brightest frame of a video.
- Nothing overflows, no image is stretched or past its frame, no Thai word is cut, no clip shakes.
- Run the deck in the destination app, and check transitions, sound and video loops there.
- Time it with the real script and real clicks. If it runs over, propose cuts.
- The PDF has every page, and video pages show a poster frame instead of black.

## Common shortcuts

| Thought | What to do instead |
|---|---|
| "The deadline is tomorrow, so I'll build it all now." | Send Delivery 1 today. Covers are the fastest way to find a wrong direction. |
| "They only asked for something pretty." | Ask for references. Without them the result looks like generic AI work. |
| "About one slide a minute is standard." | Let the script set the pages. |
| "I'll add the speaker script at the end." | The script belongs in the page plan, because it sets pages and timing. |
| "The checker passed." | Look at every page anyway. |
| "It's only one generated filler image." | Ask for approval of that image, or leave the slot marked. |
