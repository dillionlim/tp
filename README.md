# Pull request screenshots

Images referenced from the v1.3 UI pull requests (#166–#169).

Every one was photographed on a virtual display (Xvfb, 998x731) running the
sample data the app ships, so the frames are the same size, carry no window
manager chrome, and differ only by the change under review.

| File | Branch |
| --- | --- |
| `00-before.png` | `master` |
| `01-theme.png` | the theme |
| `02-card.png` | the theme and the card |
| `03-sidebar.png` | the above and the sidebar |
| `04-commandline.png` | the whole stack, with a command typed |

## v1.4

Images referenced from the v1.4 pull requests (#172, #173). The card pair is
the same 998x731 virtual display; the command line pair is 850 wide, because
narrowing the window is what the change under review is about.

| File | Shows |
| --- | --- |
| `07-card-before.png` | two names agreeing over their first 22 characters, cut to the same text |
| `07-card-after.png` | the same two names cut from the middle, and a 23-character name left whole |
| `08-cmdline-before.png` | a long command after the window narrows: the copy stops short and no caret is drawn |
| `08-cmdline-after.png` | the same command and width, the copy following the field and the caret at the end |
| `09-narrow-before.png` | the same two names on a crowded row at a 520 px window, both drawn as the same text |
| `09-narrow-after.png` | the same, with the row's own cut taken from the middle so the two still read apart |

## v1.4 release notes

Images referenced from the v1.4 release notes, in `shots/release-v1.4/`. Each
is 900x690, photographed on a virtual display (Xvfb) running the sample data,
with `master` at `40372ee5` and #364, #366 and #368 merged in.

| File | Shows |
| --- | --- |
| `01-tag-add.png` | `tag 1 -a "Lab 3"` adding one tag beside an existing one |
| `02-tag-remove.png` | `tag 2 -r friends` removing one tag and keeping the rest |
| `03-duplicate-warning.png` | a second Alex Yeoh added, with the duplicate warning |
| `04-find-fields.png` | `find -n alex -t "lab 3"` matching both fields |
| `05-edit-by-id.png` | Charlotte edited by NUS Student ID while the search hides her |
| `06-delete-by-id.png` | Roy deleted by NUS Student ID while the search hides him |
| `07-did-you-mean.png` | `delte 3` answered with the command it was meant to be |
| `08-recall.png` | `Up` recalling the previous command into the command box |
| `09-help.png` | the command reference shown in the main window |

Kept on a branch of the fork so that they are not committed to the team
repository.

## v1.5

Images referenced from the v1.5 pull requests (#512, #513, #514, #527). The
diagram pairs are PlantUML 1.2024.7 renders rather than photographs; the
application shots were taken on a virtual display at 760x620, the width the
help pager and the start-up dialog are laid out for.

| File | Shows |
| --- | --- |
| `v1.5/483-before.png` | `BetterModelClassDiagram` with the hidden layout edge declared twice |
| `v1.5/483-after.png` | the same diagram with one declaration, drawn a little more compact |
| `v1.5/484-before.png` | the add duplicate check under `skin rose`, in yellow and pink |
| `v1.5/484-after.png` | the same flow under `style.puml`, and asking its question in the decision |
| `v1.5/492-before.png` | the help reference in one fill: headings, syntax and prose all alike |
| `v1.5/492-after.png` | the same reference carrying the command box's own colours |
| `v1.5/494-load-refused.png` | the start-up refusal when a data file holds `Needs follow-up` as a tag |

## v1.6

Images referenced from the v1.6 pull requests (#570). Both are the same
600x510 crop of a virtual display (Xvfb, 1400x900) showing the start-up
dialog over one data file, whose second student's name line carries a `//`
comment, with only the JAR under review changed between them.

| File | Shows |
| --- | --- |
| `v1.6/570-data-error-excerpt-before.png` | the quoted lines in the window's proportional font, their gutters in three columns |
| `v1.6/570-data-error-excerpt-after.png` | the same lines in a monospaced box, their gutters and indents in one column |

The pair for #691 is the student list panel alone, rendered at 320 wide, the
width the list has when the window sits at its own minimum. Eleven students
share one long name so the names compete with the index for the row, and the
index crosses from one digit to two. `master` is at `dbd0c0f8`.

| File | Shows |
| --- | --- |
| `v1.6/691-index-column-before.png` | names on cards 10 and 11 starting a digit's width right of those on cards 1 to 9 |
| `v1.6/691-index-column-after.png` | the same eleven cards with every name starting at one place |

The pairs for #707 are the whole window after one `add` of a student whose
email is long enough to wrap the contact row, photographed once the list has
stopped moving. The first pair is 740 wide by 600 tall over forty students,
the geometry the issue measures; the second is the same window at its minimum
height of 400 over ten students, where the card is in view for one pass before
it grows. `master` is at `63888d2d`.

| File | Shows |
| --- | --- |
| `v1.6/707-reveal-before.png` | card 41 cut off at the foot of the list, its email line against the edge |
| `v1.6/707-reveal-after.png` | the same card whole, its lower edge clear of the list |
| `v1.6/707-reveal-minimum-height-before.png` | card 11 cut off in the short window, the email line half drawn |
| `v1.6/707-reveal-minimum-height-after.png` | the same card whole, the list having scrolled a little further |
