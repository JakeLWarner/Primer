# Typography

Typography – that is, the way you use type^1 – is one of the most important tools at your disposal for effective communication. Good typography can engage and persuade, command and direct attention, convey emotion and set the tone for a design. On the other hand, typography can work against you if it is not treated with care, much like how an actor’s poor performance can make a mockery of a well-written script.

<aside>1 Some prefer a more abstract definition. Robert Bringhurst (2012) calls typography “idealized writing” and “the craft of endowing human language with a durable visual form.” Ellen Lupton (2010) writes that “typography is what language looks like.” And Matthew Butterick (2018) holds that “typography is the visual component of the written word.” See *Appendix 6.1: Further reading* for more.</aside>

As with most creative endeavors^2, there are few hard-and-fast rules to working with type; the most important things are to understand the tools and conventions, and to always make deliberate decisions. These tools and conventions have been honed over centuries by studied designers, and to paraphrase Paul Watzlawick, you cannot not practice typography – you can either do it well or do it poorly. Thus, to shirk or abstain from this decision-making process is to do your audience, and yourself, a disservice.

<aside>2 For a non-exhaustive list, see https://practicaltypography.com/summary-of-key-rules.html</aside>

## Letters & words

It’s tempting to assume that good typography is as simple as picking the font that contains the nicest letters. While most of your decisions will take place above the level of individual letters, it can be helpful to start here since they are the atomic units of text. 

### Proportion

There are technical terms for near every part of a letter, but I want to encourage you to develop a useful mental model based on proportions. x-height, font size

Most fonts have a sweet spot for font size. If you’re young, keen of vision, and working on a high-quality computer monitor, then it’s probably larger than you’d expect – especially for larger screens like laptops and desktop monitors, where users can’t always “zoom in” by bringing the device closer to their face.

### Legibility

We read by perceiving word shapes. Factors that can aid this include distinct letterforms (especially for sans-serifs: I, l, and 1), open apertures, stroke contrast, serifs, etc.

Lowercase creates more distinctive word shapes than uppercase. “When we read longer text, we don’t look at individual characters; we recognize whole word shapes and see what we expect to see” (Spiekermann, 2003). Helvetica.

### Letterspacing & kerning

“Don’t letterspace lowercase…stealing sheep”. This is generally good advice, unless you really know what you’re doing. Text fonts can have their letterspac-ing condensed by 1–2% when used at display sizes (see Apple Dynamic Type and Inter UI Dynamic Metrics). Small text can benefit from additional letter-spacing as well – the footnote and caption text styles in JDF have their letter-spacing expanded by 0.15pt. And some fonts can benefit from additional letter-spacing when used in running text, like Helvetica as I mentioned earlier. Sometimes I add 0.5% letterspacing to Palatino for running text, as I have done here – its designer, Hermann Zapf, preferred it as a display typeface and spaced it accordingly – but this is not done in JDF since letterspacing is not possible in Google Docs.

You should letterspace text set in uppercase by 5–12%. In JDF, for example, Heading 1 is set in all caps with 5% letterspacing added (expanded by 0.55pt for 11pt text). 

Use kerning whenever possible. In Word, Format > Font > Advanced > Turn on “Kerning for fonts 8pt and above”. In CSS:

### Fonts

As I said, typography is fundamentally not about fonts, but about how you use them. However, without good fonts, good typography would not be possible. And make no mistake, there are tiers of quality when it comes to fonts.

#### Professional fonts

Buy them. If your employer or institution (or you personally) subscribes to Adobe Creative Cloud, then you have access to an incredible library of high-quality professional fonts through Adobe Fonts.

#### System fonts

You can practice good typography with system fonts. Here are some tips.

Choose typefaces for specific applications. For example, while Helvetica may not be the best choice for running text due to its tight spacing and uniformity, but it can be used well in large sizes for headlines, or for short phrases of UI text.

Use each font at only one or two different sizes. Professional fonts come with optical sizes, which have design compensations for rendering at different sizes. Generally, as you go up in size, contrast is increased, widths are narrowed, x-heights are shrunk, and extenders are lengthened. This allows for more elegant presentation. At the time of this writing, no system fonts come with optical sizes. So your best bet is to use a given typeface at only one size – ideally the size for which it is optically tuned – lest your readers should notice its deficiencies at an ill-fit size. There is an anchoring effect wherein the first context a user en-counters a typeface is given grace and assumed to be a good use of the type, but additional contexts are more heavily scrutinized.

Create harmonious pairings – see section 2.5.

#### Free fonts

### Classification & pairing

The principal occupation of typography is use, not definition, and in this sense it is important not to get bogged down by the minutiæ of type classifications. Classification is only useful inasmuch as it can help you form a mental model conducive to typeface selection and pairing. 

There are many type classification schemas that each promise varying levels of usefulness and fidelity. Some are purely prescriptive, focusing on the immutable traits like date of design. For example, Bringhurst classifies typefaces based on their history. Others are purely descriptive, lumping typefaces together based on shared traits. While it can often be useful to know a typeface’s history and likeness to archetypal historical forms, I prefer the latter approach. I favor the variant of the Vox ATypeI classification schema used by Pohlen (2010).

Shoaf (2017) says to focus on the degree to which the letters seem handwritten ver-sus constructed. Draw continuum/number line for serif and sans-serif 

When choosing typefaces, it can be helpful to think about how modern you want your design to look and selecting a typeface from the appropriate category. To pair multiple typefaces, just look down the chart and choose a typeface from the opposite category that falls in a similar place between written and constructed: for example, a Garalde and a neo-humanist, or a Clarendon and a neo-grotesque. This is not the only way to select typefaces, but it’s a safe bet. Relying on harmony rather than contrast.

#### Serifs

Serifs are the small perpendicular strokes at the ends of the letter.

> “Serifs – those little entry and exit strokes through which the writing hand and the reading eye like to find their way into and out of a letterform – are also a means by which letters tie themselves into a line: a form of graphic social bonding. They are as old as the letters themselves; but sanserif letters – the socially disengaged – are no younger.” —Bringhurst 2018

##### Humanist

Closest to calligraphy. Letters look like they were written with XX pen. These are often lumped together with Garalde types under the moniker “oldstyle”. Examples include Centaur, Gentium, and Alegreya (pictured).

##### Garalde

Examples include Palatino, Garamond, Hoefler Text, and Iowan Oldstyle (pictured).

##### Transitional

Examples include Baskerville, Perpetua, and Times New Roman.

##### Clarendon

Because of these characteristics, Clarendon types are often useful in designs intended for the screen. Examples include Century Schoolbook (pictured), Georgia, Charter, Source Serif, and Merriweather.

##### Modern

Examples include Didot and Bodoni* (pictured).

##### Slab serif

Slab serif, or Egyptian, types are united by their thick, rectangular serifs and complete lack of stroke contrast. Other than this, their forms can vary greatly, so it can be useful to think of them as sanserif letterforms (of any kind) with the addition of slabs. Examples include Rockwell, Roboto Slab, Arvo, and Plex Serif (pictured).

#### Sans-serifs

Squared or rounded stroke endings

#####  Humanist

Examples include Optima, Gill Sans (pictured), Alegreya Sans, and Fira Sans.

##### Neo-humanist

Examples include Lucida Grande, Segoe UI, Ubuntu (pictured).

##### Grotesque

Examples include Franklin Gothic and Source Sans (pictured).

##### Neo-grotesque

Neo-grotesque types have become the weapon of choice for many major companies in their brands and digital products. They are often, but not always, more squared than grotesques. Through their ubiquity, they have come to read as neutral in these applications, so they can be a great choice for applications where you want the typography to blend in rather than stand out. Examples include Helvetica, San Francisco, Roboto, Inter UI, and Cooper Hewitt (pictured).

##### Geometric

Examples include Avenir, Futura, Montserrat, and Nunito.

#### Monospace

Monospace types are those in which all letters occupy the same horizontal space. They are frequently used to display code or in designs that hearken back to the typewriter. Generally, these can be classified according to the same traits as sans-serifs. Examples include Courier New, Source Code, Roboto Mono, Fira Code, and Plex Mono.

#### Display fonts

Broadly speaking, display fonts are those designed to be used in large, decora-tive applications. They vary greatly in design, from Medieval-looking blackletter to elegant inscriptional capitals that you might find at the base of an ancient Roman column to formal and casual scripts.

## Sentences & paragraphs

As you practice typography, you will inevitably move beyond letters and words, and work on their assemblage. Avoid “walls of text.” etc.

### Line length

Measured in characters, including spaces and punctuation – referred to as measure. When the measure is too wide, it is difficult for the eye to jump from the end of one line to the beginning of the next. Often you’ll jump an extra line or end up re-reading the line you just read. Various sources recommend between 50–80 characters per line for text with a single column, with 66 being the ideal recommended in The Elements of Typographic Style by Robert Bringhurst:

> “Anything from 45 to 75 characters is widely regarded as a satisfactory length of line for a single-column page set in a serifed text face in a text size. The 66-character line (counting both letters and spaces) is widely regarded as ideal. For multiple column work, a better average is 40 to 50 characters.” (Bringhurst, 2012).

### Line height

The amount of leading you use will vary based on the line width, font size, and proportions of a given typeface. Generally:

*	Longer line lengths call for greater line heights, while shorter lines need less;
*	Smaller text calls for greater line height, while larger text needs less;
*	Fonts with large x-heights call for greater line heights, while fonts with smaller x-heights need less. 

For a 66-character line width at a normal font size, Matthew Butterick (2018) recommends a line height 120–145% of the font size – but he was referring to print work. For screens, a line height up to 160% can read more comfortably, as seen on the online publication Medium.

### Justification

Ladders, rivers, pigeonholes, bad breaks – as Bringhurst (2012) would describe it, “text full of birdshot and wormholes”.

#### Hyphenation

Hyphenation can help create a more even rag in left-aligned text, or more even spacing between words in justified text.

#### Orphans & widows

Don’t worry about these on the web.

### Headings

Most papers will only need three levels of headings. These docs provides a fourth level, which is a run-in-sidehead that encourages use as a glorified list rather than a new hierarchical level.
No need for huge, colorful headings. Do just enough to set them apart. “When your text is set in a 12 pt medium roman, it should not be necessary to set the heads or titles in 24 pt bold italic capitals” (Bringhurst, 2012). 

Write descriptive headings. Use sentence case, not title case, for headings – they are text, not titles. In this template, all headings are set at the same size as body text in bold, providing a sufficient amount of contrast to make them easily scannable. Heading 1 uses letterspaced capitals, Heading 2 roman, Heading 3 uses italic, and Heading 4 is a run-in sidehead.