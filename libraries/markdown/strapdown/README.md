Strapdown
=========

[Strapdown.js](http://strapdownjs.com/) [[GitHub]((https://github.com/arturadib/strapdown))] lets you write web pages using markdown.


Forks
-----

A more updated [fork](http://lbesson.bitbucket.org/md/) is maintained by Lilian Besson and contains some added features including MathJax, etc.

    <script type="text/javascript" src="//https://cdn.rawgit.com/Naereen/StrapDown.js/master/strapdown.min.js"></script>

Another fork/variant [strapdown-zeta](http://strapdown.ztx.io/) supports MathJax, GFM, Highlight.js mononokai(tweaked).

Other interesting forks include one that include a [table of contents](https://github.com/ndossougbe/strapdown), and another more update for from that which of course also supports [table of contents](https://github.com/yieme/strapdown).

A nice fork adds [navigation](https://github.com/smzg/strapdown) (as well as multiple `xmp.textarea` tags, which the original does not!).

Usage
-----

Basic use is to write markdown in `<xmp>` tag (`<textarea>` also works and is not deprecated).

Include [Bootswatch themes](Bootswatch.com) by adding `theme` attribute.
ls


See Also
--------
=======
Note there are some nuances that affect processing, including the presence or absence of a `<title>` tag and a sectioning element with `class="navbar"`.


#### Navbar


If you have specified a `<title>` but no `.navbar` then Strapdown will insert the following with your title as follows:

    <div class="navbar-inner">
        <div class="container">
            <div id="headline" class="brand">
                Your Title Here
            </div>
        </div>
    </div>

#### Themes

You can specify a themes from [Bootswatch](https://bootswatch.com/) by adding a `theme` attribute on the enclosing element.

For other ways to write markdown slideshows see [Cleaver](http://jdan.github.io/cleaver/)
