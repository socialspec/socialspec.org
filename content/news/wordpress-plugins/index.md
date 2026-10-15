---
layout: post
created_at: 2026-10-15T12:01:00-07:00
title: "App Spotlight: WordPress (Plugins)"
description: |
  A new plugin from WordPress maintainers introduces first-class support for @followspec.org, @aboutspec.org, and @contactspec.org.
byline:
  name: Caleb Hailey
  username: "@calebhailey.com"
  href: https://calebhailey.com
tags: [apps]
date: October 15, 2026
color: none
---

> **Thursday, October 15, 2026** &mdash; [WordPress] maintainers have created a new plugin for adding @followspec.org, @aboutspec.org and @contactspec.org to any WordPress website.
> 
> Check out [`pfefferle/wordpress-socialspec` on GitHub], or visit the [WordPress Plugin Registry] to learn more.

You may recognize [Matthias Pfefferle]'s (@notiz.blog) name as the developer who ~~[challenged Automattic's plans to implement ActivityPub support in Tumblr]~~ _encouraged_ [Matt Mullenweg] (@ma.tt) to implement ActivityPub support in WordPress. 
He now works as the [Open Web Lead] at [Automattic] (@automattic.com).
Bravo!

<figure small>
  <img src='https://notiz.blog/wp-content/uploads/2023/06/tumblr-wordpress-activitypub.png'>
  <figcaption>Well played, Matthias. 👏🏽</figcaption>
</figure>

I'm very excited to share that Matthias has already created not one but _two_ SocialSpec implementations for WordPress.

First he added @followspec.org support to his [blogroll plugin](https://wordpress.org/plugins/blockroll/#developers). 
The changelog for the blogroll plugin says _"Apps that show who you follow can now find the feeds of your blogrolls at `/.well-known/following.opml`, as described in FollowSpec."_

Matthias also created [a new SocialSpec plugin] with robust support for @followspec.org, @aboutspec.org, and @contactspec.org. 
The description he uses in the project README captures the spirit of SocialSpec perfectly:

> Share who you are, how to reach you and what you follow with feed readers and social apps.
> 
> Your site probably has an About page already, maybe a contact page and a list of blogs you like to read. **People can read these pages, but apps can not.** This plugin publishes the same information in simple files that every feed reader and social app can understand. It follows SocialSpec, an open set of three small formats.
>
> A feed reader that knows SocialSpec can then show your site like a social profile: your posts, an "About" tab, a "Following" tab and a button to contact you.

We couldn't have said it better ourselves, Matthias![^1]

WordPress powers over 40% of the websites on the world wide web.
Thanks to Matthias' work on these plugins alone, that means there is now a 4-in-10 chance that your website supports SocialSpec APIs.
All in the first 72 hours since announcing the project! 🤯

Check out [`pfefferle/wordpress-socialspec` on GitHub], or visit the [WordPress Plugin Registry] to learn more.

> ### About WordPress
> 
> WordPress started in 2003 when Mike Little (@mikelittle.org) and Matt Mullenweg (@ma.tt) created a fork of b2/cafelog. The need for an elegant, well-architected personal publishing system was clear even then. Today, WordPress is built on PHP and MariaDB, and licensed under the GPLv2. It is also the platform of choice for over 43% of all sites across the web.
> 
> Learn more at https://wordpress.org/about &rightarrow;

<!-- Footnotes -->
[^1]: In fact, we haven't explained it this well (yet).
      I suspect we might need to borrow some of these words for the @socialspec.org, @followspec.org, @aboutspec.org, and @contactspec.org websites.

<!-- Links -->
[`pfefferle/wordpress-socialspec` on GitHub]: https://github.com/pfefferle/wordpress-socialspec/
[a new SocialSpec plugin]: https://github.com/pfefferle/wordpress-socialspec/
[Automattic]: https://automattic.com
[challenged Automattic's plans to implement ActivityPub support in Tumblr]: https://notiz.blog/2023/06/02/20-jahre/
[Matt Mullenweg]: https://ma.tt
[Matthias Pfefferle]: https://notiz.blog
[Open Web Lead]: https://www.linkedin.com/in/pfefferle/
[WordPress Plugin Registry]: https://wordpress.org/plugins/search/socialspec/
[WordPress]: https://wordpress.org
