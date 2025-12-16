# MIDI 1.0 Messages Demystified

The resources in this repo untangle the essentials of the MIDI 1.0 standard for beginner musicians and aspiring instrument makers.

The mental model is that of a musician-producer who uses MIDI to play and write music. To my peers and me, it functions as a real-time notation language for both the score and its interpretation, grounded in music theory, and intelligible to both humans and machines. 

I encourage developers to approach MIDI with this mindset if they want to avoid writing wonky programs that are hostile to musical practice and culture. It means, among other things, not trying to replace MIDI, not hiding it under too many layers of abstraction, not converting it—and introducing errors from bugs and rounding—but instead passing it through as is, without changing the order of the messages (the latter amounts to rewriting the score, which is obviously unacceptable). I’m looking at you VST3.

[MIDI 1.0 Messages Demystified](https://docs.google.com/document/d/1mNEl-4xRUtdilLxmV_6JKfgVAksGtDIJLRqTvIcyQwY/): lists and briefly explains the different MIDI messages

[MIDI 1.0 CC Cheat Sheet](https://docs.google.com/spreadsheets/d/1dl6iuqFCuGr4E6kiuZF266JmtjZGssYR-wN0yGWjE9w/): lists the 128 Control Change messages, along with related information
