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
