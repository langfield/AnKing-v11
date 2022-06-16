Introduction
------------
This is a stress-test upload of the AnKing-v11 deck in the form of a git
repository generated with [ki](https://github.com/langfield/ki).

It can be imported by installing ki, cloning your local Anki collection, and
adding this deck as a git submodule. For information on how to do this, see the
[documentation](https://langfield.github.io/ki/).

AnKing is already large enough that I’ve got to shard the media directory
across multiple commits to get around Github’s pack size limit for pushes, and
I’m not even sure if clones will work, but we’ll see. They probably ought to be
shallow clones, or perhaps it doesn’t matter if the media files don’t get
messed with very often.

**Update**. Clones of the full 6.5GB repository (including .git) work without any
shallow/partial trickery. Ha! Github is quite generous. Without the .git
folder, the repository is roughly 500M larger than the downloaded .apkg file,
so still under 4GB.

The AnKing deck’s git repo representation has roughly 68k files, about half of
which are media. Without media files, this thing would be exceedingly
manageable and clones and installs would be pretty damn fast. I may look into
options for keeping media files out of the version history for large decks, but
for now it’s fine. The clone is actually reasonably fast. Certainly not more
than an order of magnitude longer than a download from Google drive.

It goes without saying, but I did not create this deck. See below for the list
of contributors.

Contents
--------
This deck is a comprehensive deck for USMLE Step 1. It combines the best parts
of Lolnotacop and Zanki with images from the Pepper micro/antimicrobial and
UltraZanki decks. It is re-organized and probably the best organization
currently available. It is also forever updatable so we as a medical school
community can continually update it for new content.

Contributors
------------
```quote
The entire AnKing team.

Main decks: u/ZankiStep1, u/bluegalaxies, u/lolnotacop, u/DerpyMD,
u/Jonathan\_Hermes, the creator of the Pepper decks, u/dorian222,
u/Cheesy\_Doritos, u/Numerous\_Birds

Add-ons: u/trustmeimnotadick, u/glutanimate, u/ArthurMilchior, u/truthling,
u/hgiesel

Tagged 50+ videos or made other significant updates: u/DocBrk,
u/DoctorToBeIn23, u/drmxyzptlk13, u/thedream95, u/dollajas,
u/environmental\_box\_47, u/hoosier7923, u/MagnetoMed169, u/nw\_throw,
u/TrickyTopic4u, u/pineapples9, u/PM\_ME\_YOUR\_EXERCISE, u/sleepygary15, Jabran
Westi, Ayan, u/Physeo

Tagged 20+ videos: u/WutsDatBud, u/anbu5000, u/BlazinWaffles, u/iherwis,
u/kushapatel07, u/noodlz\_synthetase u/USMLEACER, u/strangerorbitalrings

u/94j96, u/alwayshungry\_med, u/amazeum, u/Anki\_Kong, u/ausernameisoverrated,
u/byron2130, u/FamiliarEffective, u/FobbitMedic, u/GodIHateShakespeare,
u/hippocampus3, u/HYTriangleking, Jesse Simon, u/joejoeMD, u/Joshausha,
u/KingdomofBrohan, u/MadAboutMedicine, u/MHND, u/mittahrodgers, u/MozamBosque,
u/nagatomd, u/neovanilla, u/nmwwinicki, u/NoPerspective93, u/psbd18,
u/pyruv528, u/Ranim\_Naoum, u/RapheObscurus, u/Regular-opinion, u/RockChalkJDoc,
u/stickyjon23, u/StookDog, u/usmle\_india, u/WikKnows, Yasmeen

And the many people who elected to remain anonymous or submitted errata and
helped fact check changes!
```
