
## 1.4.2 — 2026-08-26

Fixes setting up a fresh install, and makes a new install check for updates
straight away instead of waiting a day.

No database change. Nothing to do before or after updating.


## 1.4.1 — 2026-08-26

Fixes what a new install receives.

Until now, making a starter copy of the CMS also copied the theme belonging to
the install it was made from — its page designs, its logos and its sample
content. A new install now gets only the CMS and its own two themes. Any theme
you build by hand stays yours: it is never copied out, and CMS updates never
touch it.

Also fixes a setup problem where a fresh install could point at a theme that
was not included, and tightens things so the CMS's own two themes cannot be
edited by mistake — edits there would be overwritten by the next update.

No database change. Nothing to do before or after updating.



## 1.4.0 — 2026-08-26

Internal change, nothing visible on your site.

The CMS's own web code and your theme's code now live in separate places. Until
now the whole site — every page and every shared piece — sat inside one
theme, so taking that theme away would have taken the site with it. They are
now cleanly apart, which is what lets your theme live in its own place and
still receive CMS updates.

Also fixes a developer annoyance: if the web port was busy, the dev server used
to quietly take the API's port instead, and the API looked like the thing that
broke. It now says plainly which port is in use.

No database change. Nothing to do before or after updating.


## 1.3.1 — 2026-08-26

Safety and tooling. Nothing changes on your site.

Fixes a display bug in the admin: a custom field holding a list or a group of
values showed as "[object Object]" in the information table instead of its
actual content.

Behind the scenes, the CMS now blocks any change that could break your database
on update, and every release is checked automatically before it ships. Going
back to a previous version has also been tested properly for the first time.

No database change. Nothing to do before or after updating.




## 1.3.0 — 2026-08-25

Internal change, nothing visible on your site. The CMS's own blocks and your
theme's blocks now live in separate folders. This is what lets you take future
updates without them clashing with your own design work.

No database change. Nothing to do before or after updating.

## 1.2.0 — 2026-08-25

Internal change, nothing visible on your site. Adding a block, template or part
now registers itself automatically instead of needing an entry in a shared file.

No database change. Nothing to do before or after updating.
