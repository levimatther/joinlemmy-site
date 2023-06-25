# Avatars, email notifications, and a whole lot more

_Written by @dessalines, 2020-01-16_

`v0.6.0` is here, and we've closed [41 issues!](https://github.com/dessalines/lemmy/milestone/15?closed=1)

This is the biggest release by far:

- Avatars!
- Optional Email notifications for username mentions, post and comment replies.
- Ability to change your password and email address.
- Can set a custom language.
- Lemmy-wide settings to disable downvotes, and close registration.
- A better documentation system, hosted in lemmy itself.
- [Huge DB performance gains](https://github.com/dessalines/lemmy/issues/411) (everthing down to < `30ms`) by using materialized views.
- Fixed major issue with similar post URL and title searching.
- Upgraded to Actix `2.0`
- Faster comment / post voting.
- Better small screen support.
- Lots of bug fixes, refactoring of back end code.

Another major announcement is that Lemmy now has another lead developer besides me, [@felix@radical.town](https://radical.town/@felix). Theyve created a better documentation system, implemented RSS feeds, simplified docker and project configs, upgraded actix, working on federation, a whole lot more.

https://dev.lemmy.ml
