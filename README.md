# Bootstrap 4 + Jekyll + Travis-CI for GitHub Pages

To use: when you have the dependancies as per
[the docs](https://jekyllrb.com/docs/installation/) you should run
`bundle install`.
    
HTML files are based on Minima - if you need to configure
the post or page layouts, copy [those files](https://github.com/jekyll/minima/tree/master/_layouts) in as needed.
    
Bootstrap variables can be overriden in `_sass/custom.scss` - refer
to the [full list of available values](https://github.com/twbs/bootstrap/blob/v4-dev/scss/_variables.scss).

Note that GitHub Pages doesn't run gems that aren't on their predefined list, so it won't work with their autocompile, you'll need to push up and serve the compiled files.

[the starter kits make from here](https://github.com/jenofdoom/jekyll-bootstrap-4), re-factory and update latest version

# References
* [Travis-CI encrypt 'GITHUB_TOKEN'](https://github.com/travis-ci/travis.rb#encrypt)
* [Travis-CI Deploy](https://docs.travis-ci.com/user/deployment/pages/)
* [Success build log](https://travis-ci.org/KunYi/jekyll-bootstrap-4/builds/382002804)
* [Demo GitHub Pages](https://kunyi.github.io/jekyll-bootstrap-4/)
