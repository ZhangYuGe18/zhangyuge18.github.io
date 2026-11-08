# Adding an invited talk

All talks live on one page: edit `_pages/talks.md` and add a new `talk-entry` block immediately above `<!-- Add invited-talk entries here. -->`. Put your newest talk first.

```md
<div class="talk-entry">
  <div class="talk-date">Nov 2026</div>
  <div class="talk-content">
    <div class="talk-title">AI for Adaptive Radiotherapy: From Images to Decisions</div>
    <div class="talk-event">2026 Example Symposium</div>
    <div class="talk-location">Example University · Xi'an, China</div>
  </div>
</div>
```

The date, title, event, and host/location make a complete entry. To link a conference announcement, replace the event text with `<a href="https://...">Event name</a>`. Place slide PDFs in `files/`, then link to them as `/files/your-slides.pdf`.

## Preview locally

From the repository root, install the Ruby dependencies once, then start Jekyll:

```bash
bundle install
bundle exec jekyll serve --livereload --host 127.0.0.1
```

Open [http://127.0.0.1:4000/talks/](http://127.0.0.1:4000/talks/) in a browser. Keep the terminal running while you edit; content changes usually refresh automatically. Restart the command after changing `_config.yml` or `_data/navigation.yml`.

If dependency installation reports that Ruby is too old, use Ruby 3.0 or later, then run the two commands again.

For a strong, consistent entry:

- **Title:** use the exact talk title, in title case.
- **Event:** name the conference, seminar, or workshop; add its edition/year when useful.
- **Venue + location:** distinguish the host institution from the city or `Online`.
- **Summary:** one plain-language sentence on the topic and one on its contribution or discussion—about 25–45 words total.
- **Links:** include only public, durable slide, recording, or event links.
