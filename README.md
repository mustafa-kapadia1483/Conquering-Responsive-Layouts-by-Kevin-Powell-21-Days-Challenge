# Conquering-Responsive-Layouts-by-Kevin-Powell-21-Days-Challenge-
## Day 1 Challenge 1: 
Learnt that html is responsive even without css, may not be the best looking but it is responsive and it is the css that we write that in turn causes issues with our web page being responsive. Never use fixed height and widths as it will force the content to overflow on certain screen sizes. It is best to use width percentages and resist having certain defined width for content containers

## Day 2 No Challenge: 
Learnt about em & rem units. Both em and rem scale with respect to font-size but both are a lot different other than this one thing, em scales according to element's font-size if not specified then it's parent's font-size, if the parent element's font-size is also not set then it scales according to the root font-size while rem on the other hand only scales according to the root font-size (One thing to remember about em is it's font-size always depends on the parent element while used anywhere else it depends on the font-size of the current element). Using rem to things where we want them to be consistent like margins. font-sizes, etc and use em units where we want to scale things respective to the font-size of the element like for btns and paddings for certain sections. Avoid using ems for font-sizes, instead it can be used for btn padding.

## Day 3 Challenge 2: 
Learnt about max-width property and to use it in place of min-width as min-width kind of to a certain extend means setting up a width. max-width is beneficial in scenarios like text paragraphs where we can set the max-width for how much the para text spans in on the window for higher width displays. It's a good UI practice to limit the width of text paragraphs from occupying the entire with of window on higher width windows as it gets progresively hard to read that. The challenge was basically limiting the stretch of the intro-content para and aligning all the text content to center.

## Day 4 Notes: 
vh and vw are units that scale according to the window size, vh scales according to the viewport height while vw scales according to the viewport width. They can be used in scenarios such as a header section in desktop where we want it to cover the 100% of viewport height so we can achieve that through 100vh and if we want a certain container to always fill the 100% of the entire viewport width then we can use 100vw there. Using vh on smaller screen causes some issues so should use it on small screens with caution. Vmax considers whichever viewport is greater, that is, for 20vmax whether 20vw > 20vh then it is 20vw or vice versa and then scales according to that viewport. Vmin is the opposite of vmax, that is, for 20vmin whether 20vw < 20vw the it is 20vw or vice versa and then scales according to it. They can be used for font sizes but should be used with extensive testing when used for font-sizes.

## Day 5 Challenge 3: 
Achieved responsiveness without the use of media queries by using what I have learnt up till now, that is, using units like rem, em, vmax,vw to achieve responsive typography and design. Used vmax for the inner container width for the content inside the main header / container. Used vmin for heading for making the heading responsive. Made use of em units for margins and paddings so that they shrink or grow according to the size of the fonts which are in turn responsive to the viewport widths and heights. Made the padding of btn responsive to it's font size using em units so the padding for the btn remains consistent even if the font size increases or decreases.

## Day 6 No Challenge: 
Learnt that em should not be used for font sizes as it could bring things very easily and not scale as we want cause em is always relative to the font-size of the parent and as far as ems are concerned is should be used for paddings and in some scenarios can also be used for setting margins for elements but should be avoided for font-sizes.

## Day 7 No Challenge: 
Looked at Kevin's solution, he had more easy going approach by setting certain predefined witdhs for max-width and stuff where as I tried to tackle is using viewport units and min function for font-sizes with viewport units for font-sizes as well, using min to cap the maximum size it can grow to. 

## Day 8 Flexbox Challenge 1: 
Learned about the basics of flexbox, that is, how flexbox container and flex items behave. The default flex direction is row and than flex items are shrink to the minimum##  width possible by default. Gap 
between flex items can be specified using gap property as it is supported by most browsers now. Further the challenge was just putting to use the above knowledge of flexbox creating a layout for desktop only right now