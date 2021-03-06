# Color palettes

Although it is often not given much attention, choosing the right color palette can make a significant difference in how our work is received. In general terms, when choosing a color palette we need to think about two main, and often competing, interests: __functionality__, and __aesthetics__.

<hr>

##  Functionality

In science and engineering, the main objective should always be functionality. Most of the time we are trying to communicate difficult concepts to an audience that might not be that interested in figuring out the details of how to read the information we are trying to convey. In this sense, the first thing we have to take into account is wether we want to use a sequential, diverging, or categorical color palette.

### Sequential

Sequentiel palettes are great for data that does not require a broad spectrum of differentiation, or when the concepts it is trying to transmit is one-dimensional in nature (hot, cold, positive, negative quantities).

<a href="https://betterfigures.org/2015/06/23/picking-a-colour-scale-for-scientific-graphics/"><img src="../media/sequential.png" width="25%"></a>

### Diverging

Diverging palettes are great for when the data range is wide, or represents competing concepts in the same graph (hot/cold, positive/negative).

<a href="https://betterfigures.org/2015/06/23/picking-a-colour-scale-for-scientific-graphics/"><img src="../media/diverging.png" width="25%"></a>

It is important to keep the palette with the least amount of colors possible. An example of how not to define a diverging color palette follows:

<a href="https://www.kennethmoreland.com/color-maps/"><img src="../media/divergingNot.png" width="25%"></a>

This is because, from a viewers perspective, there is no clear relationship between the colors and the values. Despite it ranging through RGB colors, it is not clear which is a "low" value, and a "high" value given that green is in between them.

### Categorical

Categorical color palettes, as their name implies, are great for categorical data. An important note here is, that they should never be used for non-categorical representations because they are almost uninterpretable in those contexts.

<a href="https://betterfigures.org/2015/06/23/picking-a-colour-scale-for-scientific-graphics/"><img src="../media/categorical.png" width="25%"></a>

<hr>

##  Aesthetics

Although it is often neglected in science and engineering, aesthetics are important. Most of the default color palettes use some variation of the "complementary" (leftmost panel) or "triads" (rightmost panel) principle. This is a good way to make sure the colors are as differentiable as possible but, unfortunately, it does result in poor color combinations more often than not. A good compromise is to manually select colors that are "far apart enough", but that still match well with each other.

<a href="https://www.aje.com/dist/docs/Using_Color_In_Your_Manuscript_Figures.pdf"><img src="../media/triads.png" width="100%"></a>

<hr>

## Other Notes

Besides those two main points, there is a couple more things that might be worth taking into account when picking a color palette, or designing to avoid al the information being dependent on color.

### Projectors

Although we can't plan on every type of possible projector failure, we do need to factor in that, if we are presenting our work live, there's always the chance that things might go wrong and if our color palette is not wide enough, differences between tones might be blurred.

### Colorblindness

Designing for colorblindness is difficult. There are tools that can help us understand how differentiable our color palettes are, such as the one accessible through the link accessible by clicking the image:

<a href="https://coolors.co/edffec-6320ee-61e786-70a0af-494368"><img src="../media/colorblind.png" width="100%"></a>

<hr>

##  Resources

* <a href="http://colorpalettes.net/">Artistic Color Palettes</a>
* <a href="https://coolors.co/">Coolors</a>
* <a href="http://tristen.ca/hcl-picker/#/hlc/6/1/657D9F/E2E062">Color Picker for Data</a>
* <a href="https://cran.r-project.org/web/packages/ggsci/vignettes/ggsci.html">Sci-Fi Color Palettes</a>
* <a href="http://colorbrewer2.org/#type=sequential&scheme=Blues&n=7">Color Brewer for Maps</a>
* <a href="https://www.rdocumentation.org/packages/RColorBrewer/versions/1.1-2/topics/RColorBrewer">RColorBrewer Package</a>
