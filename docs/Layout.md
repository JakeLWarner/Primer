# Layout

While 

## Canvas

Whether a page in a document, a webpage, or a screen in an interface design

### Hierarchy

Gestalts. Foreground & background. Big, medium, and small. Color/contrast.

#### Modular scale

A modular scale can be a good way to guarantee sufficient contrast between two type treatments.
As a computer scientist, you probably feel a strong urge to base everything around mathematical relationships.

Butterick (2018) derides their usage because one shouldn’t “try to resolve typographic decisions with logic.” There’s merit to the sentiment – just because something is mathematically perfect doesn’t mean it’s aesthetically pleasing – but a modular grid can be a useful tool to ensure that the size of every element is meaningfully distinct. Butterick recommends making adjustments “with the smallest visible increments”, but in practice, this can lead to an unclear hierarchy. As a rule, if you’re going to make two elements different, make them obviously different.

Modular scales can also break down when combining differently proportioned typefaces. As I noted earlier, fonts most often appear different at the same point size.

### Whitespace

Whitespace can be used to emphasize. Whitespace is not only present in mar-gins and gaps between content, but also within content in the form of letterspac-ing and line height.

#### Margins

Don’t be afraid of wide margins. Remember appropriate text measure.

At the same time, if you are designing for a narrow screen like a mobile phone, it’s often best to shrink the side margins to a few percentage points of the screen width. On small screens, you should pay close attention to the space between successive paragraphs, as it will likely be the most prominent use of whitespace on a page of running text.

### Grids

Organizational tool. “The grid system is an aid, not a guarantee. It permits a number of possible uses and each designer can look for a solution that is appropriate to his or her personal style. —But one must learn how to use the grid; it is an art that requires practice.” Josef Müller-Brockmann.

#### Block grids

The simplest kind of grid is one in which a single block of text is floated somewhere on a page. It basically represents the inverse thinking as setting the margins – working from the text outward, rather than from the page inward.

If you’re designing for the web, you can achieve a simple yet typographically sound block layout using the following 58 bytes of CSS:

On the web, you can also use a block grid for your main text content, but use the full screen width for headers, footers, images, etc.

Activate the margins with sidenotes, runners, page numbers.

#### Column grids

The canvas is divided vertically but not horizontally. This can be useful for documents in which the content types are simple, and on screens, where the canvas can scroll infinitely in the vertical direction.

This is what I typically use on websites where the content is likely to vary, such as images of different aspect ratios.

#### Modular grids

Modular grids can help you organize a lot of predictable content.

To be typographically successful, modular grids need to encompass another kind of grid that I have yet to discuss: the baseline grid. This special kind of grid provides granular divisions in vertical space for text to sit on top of. So, for example, in text with a 17pt line height, your baseline grid would increment every 17 points (or every 8.5 points if you want more flexibility). A baseline grid is good for aligning text across multiple columns or on the reverse side of a double-sided print, and many design programs make them easy to use. But in UI design, there is little support for baseline grids, and in development, they’re usually more trouble than they’re worth. Screens can scroll vertically to infinity, but it’s rare to scroll horizontally; and users are not especially concerned with the alignment of text across successive pages of your website or app