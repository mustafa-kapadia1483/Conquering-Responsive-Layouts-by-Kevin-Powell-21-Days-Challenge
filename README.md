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
Learned about the basics of flexbox, that is, how flexbox container and flex items behave. The default flex direction is row and than flex items are shrink to the minimum width possible by default. Gap between flex items can be specified using gap property as it is supported by most browsers now. Further the challenge was just putting to use the above knowledge of flexbox creating a layout for desktop only right now

## Day 9 Flexbox Challenge 2: 
Added image to the hero section by wrapping it in a div so that it does not get stretched being a flexed item. Created a two column layout where the 2nd column has a flex direction of column. Learned more about using flex and how to make one column bigger than the other.

## Day 10 No Challenger:
Learnt more about display flex properties like flex flow, grow, shrink. Mostly the ins and outs of flexbox.

## Day 11 Flexbox Challenge 3:
Navbar alignment using flex box. It is very easy to align the navbar for wide screens using display flex and gap property.

## Day 12 Flexbox Challenge 4:
Landing Page creation challenge for desktop size. Learnt how to use flex grow and shrink effectively also how to make alternating cloumns layout by styling even and odd through nth-of-child differently and modifiying the order property of the flex items. Made the header responsive using vmin and vmax units for font-sizes.

## Day 13/14 No Challenge:
No challenge or course videos, saw the max(), min(), clamp() functionality in Kevin's YouTube videos. When and how to use them effectively in css for creating responsive layouts.

## Day 15 No Challenge:
Introduction to Media queries and how min-width and max-width can be used for creating either mobile first or desktop first web experiences. There are many types for media queries which can be specified but the most used one is screen for changing styles of the webpage based on the width of the page. Also media queries should be placed at the end of the css file so that it can override the previous styles. No challenge.

## Day 16 No Challenge:
1st video focusses on deciding the breakpoints to be used for media queries, like how to determine what breakpoints are to be used. Kevin says that instead at looking at breakpoints from the point of bootstrap or specific sizes of devices, apply breakpoints where you think the current layout is breaking, looking odd, etc. You choose a breakpoint where you think the current element structure is either breaking or not making sense when viewed at that width. Dev tools are very beneficial in determining this thing as using it one can play with different screen sizes and how does your layout look at certain screen sizes. Some components may look proper at different screen sizes whereas some may outright not make any sense and look out of place, such components can be fixed for that screen size using breakpoints.Most simple layours can be made using only media query breakpoint but depends on how complex the design really is. The fcc link provides good info for basic breakpoints and can be used as reference when developing sites.

## Day 17 No Challenge:
Media viewport tag is disccused on day 17. It sets the initial scale of zoom of the page, which is usually to 1.0 so that there is no weird behaviour. It also helps the browser implement media queries which would not be possible without viewport meta tag.

## Day 18 No Challenge:
Kevin shows the solution to flexbox challenge 4

## Day 19 Nav Challenge:
The challenge was to design a responsive nav, the design for how the nav should look in mobile was given by kevin and how the desktop version should look was open to us. Completed the challenge, which gave me confidence as to how to read other's code base and make effective changes to it.

