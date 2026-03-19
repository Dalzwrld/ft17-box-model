# Introduction to The Box Model

<!-- Paddings & Margins -->

Paddings/Margins move clockwise (Top, Right, Bottom, Left). This applies for all four values.

One value targets them all at once.

Two values [(Top & Bottom), (Left & Right)].

Three values [Top, (Left & Right), Bottom].


<!-- Units of measurements -->

Absolute units are fixed regardless of the windows dimensions eg px, cm, m etc.

Relative units are calculated against a based value such as window dimensions eg rem (16px as the default), vh, vw etc.

The root element can be modified to change the default measurement of a relative unit. Eg if it's modified from 16px to 10px, the relative units will be *10. So 2rem will be 20px in size.

This is overridden in the html{} selector in the css code.


<!-- Flexbox -->

Flex layouts are usually displayed as rows or columns. They are applied in block elements.

Flexbox has two axes, the main axis and the cross axis. Their positions are determined by the flex-direction property.

The flex items move along the main axis as a group, so if the main axis is a row, they will align themselves vertically along the main axis. This makes the horizontal axis the cross axis. This works in the opposite way for the column as the main axis.

A normal div aligns its items vertically, but flex-direction allows us to change that.

A flex-container is a parent element that allows a user to manipulate and align its children in various ways. This is done by first using a display of flex on the parent.

The default behavior of flex is row.

Justify-content & Align-items heavily rely on the two axes. Justify-content brings the content to the top center (main axis), while align-items brings them to the middle of the page (cross-axis).


<!-- Spacing -->

By using a padding/margin value of auto and setting a specific amount of max-width, we allow the element(s) to take up equal space automatically from left to right.

Eg [padding: 0 auto;] and [max-width: 1200px;] allows the element(s) to take up equal horizontal space, bringing it to the center. It takes up no vertical space since it's set to 0.