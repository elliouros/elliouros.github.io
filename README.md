# elliouros.github.io

This is the source code for my site.<br>
<sub>do i really need to be writing a readme for a website..?</sub>

## layouts

### page

The page layout is for main pages. It contains titling, stylesheets and the
navbar.

The front matter `style` can be set to a sequence of filenames (sans
extension). A seqence of 1 style is possible and common. 0 is equally
possible.<br>
`style-internal` can be used to fill the &lt;style&gt; element. Ideally a scalar
literal (using `|-`). When empty, &lt;style&gt; is excluded entirely.

### blog (layout & posts)

The blog layout is simplistic as well, containing a title, a back button, and
styling facilities.

Styling follows the same rules as the page layout. `style-internal` is
encouraged, since blog posts are not intended to have lots of complex style.

Front matter `title` is used to both title the page and give it a title on the
index (/blog). `ititle` (index title) can be used to override the title for the
index. `summary` fills in the index subtitle. `img` is a path to the post's
thumbnail- again, for the index.
