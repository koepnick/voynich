# Welcome!

Welcome to the one jillionth set of Voynich Manuscript (VMS) odds and ends.

## Why?

I've been wanting to do this for awhile but have been hesitant to deviate from the community accepted transcription philosophy.

But here we are...

A lot of the analytics that I want to perform require data structures and metadata not captured by the current EVA standards.

* Decompose and/or flatten arbitrary strokes and glyphs.
* Glyph rotation.
* Dynamic "word" definitions.
* Completely ignore color.
* Render a logical[^1] version of the manuscript.
* Support stroke simulation.
* Discrete illustrations with shared text. Eg. the text found in an illustration should be directly queryable from the document.

## Shouldn't You Just Contribute to XYZ?

Probably.



![](https://imgs.xkcd.com/comics/standards.png)

But I wanted to ensure that my requirements were first-class citizens.

I wanted to make this as object-oriented as possible.

There are aspects, such as dynamic font generation, etc., that would likely be seen (and correctly so) as adding unnecessary complexity to existing projects.

# Disclaimer

I'm treating this as a personal project and have no idea how much time and energy that I'll be able to devote to it. I'm putting the code and assets up as a way of ensuring that the community has access in case any of it turns out to be useful.

Everything here is tested in Debian Linux running Python 3.12. Everything should, *in theory*, be portable. But I don't use Windows or Mac and have zero intention of searching for or fixing their little idiosyncracies. 

[^1]: The difference between a line schematic of the London Underground vs. a standard map of the city.
