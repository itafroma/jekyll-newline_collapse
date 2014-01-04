# Jekyll Newline Collapse

This plugin removes extra newlines from rendered Jekyll markup.

Based on [kerotaa][1]'s original [remove-empty-lines-html.rb][2] plugin, this
version strips newlines from non-HTML files and incorporates a few coding style
changes.

## Installation

This plugin is provided as a gem:

```sh
gem install jekyll-itafroma-collapse_newlines
```

Once the gem is installed, include it in your Jekyll site's configuration:

```yaml
gems: ['jekyll/itafroma/collapse_newlines']
```

## Acknowledgements

This plugin is a direct derivative work of kerotaa’s plugin, which is used with
permission under the terms of the MIT license. The original plugin is copyright
© 2012 kerotaa. The full text of the permission notice required for the MIT
license can be found in the source code.

## Copyright and license

This plugin in its derivative form is copyright © 2013 [Mark Trapp][3]. All
rights reserved. It is made available via the MIT license. A copy of the license
can be found in the `LICENSE` file.

## Related links

* [Canonical project page][4]
* [RubyGems project page][5]

[1]: http://kerotaa.hateblo.jp "kerotaa’s website"
[2]: https://gist.github.com/kerotaa/5788650 "kerotaa’s remove-empty-lines-html.rb"
[3]: http://marktrapp.com "Mark Trapp’s website"
[4]: http://marktrapp.com/projects/jekyll-collapse-newlines "jekyll-archive project page"
[5]: https://rubygems.org/gems/jekyll-itafroma-collapse_newlines "RubyGems project page"
