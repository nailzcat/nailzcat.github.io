# Circle Land Films

The site is hosted on [GitHub Pages](https://pages.github.com/), and is built using [Jekyll](https://jekyllrb.com/). When you push to the `master` branch, GitHub will build and redeploy the site automatically.


## Writing posts

There are two types of posts: Media and News.  All posts should be [markdown](https://guides.github.com/features/mastering-markdown/) files (using [kramdown](https://kramdown.gettalong.org/syntax.html)), and **must** be named in the format `YYYY-MM-DD-title.markdown`.  In addition to standard markdown, Jekyll posts all have "front matter" - the section delimited by three dashes at the top of each file.

Contents vary as follows:

### Media

Media posts appear in full in a list on the [media page](https://nailzcat.github.io/).  Each one can have a YouTube video, a Vimeo video and some content, and all are optional.  Youtube and Vimeo links are specified in the front matter, and you can provide an embedded link (to show the video in the page) as well as the regular link to view the video on YouTube or Vimeo.  These links should be provided in the front matter as `youtube-embed`, `youtube`, `vimeo-embed` and `vimeo`.

### News

News posts appear in a list on the [news page](https://nailzcat.github.io/news/) that displays an image and a summary of the post, which are specified in the front matter as `image` and `abstract` respectively.  The title of each post and its image (if specified) link to the full post, where the content will appear as well as the image.


## Running locally

Clone the repo:

    git clone git@github.com:nailzcat/nailzcat.github.io

You can [run Jekyll locally](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) to preview changes before pushing them to GitHub.  First [install Jekyll](https://jekyllrb.com/docs/installation/) and then run:

    jekyll serve --incremental

This will build the project and fire up a server at [http://127.0.0.1:4000](http://127.0.0.1:4000/).  Livereload is configured to run automatically, but it may not work because reasons; you may have to refresh to see changes.

## Copyright

Copyright © 2017 Henry King, all rights reserved.

## License

No license is provided for the contents of this repository.

## Contact

[circlelandfilms@gmail.com](mailto:circlelandfilms@gmail.com)
