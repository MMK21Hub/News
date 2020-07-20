When writing news, try to follow the [Style Guide](#style-guide). Every point should have at least one link. Try not to use Discord message links.

## Useful Soruces
 - [Tech/News - Meta](https://meta.wikimedia.org/wiki/Special:MyLanguage/Tech/News/Latest)
 - [Wikimedia phab.](https://phabricator.wikimedia.org/notification/)
 - [GitHub releases](https://github.com/notifications)
 - Discord announcements/pings ("Recent Mentions")
 - [Spam email](https://mail.google.com/mail/u/1/)
 - Mailing lists (Use 'Thread' view): [Wikimedia-l](https://lists.wikimedia.org/pipermail/wikimedia-l/) [Wikitech-l](https://lists.wikimedia.org/pipermail/wikitech-l/) [MediaWiki-announce](https://lists.wikimedia.org/pipermail/mediawiki-announce/)
 - [RSS feeds](https://feedreader.com/)
 - [Terraria community calendar](https://docs.google.com/spreadsheets/d/1XEQiZlonknFfE0aXapBn--8CksTW521hluoIDgWowzk/edit?usp=sharing)
 - [Google calendar](https://calendar.google.com/calendar/r)
 - #community-creations in VanillaTweaks discord server.
 - #update-releases and #new-releases in The Fabric Project discord server.
 - r/Hermitcraft beacon

## Style Guide
Technical levels:
- 1 - Editing
- 2 - Technical user
- 3 - Writing code

|Terms to avoid|Use instead|
|--------------|-----------|
Minecraft: Java Edition | Minecraft 
Mojang Studios<br>Mojang AB | Mojang

## Sunday
Cutoff is 7:00 AM UTC. After that, run a full update of the Auto-Updating Page, and change the status to 'Fully up-to-date!'. 

Once the page is fuly updated, schedule the weekly email to send at 12:00 PM UTC.

Once the email is scheduled, it's time to archive. Convert the page to the folllowing formats: Markdown, HTML, RTF and Wikitext. Then save the outputs to `Archives/<YYYY>/<WW>/<format>.<ext>`. Example: `Archives/2020/29/markdown.md` `Archives/2020/29/html.html` `Archives/2020/29/richtext.rtf` `Archives/2020/29/wikitext.txt`. Then add a `index.md` in that folder with links to the above files.

Finally, reset the `Latest/index.md` by replacing it with the [Auto-Updating Page Template](News-Template.md) (`News-Template.md`). Comment things out and replace the ❌es as needed.
