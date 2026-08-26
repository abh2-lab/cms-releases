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
