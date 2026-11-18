# Boards shown to the class

The topic boards of the Kant Lab's [Logic Portal](https://mikrishnan.github.io/kant-lab/logic-portal/)
that their owners have shown to the class. Each is one file, `<number>.json`, named by the board's
four-digit number, and holds a copy of a shared board **locked with the class password**
(AES-256-GCM, the key made from the password with 600,000 rounds of PBKDF2-SHA-256, as the
portal's handouts are). Without the password the files read as nothing.

To look at one, open `https://mikrishnan.github.io/kant-lab/logic-portal/topic-board.html#look=<number>`,
or type the number into the portal's My topics, under *Shown to the class*, and give the class
password. It can be looked at there, not changed.

The files are written by the portal, from the page of whoever may change the board, a few seconds
after each save. Don't edit them by hand. The board itself is kept in its own private repository
in this organisation. *Stop showing it*, in the board's *Who has it…*, deletes its file here, but
this repository's history keeps the copies sent, still locked.

How it works: the portal's README, [Sharing a board](https://github.com/mikrishnan/kant-lab/blob/main/logic-portal/README.md#sharing-a-board).
