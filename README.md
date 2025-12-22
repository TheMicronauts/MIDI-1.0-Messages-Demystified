# MIDI 1.0 Messages Demystified

I created the resources in this repository as a vade mecum that cuts through the noise and untangles the essentials of MIDI 1.0.

My daughter found it useful when she started producing music. Hopefully, other musicians, students, aspiring instrument makers, or coders will find them just as helpful.

The resources in this repository untangle the essentials of the MIDI 1.0 standard. 

I originally created them for my daughter, but any beginner musicians, aspiring instrument makers, or coders may find them just as helpful.

[MIDI 1.0 Messages Demystified](https://docs.google.com/document/d/1mNEl-4xRUtdilLxmV_6JKfgVAksGtDIJLRqTvIcyQwY/): lists and briefly explains the different MIDI messages and their format

[MIDI 1.0 CC Cheat Sheet](https://docs.google.com/spreadsheets/d/1dl6iuqFCuGr4E6kiuZF266JmtjZGssYR-wN0yGWjE9w/): lists the 128 Control Change messages, along with related information

The mental model is that of a musician-producer who uses MIDI to play and write music. 

In this model, MIDI Messages constitute a real-time notation language for both the score and its interpretation, grounded in music theory, and intelligible to both humans and machines. 

I encourage developers to adopt this model if they want to avoid writing wonky programs that are hostile to musical practice and culture. Changing the messages via abstraction or conversion bugs and rounding errors, or changing their order amounts to rewriting the score, which is obviously unacceptable (I’m looking at you VST3).
