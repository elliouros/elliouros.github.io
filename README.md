# elliouros.github.io

This is the source code for my site.<br>
<sub>do i really need to be writing a readme for a website..?</sub>

## layouts

### page

The page layout is for main pages. It contains a simple frame for titling,
& stylesheets w/ a navbar.

The front matter `style` can be set to a sequence of filenames (sans
extension). A seqence of 1 style is possible and common. 0 is, in theory,
equally possible. `base.css` is included by default, but an option may be added
later such that it is excludable.

### blog (layout & posts)

The blog layout is incredibly simple, containing only titling back
button, and a style element.

Front matter `style` can be used to fill the style element. Ideally a scalar
literal (using `|-`). Blogposts are not intended to have lots of style. (this
should probably be revised.)

Front matter `title` is used to both title the page and give it a title on the
index (/blog). `ititle` (index title) can be used to override the title for the
index. `summary` fills in the index subtitle. `img` is a path to the post's
thumbnail- again, for the index.

## style

<sub>this is basically tl;dr for styling from **layouts**.</sub>

- `base.css` for everything.
- `(slug).css` for specific cases, with `style` front matter as a sequence of
slugs.
- blog posts have `style` front matter as the contents of a \<style\> element.
