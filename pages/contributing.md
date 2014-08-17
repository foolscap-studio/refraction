---
layout: page
title: Contributing
permalink: /contributing/
---

Refraction is maintained via [Github](https://github.com/{{ site.username }}/{{ site.projectname }}). A detailed introduction to [Git](http://git-scm.com/documentation) and [Github](https://help.github.com/) is beyond the scope of this document.

### Ways to Contribute

1. If you discover flaws of any kind &ndash; typos, errors in grammar or spelling, continuity errors, awkward pacing, anything &ndash; then you can open an issue on the [issue tracker](https://github.com/foolscap-studio/refraction/issues). You can also use the issue tracker to submit ideas for things you'd like to have in the future.

2. If you want to contribute more directly, you can [fork](https://help.github.com/articles/fork-a-repo) Refraction, make edits to your own copy, and submit a [pull request](https://help.github.com/articles/creating-a-pull-request).

### How to Edit

After forking, use the `/backstage/` directory to help maintain a coherent artistic vision when editing, but be aware that spoilers are likely. Read `/backstage/About Backstage` first.

To add a new story to Refraction, create a file in the `/_posts/` directory. The name of the file must be in the format `YYYY-MM-DD-posttitle.md`, with the appropriate date and title. You should also add a link to your story to the Contents page, in the file `/pages/02-contents.md`.

When working on a new story, you may wish to use the `/drafts/` directory. To include drafts on your locally-hosted instance, invoke Jekyll as `jekyll serve --draft --watch`.

When updating an existing story, create a symlink in `/_posts/` with the date of the update, so that the Updates page and the RSS feed show the update.

Your file should begin with [YAML front matter](http://jekyllrb.com/docs/frontmatter/), which looks like this:

<pre>
---
layout: page
title: Contributing
permalink: /contributing/
---
</pre>

The rest of the document is [Markdown](http://daringfireball.net/projects/markdown/basics). 

