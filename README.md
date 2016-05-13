# twiddler-configs and cheat sheets

This repo holds my [Twiddler3](http://twiddler.tekgear.com/) keyboard
config file as well as cheat sheets for some different Twiddler3 key
configs listed below. Each is exemplified by the first block from
their cheat sheet. Hope the sheets are useful to someone!

## Default

![defaultimage](img/default.png)

This is the default keyboard layout coming with the Twiddler since 20
years or so.  Its letters are ordered alphabetically which makes it
pretty easy to learn while maybe being less than optimal for
touch-typing (but then again, neither is querty). It is widely used.

## TabSpace

![tabspaceimage](img/tabspace.png)

This custom layout was made by Brandon Rhodes in 1999 and changes the
default in many ways. Notably it optimizes the letter distribution for
how often they are used in English. It centers around using the index
finger as a common qualifier and moves the TAB key to make the layout
more useful for a programmer/terminal user. This is a popular
alternative, even linked to from the Twiddler documentation.  Brandon
discusses the layout and its ideas at length 
[in this PDF](http://rhodesmill.org/brandon/projects/tabspace-guide.pdf).

## BackSpice

![backspiceimage](img/backspice.png)

User Alex Bravo started from TabSpace some years ago and made his own
modifications until the two shared little resemblance. He apparently
uses backspice every day to good results. The cheat sheet is for the
"full" backspice layout rather than the "simplified" one without the
N-grams. You can get the latest backspice config and read more
information 
[at his github reposity](https://github.com/AlexBravo/Twiddler). Note
that there may still be changes happening to the config, at which
point this sheet may not be completely accurate. 


## DelEnt

![delentimage](img/delent.png)

This was my first own keyboard layout, named after the Del and Ent
keys being next to each other. This was done by starting from an empty
layout (so *not* from TabSpace or Default) and order the letters by
frequency in English according to where my fingers felt most
comfortable to reach. The config grew from there. 

While I'm both a Unix user and a programmer, my main use of the
Twiddler is for writing text when on the move (usually "blindly", with
the phone tucked away in a pocket). So this layout does not have much
focus on programming/terminal use - contrary to the other layouts the
Tab key is pretty well tucked away, for example. 

I also have rather short fingers which influenced where various common
keys ended up and which types of finger-combinations are allowed. This 
tended to make for a pretty clean presentation which helped me remember
it visually. 

## TeaSan

![teasanimage](img/teasan.png)

This is a development of DelEnt I'm currently trying (the name is from
the letters "tea" crossing "san" on the first cheat-sheet block). 

Compared to DelEnt, TeaSan reshuffles the letters based on where I've
experienced them to feel the most comfortable during testing (so a
very subjective thing obviously). It also moves the Del key to
Shift+BS which means I could move the common letters "i" and "n" up a
bit so less work is done by the pinkie. 

TeaSan also removes a lot of trigrams (only leaving the 3 most common
ones) to make it easier to remember (the DelEnt ones had a lot of
overlaps with digrams, I found). It also makes the digrams appear
clustered in a (mostly) more logical way based on their first letter.
I may expand with more N-grams later, we'll see.

## Cheat-sheet template

![defaultimage](img/template.png)

This is an empty SVG template I start from when planning out a new
layout. It's quite nice for making/presenting your own Twiddler config
in a nice way. It's meant to be printed and folded once or twice so
you can to carry it with you for easy reference.

The template and all cheat-sheets were created in the OSS program
[Inkscape](https://inkscape.org/en/). The sheets are in color but the
colors are chosen such that they will present very clearly also in
black&white. Use as you please!

The PDFs I made are ISO A4 format. If you prefer another paper format,
you can always change the document type of the corresponding SVGs in
Inkscape and print that.
