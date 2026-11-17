# Case Analysis: Amber Guyger (Law & Justice)

An interactive timeline version of the "Case Analysis: Amber Guyger" assignment. Students explore 16 events from the shooting in September 2018 to her release on parole in October 2026, watch news and courtroom videos of what happened, learn how Texas law sorts killings into different crimes, answer the nine questions from the assignment, and finish by downloading a Word essay to turn in on Google Classroom.

Everything runs in the student's browser. There is no server, no account, no tracking, and no outside fonts or libraries, so it works on school networks. The only outside links are your assignment's readings and the videos. Videos load from YouTube only when a student clicks play, and the readings and news-site videos open in a new tab.

## What students do

1. **Explore the timeline.** A timeline with cards above and below the line, colored by Part, with a card and illustration for each event. Cards with videos show a small play mark. Click any card to open a slide that starts with a short account of the event, with "Watch" and "Texas law lens" sections you can open if you want them. Arrow keys work everywhere.
2. **Use the Texas Law Toolkit** (top bar). Tabs: Offense ladder (with an ungraded quick check), Texas vs. most states, Castle Doctrine, Sentencing, Parole, Videos, Sources.
3. **Answer the questions.** At the end of each Part there is a pencil node. It opens your readings (the links from your document), the key moments in that Part, and the questions as text boxes with live word counts. Writing saves automatically on that device.
4. **Finish.** The star node (or "My essay" in the top bar) shows a checklist. When every box meets its minimum, "Finish and download my essay" builds the Word document and downloads it. Then the student attaches it in Google Classroom (Add or create, File, Turn in).

The questions and readings are exactly the ones in your document (Part 1: The crime and arrest, three questions; Part 2: The Trial, four questions; Part 3: Sentencing, two questions). The Word essay uses the same headings, with each question as a bold heading and the student's answer below it. See `example-output/Example-Student-Essay.docx`.

**Part 3 parole update.** Your Parole link describes the 2024 denial. Since then parole was granted (Oct. 1, 2026) and she was released (Oct. 16, 2026). The site says so on the Part 3 panel, links two newer articles, and carries the story through the timeline, so students answering "the recent parole decision" have current facts.

## Publish on GitHub Pages

1. Create a new repository on GitHub (for example `guyger-case-analysis`).
2. Upload the contents of this folder (at minimum `index.html`). Dragging the files into the repository page works.
3. Open Settings, then Pages. Under Source choose "Deploy from a branch," pick `main` and `/ (root)`, and save.
4. After a minute or two, your site is live at `https://YOUR-USERNAME.github.io/guyger-case-analysis/`. Share that link in Google Classroom.

Do not rename the repository after students start, because progress is saved per web address.

## Customize

- **Word minimums.** Open `index.html` in a text editor and search for `mins:`. Each question has its own minimum (for example `q2b:50`). Change the numbers and save.
- **Event text.** Search for `var EVENTS=` to edit the timeline text, or `var LADDER=` and `var STATES=` for the Toolkit.
- **Pairing with a rubric.** The nine questions map neatly onto your existing Constitutional Analysis rubric structure (summaries and questions, analysis and reflection, writing). Ask if you want a version written for this assignment.

## Student progress and privacy

- Progress (name, answers, which events were opened) is saved in the student's own browser on that device. It is not sent anywhere. The teacher sees work only when students turn in the Word file.
- A student who switches devices or browsers, or whose school computer clears browsing data at sign-out, starts over. The "Copy my answers as text" button on the finish screen is a backup.
- If downloads are blocked on a school device, students can copy their answers as text and paste them into a Google Doc.
- Updating this site (replacing `index.html`) does not erase progress, as long as the web address stays the same.

## Videos

13 of the 16 events have videos (24 in all). Twelve play inside the slide after a click (YouTube, using the privacy-enhanced address). Twelve are news sites' own video pages, which cannot be embedded, so they open in a new tab. Each video has a plain link underneath in case the player is blocked.

| Event | Videos |
|---|---|
| The wrong apartment | WFAA: Guyger's interview with investigators (link; not shown to jurors) |
| Fired | NBC News Nightly News; FOX 4 (links) |
| Trial begins | Prosecution and defense opening statements (Law&Crime Network, play here) |
| Guyger testifies | ABC News; NBC Nightly News (play here) |
| Jury instructions | WFAA: Judge Kemp reads the instructions (play here); WFAA closing-arguments report (link) |
| Verdict | The Washington Post (link); a news clip of the verdict being read (play here) |
| Ten years | ABC News: Brandt Jean says "I forgive you" (play here) |
| Appeals | Law&Crime: the 2021 appeal hearing (play here); WFAA report (link) |
| Bo's Law | KHOU (link); a committee-hearing report (play here) |
| Civil judgment | WFAA; CBS Texas (links) |
| Parole denied (2024) | WFAA, two reports (links) |
| Parole granted (2026) | CBS News Texas; FOX 4 (play here) |
| Released | CBS News Texas (play here); CBS Texas on her parole restrictions (link) |

**Notes**
- Publisher not confirmed for three videos (a clip of the verdict being read, a Bo's Law committee-hearing report, and the prosecution opening). The site labels these on the card.
- The police body-camera footage and the 911 call shown at trial are left out on purpose.
- If a publisher turned off embedding, or your school blocks YouTube, use the link under the player. News sites sometimes remove pages, so check links before the unit.

**To turn all videos off**, open `index.html`, search for `videos:true`, and change it to `videos:false`. The badges, Watch sections and Videos tab disappear. **To change a video**, search for `var VIDEOS=`. Each entry is either `yt:"VIDEO_ID"` (plays here) or `u:"https://..."` (opens in a new tab).

## Accuracy notes for the teacher (current to October 2026 reporting)

This is a real case about a real death, so please skim these. Facts come from the sources listed under Toolkit, then Sources, restated in our own words. Where sources disagree, the site says so or uses a range.

**Things to double-check or watch for updates**
- **Parole and release.** Parole granted Oct. 1, 2026, and release Oct. 16, 2026, from the Christina Melton Crain Unit in Gatesville (CBS Texas, NBC News, KERA, FOX 4, Dallas Morning News). On Oct. 16 CBS Texas reported her conditions, citing TDCJ: regular check-ins, home visits and employment requirements; no living in Dallas County; no contact with Jean's family or Dallas police officers; no leaving Texas without approval. Supervision runs until her sentence expires in 2029. The Jean family's lawsuit against the City of Dallas (filed in March 2026) was pending in October 2026. Check for anything newer.
- **The 2024 denial** was on Oct. 10, 2024, with the next review set for Oct. 2026 (WFAA, CBS Texas). An earlier draft said only "2024" because one outlet said September.
- **The civil judgment** was a federal civil rights case decided by a federal jury (FOX 4, WFAA): about $98.65 million, with roughly $60 million punitive and $38.65 million compensatory. Guyger did not take part in the trial.
- **Arrest.** WFAA says the Texas Rangers arrested her in Kaufman County; the Dallas Morning News says she turned herself in. The site says she turned herself in and was arrested there.
- **Length of her shift.** Reported as 13 to 15 hours. The site says "roughly 13 to 15 hours."
- **Deliberation times.** Verdict: roughly five to six hours over two days. Sentence: reports range from "a little over an hour" (ABC) to two hours (jurors on NBC), so the site says "roughly one to two hours."
- **Appeals.** Fifth Court of Appeals affirmed Aug. 5, 2021, and again after rehearing on Nov. 17, 2021. The Texas Court of Criminal Appeals refused to hear her petition in March 2022; two of its judges wrote dissents (WFAA).
- **Bo's Law.** Signed by Gov. Abbott June 16, 2021; effective Sept. 1, 2021. An earlier version would also have clarified the Castle Doctrine; the final law covers body cameras only (WFAA, Spectrum News).
- **Her relationship with Martin Rivera.** Covered on the trial-begins slide, with a sentence on the night-of slide. Sources: NBC News, CBS News, CNN and The Dallas Morning News. Rivera, her police partner (CNN describes him as married), acknowledged a sexual relationship and sexually suggestive messages that day, but testified they were no longer intimate and had no plans to meet. The defense said the relationship was "ramping down" and irrelevant. Prosecutors said she was on the phone with him for 16 minutes as she drove home and that she texted him "I need you. Hurry" while on with 911. The messages were deleted the next day and later recovered. The site paraphrases the explicit message text rather than quoting it.
- **Wikipedia** is cited for a few facts (such as that she was the first Dallas officer convicted of murder since 1973). Worth confirming if you plan to quote them.

**Texas law, with statute references**
- Murder, capital murder, manslaughter, criminally negligent homicide, and sudden passion: Penal Code ch. 19 (§19.02(d) for sudden passion).
- Punishment ranges: murder 5 to 99 years or life (§12.32); sudden passion and manslaughter 2 to 20 (§12.33); state jail felony 180 days to 2 years (§12.35); capital murder is life without parole or death (§12.31).
- Castle Doctrine and no duty to retreat (2007): Penal Code §9.32.
- Parole eligibility for murder (a "3(g)" offense): half the sentence or 30 years, whichever is less, minimum 2 years, with no good-conduct credit toward that half. Other offenses: one-fourth or 15 years, counting good conduct. Government Code §508.145.
- "Texas has no degrees of murder": supported by the Penal Code and by Recording Law's 50-state comparison, which also lists Indiana, Kentucky, Maine, New Jersey, North Dakota and South Carolina as having no degrees. The site is careful not to claim Texas is unique in that one respect, and points instead to the combination of features (sudden passion at punishment, jury sentencing by the defendant's choice, the Castle Doctrine, and the half-sentence parole rule).

**What I could not find**
- **A murder-only average sentence for Texas.** TDCJ's annual Statistical Reports group all homicide convictions together. The Sentencing tab therefore compares 10 years with the legal range, what prosecutors asked for, TDCJ's average for all violent crimes (10.2 years for new prison admissions, FY 2025), other North Texas officer cases (Roy Oliver, 15 years for murder; Aaron Dean, 11 years 10 months 12 days for manslaughter), and says plainly that a murder-only average was not available. It frames "typical" as a research question and includes an optional research challenge.
- **TDCJ figures.** Comparisons use FY 2025 data. Life sentences are counted as 60 years when TDCJ computes averages.

## Content note

The cover asks students to treat Botham Jean, his family, and everyone affected with respect. Descriptions of the shooting are brief and not graphic. Opinion questions ("Do you agree...") get balanced context (prosecution, defense, jurors, the Jean family) and do not point to an answer.

## Files

- `index.html`: the whole site (one file).
- `text-assignment/`: your original Word assignment.
- `example-output/`: a sample finished essay (fictional student).
- `screenshots/`: a gallery of what the site looks like.
