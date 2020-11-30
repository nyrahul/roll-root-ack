# RPL Storing Root Ack

This is the working area for the individual Internet-Draft, "RPL Storing Root Ack".

## Draft Abstract

This document explains problems with DAO-ACK handling in RPL Storing MOP and provides updates to RFC6550 to solve those problems.

* [Editor's Copy](https://nyrahul.github.io/roll-root-ack/#go.draft-jadhav-roll-storing-rootack.html)
* [Individual Draft](https://tools.ietf.org/html/draft-jadhav-roll-storing-rootack)
* [Compare Editor's Copy to Individual Draft](https://nyrahul.github.io/roll-root-ack/#go.draft-jadhav-roll-storing-rootack.diff)

## Building the Draft

Formatted text and HTML versions of the draft can be built using `make`.

```sh
$ make
```

This requires that you have the necessary software installed.  See
[the instructions](https://github.com/martinthomson/i-d-template/blob/master/doc/SETUP.md).


## Contributing

See the
[guidelines for contributions](https://github.com/nyrahul/roll-root-ack/blob/master/CONTRIBUTING.md).

#### Discussion of Root-ACK in ROLL-WG - (Thanks Dominique Barthel for compiling this)
Following our ROLL session at the IETF109 meeting, I had an action point to dig up pointers to prior discussions about DAO/DAO-ACKs in storing mode and the decision to go for a RootACK.

If you want only one pointer, that would be the video of the ROLL session at the IETF103 meeting https://youtu.be/7cwhMLaddqU?t=3408 , (start time 56:45, duration about 6 mn).

More pointers below
- discussions on ML about interpretation of DAO-ACK behaviour, e.g. as far back as 2015
  https://mailarchive.ietf.org/arch/msg/roll/8jf7B4O_SSz575fjv59EMH2xs7g/
- description of the issues in draft-ietf-roll-rpl-observations, Section 4, first published in Sept 2018
  https://tools.ietf.org/html/draft-ietf-roll-rpl-observations-04
- ROLL session at IET103 meeting (Nov 5, 2018, Bangkok)
  slides: https://datatracker.ietf.org/meeting/103/materials/slides-103-roll-roll-ietf103-v2-00.pdf
  minutes: https://datatracker.ietf.org/doc/minutes-103-roll/
  Excerpt “Pascal: we could specify a mechanism to get an ACK from the root all the
  way down the DODAG. Could be a new draft. ACTION: new draft on ACK from the root?”
- Video: (from time 56:45, about 6 mn) https://youtu.be/7cwhMLaddqU?t=3408
- ensuing draft https://datatracker.ietf.org/doc/draft-jadhav-roll-storing-rootack/ first published Apr 2020
