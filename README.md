# MIDI 1.0 Messages Demystified

I created this repository as a vade mecum untangling the essentials of MIDI 1.0.

My daughter found it useful when she started producing music. Hopefully, other musicians, students, aspiring instrument makers, and coders will find it just as helpful.

[MIDI 1.0 Messages Demystified](https://docs.google.com/document/d/1mNEl-4xRUtdilLxmV_6JKfgVAksGtDIJLRqTvIcyQwY/): lists and briefly explains the different MIDI messages and their format

[MIDI 1.0 CC Cheat Sheet](https://docs.google.com/spreadsheets/d/1dl6iuqFCuGr4E6kiuZF266JmtjZGssYR-wN0yGWjE9w/): lists the 128 Control Change messages, along with related information

The mental model is that of a musician-producer who uses MIDI to play and write music. 

In this model, MIDI Messages constitute a real-time notation language for both the score and its interpretation, grounded in music theory, and intelligible to both humans and machines. 

I encourage developers to adopt this model if they want to avoid writing wonky programs that are hostile to musical practice and culture. Changing the messages via abstraction or conversion bugs, rounding errors, or reordering amounts to rewriting the score, which is obviously unacceptable (I’m looking at you VST3).
