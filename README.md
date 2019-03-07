# Stackery Changelog Scraper

Gets the changelog from `https://docs.stackery.io/en/changelog`, scrapes the relevant data, puts it in bare HTML that is then put in an S3 bucket for the app to `GET`.

✨ Huzzah! ✨ 

This is the HTML output format:

```html
<h2>Stackery Changelog</h2>
<p>We're always cranking out improvements, which you can read about in the <a href='https://docs.stackery.io/en/changelog/'  target='_blank' rel='noopener noreferrer'>Stackery Changelog</a>.</p>
<p>Check out some recent wins:</p>
<ul>
  <li><a target="_blank" href="https://docs.stackery.io/en/changelog/#note-shortcut">Note title</a></li>
  <li><a target="_blank" href="https://docs.stackery.io/en/changelog/#note-shortcut">Note title</a></li>
  <li><a target="_blank" href="https://docs.stackery.io/en/changelog/#note-shortcut">Note title</a></li>
  <li><a target="_blank" href="https://docs.stackery.io/en/changelog/#note-shortcut">Note title</a></li>
</ul>
```