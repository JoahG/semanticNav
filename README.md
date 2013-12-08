#semanticNav

My implementation of Chris Coyier's [list-less nav](http://css-tricks.com/navigation-in-lists-to-be-or-not-to-be/), which breaks from the age-old tradition of using the `nav > ul > li > a` by **not using a `ul`** in the `nav`. Instead, it utilizes the `nav > a` format, which is generally more semantic and much better for screen readers.


My main purpose in testing it is seeing how a submenu plays into it, while still not using a `ul` in the code, instead using a `section` to hold the submenu links.