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

