Zak Gordon's _Advanced Gutenberg Block_ course has very cool info
about building a Gutenberg Block having a React implementation on the Wordpress
Frontend (gallery example).  However, one thing I noticed is, whenever
the advanced-gutenberg-course plugin is activated, then the plug-in
frontend code (including React and a bunch of node modules-- see
below) is loaded on every page whether or not the page or any page
uses those blocks.  For the sake of avoiding PLB (Page-Load-Bloat),
isn’t there some way to avoid this?  That would be a great addition to
some already great stuff :)

![screenshot](https://github.com/c2mw4/gutenberg-react-blocks/blob/main/files-on-page-block-not-used.png
"Screenshot When No Blocks On Page")
