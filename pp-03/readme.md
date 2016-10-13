## ITMD 361, Production Problem 3: Relative Units in CSS

For this production problem, you will be doing some math using the formula we talked about in class
on September 21. Specifically,

    target ÷ context = result

Remember that, by default, most browsers set 1em = 16px.

You’ll then use that to compute the values for the CSS styles below.

1. Convert the base font-size listed here from pixels to ems:

      html {
        font-size: 1.188em; /* 19px/16px */
      }

2.  Convert the base font-size listed here to ems, and set the line-height in ems accordingly:

      html {
        font-size: 1.063em; /* 17px/16px */
        line-height: 1.412em; /* 24px/17px */
      }

3. Set the padding for this page to 12px on top and bottom, and 6px on left and right. Express in
ems:

      html {
        font-size: 1.125em; /* 18px/16px */
        padding: 0.667em 0.333em; /* 12px/18px 6px/18px */
      }

4. Consider the following CSS. Assuming a browser with its base size at 1em = 16px, how big is h2,
in pixels?

      html {
        font-size: 1.125em; /* 18px/16px */
      }
      figure {
        font-size: 0.888em; /* 15px */
      }
      figure h2 {
        font-size: 1.4375em; /* 25px */
      }
