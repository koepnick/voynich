# Fonts

Yeah. I know. Yet *another* set of VM fonts. 

## Why do this?

I've been trying to get a handle not only how the document was transcribed, but also what kind of glyphs the copyists had intended to create. Put another way, did their pre-existing pen motions affect the shapes of the original document?

My goal is to create 3 fonts. One is a sort of logical or Platonic ideal for the glyphs. Another is a human readable, monospaced font. The final will be a font that stays as close to the original look and feel as possible. The idea being that the glyphs assigned to each code point will be the same, so one could simply swap fonts to shift between differing presentation styles.

## Challenges

* Situational ligatures
* Re-composing compound glyphs. Perhaps using dedicated shapes in higher UTF code points.

## Tools

* [Inkscape](https://inkscape.org/)
* [FontForge](https://github.com/fontforge/fontforge)
