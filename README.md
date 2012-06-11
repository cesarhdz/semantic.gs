#About
The Semantic Grid System is a modern approach to the CSS grid. It allows you to set column and gutter widths, choose the number of columns, switch between pixels and percentages, and achieve responsive layouts, all without any unsemantic .grid_x classes in your markup. By default it's powered by [LESS.js](http://lesscss.org/), but also supports [SCSS](http://sass-lang.com/) and [Stylus](http://learnboost.github.com/stylus/).

It lives on the web at [Semantic.gs](http://semantic.gs/).

#Issues
If you spot any issues or have ideas for improvement, feel free to [file a ticket](https://github.com/twigkit/semantic.gs/issues) or fork on [GitHub](https://github.com/twigkit/semantic.gs) and issue a pull request.

##Fluid and fixed layouts differences
We need to follow different rules whether we choose one system or the other. In fixed layout we may need a row container every time we want to use columns, because we need to make the row larger to place the columns, whereas in the fluid layout we don't need the row container. In the first case the padding must be applied to the container, in the latter the columns have already the padding.

#License
Licensed under Apache 2.0. See [LICENSE](https://github.com/twigkit/semantic.gs/blob/master/LICENSE.txt)

#Created by
The Semantic Grid System was built by [Tyler Tate](http://twitter.com/tylertate/) at [TwigKit](http://twigkit.com/).