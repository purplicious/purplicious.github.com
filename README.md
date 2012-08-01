# Purplicious blog

## Guide to create a post

1. Create a new file under `_posts` following the convention for the name:

    year-month-day-post-title.markdown

2. Add new images under `static/images`. Don't forget to use the same path when you link them in your posts. For instance:

```
<a href="static/images/purple_heart.jpg">Purple heart</a>
```

3. Run the local server to verify the post looks good:

    $ ./localhost

4. Go to `http://localhost:4000` and check the home page.

5. Publish your blog in GitHub running the publishing command:

    $ ./publish

6. Go to `purplicious.github.com` to see the changes.
