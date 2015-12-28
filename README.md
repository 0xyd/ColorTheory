# ColorTheory
Note of Color Theory

### Basic Color

There are three ways to describe colors: according to their names, how pure they are and how desaturated(去飽和的) they are. 

We often use Chroma(濃度), Intensity, Saturation and Luminance(亮度) used for describing colors.

![chroma](https://raw.githubusercontent.com/yudazilian/ColorTheory/master/src/ChromaExample-Red.png)

Chroma: How pure is the hue in relation to gray.

![saturation](https://raw.githubusercontent.com/yudazilian/ColorTheory/master/src/SaturationExample-Red.png)

Saturation: The degree of purity of a hue.
Intensity: The brightness or darkness of the hue.
Luminance: How much light will reflect from a hue. A Hue with white content has higher luminance.

Tint and Shade are variation of hue.
Tint: Color with more white addition
Shade: Color with more black addition

![Tint & Shade](https://raw.githubusercontent.com/yudazilian/ColorTheory/master/src/TintShadeExample-red.png)

The middle is a pure red (rgb(255, 0, 0)) and it changes its color gradully to left and right directions.
While the color moves to the left side, the red mixes with more white which make it looks brighter.
Meanwhile, the color looks darker when it is approaching to the right side where it earns more black every single step.

### Color System

For the painters who make the artworks in traditional ways like painting, they prefer to use *Subtractive Color* method to acheive the mixed color they want. For those who works with computer to create digital art works like UI/UX Designers, colors are achieved by *Addition Color* method.

#### Subtractive Color Method

The definition of Subtractive Color method we found at [Wikipedia](https://en.wikipedia.org/wiki/Subtractive_color) is "A subtractive color model explains the mixing of a limited set of dyes, inks, paint pigments or natural colorants to create a wider range of colors, each the result of partially or completely subtracting (that is, absorbing) some wavelengths of light and not others." In other words, the color starts from white and end with black and when we add more hues, it is closer to black which, in physics field, can be explained that the some light waves has been filtered while adding other hues.

[RYB Color Mode](https://en.wikipedia.org/wiki/RYB_color_model) is a set of colors has been used in substractive color mixing for a long long while. RYB is an abbreviation for three colors: Red, Yellow and Blue which are also the primary colors in painting field.

RYB has not been replaced on color printing industry until mid-20th the more versatile color mode (CMY Color Mode) has been widely adopted in commercial printing. CMY Color mode is popular known as [CMYK model](https://en.wikipedia.org/wiki/CMYK_color_model) which is another subtractive color method. 

![cmyk](https://upload.wikimedia.org/wikipedia/commons/f/f7/CMYK_color_swatches2.png)
Cyan, Megenta, Yellow and Key(Black)

![CMYK color plate](https://upload.wikimedia.org/wikipedia/commons/1/19/SubtractiveColor.svg)

CMYK is an abbreviation of four colors: Cyan(青色或藍綠色), Magenta(洋紅), Yellow(黃色) and Key(black). As the RYB does, CMYK masks the light. The ink reduces the light that would otherwise be reflected. Simply to say, the ink subtracts the color from white.

[Halftone (半色調)](https://en.wikipedia.org/wiki/Halftone) method is the reprographic technique that simulates continuous tone imagery through the use of dots. By varying the dots in size or in spacing, Halftone can create gradiant like effect once the observers standing from the sufficient distance. How come the Halftone generate continous hue changing with incontinous dots? It's a matter of our brian cheated by optical illusion. The human brain will smooth the white space with the surrounding dots' color if human eyes can not identify the dots clearly. 



