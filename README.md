# Bits & Builds

My personal blog — built with [Jekyll](https://jekyllrb.com/) and the [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) theme, hosted on [GitHub Pages](https://pages.github.com/).

**Live at:** [suryadevarapranav.github.io](https://suryadevarapranav.github.io)

## Writing a new post

1. Create a new file in `_posts/` with the format `YYYY-MM-DD-title.md`
2. Add frontmatter at the top:

   ```yaml
   ---
   title: "Your Post Title"
   date: 2026-05-12
   categories: [Category]
   tags: [tag1, tag2]
   ---
   ```

3. Write your content in Markdown below the frontmatter
4. Commit and push — GitHub Pages will build and deploy automatically

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`
