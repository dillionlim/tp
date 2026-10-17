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

Kept on a branch of the fork so that they are not committed to the team
repository.
