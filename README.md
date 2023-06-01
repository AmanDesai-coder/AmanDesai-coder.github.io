## Using Reverie on GitHub Pages

Setting up Reverie on GitHub Pages is as simple as it gets!

### 1. Fork Reverie to your User Repository

Fork this repository, then rename the repository to `yourgithubusername.github.io`.

Alternatively, you can click the [`Use this template`](https://github.com/amitmerchant1990/reverie/generate) button if you want to create a repository with a clean commit history which will use Reverie as a template.

Your Jekyll blog will often be viewable immediately at <https://yourgithubusername.github.io> (if it's not, you can often force it to build by completing step 2).

### 2. Customize and view your site

Enter your site name, description, avatar and many other options by editing the `_config.yml` file. You can easily turn on Google Analytics tracking, Disqus commenting and social icons here.

Making a change to `_config.yml` (or any file in your repository) will force GitHub Pages to rebuild your site with Jekyll. Your rebuilt site will be viewable a few seconds later at <https://yourgithubusername.github.io> - if not, give it ten minutes as GitHub suggests and it'll appear soon.

### 3. Publish your first blog post

Delete all files from `_posts`directory and create a new file called `/_posts/2019-2-13-Hello-World.md` to publish your first blog post. That's all you need to do to publish your first blog post! This [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) might come in handy while writing the posts.

> You can add additional posts in the browser on GitHub.com too! Just hit the <kbd>Create new file</kbd> button in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-title.md

## Using Categories in Reverie

You can categorize your content based on `categories` in Reverie. For this, you just need to add `categories` in front matter like below:

For adding single category:

```md
categories: JavaScript
```

For adding multiple categories:

```md
categories: [PHP, Laravel]
```

The categorized content can be shown over this URL: <https://yourgithubusername.github.io/categories/>

## Pagination

Pagination of posts in Reverie works out-of-the-box. You only need to specify the number of posts you want on a single page in `_config.yml` and Reverie will take care of the rest.

```yml
paginate: 6
```

## RSS

Reverie comes with a [RSS feed](https://en.wikipedia.org/wiki/RSS) in-built. The generated RSS Feed of your blog can be found at <https://yourgithubusername.github.io/feed>. You can see the example RSS feed over [here](https://reverie-jekyll.netlify.app/feed.xml).

## Sitemap

The generated sitemap of your blog can be found at <https://yourgithubusername.github.io/sitemap.xml>. You can see the example sitemap feed over [here](https://reverie-jekyll.netlify.app/sitemap.xml).

## Emailware
Reverie is an [emailware](https://en.wiktionary.org/wiki/emailware). Meaning, if you liked using this theme or it has helped you in any way, I'd like you send me an email at <bullredeyes@gmail.com> about anything you'd want to say about this software. I'd really appreciate it!

## The name?

reverie - _a state of being pleasantly lost in one's thoughts; a daydream._<br><sup>/ˈrɛv(ə)ri/</sup> 


## License

MIT
