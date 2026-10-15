---
layout: post
created_at: 2026-10-13T12:00:00-07:00
title: "App Spotlight: HyperTexting"
description: |
  The HyperTexting App adds support for @followspec.org, @aboutspec.org, and @contactspec.org
byline:
  name: Caleb Hailey
  username: "@calebhailey.com"
  href: https://calebhailey.com
tags: [apps]
date: October 13, 2026
color: none
---

> **Tuesday, October 13, 2026** &mdash; The HyperTexting App has added first-class support for @followspec.org, @aboutspec.org, and @contactspec.org. 
> 
> Visit @hypertexting.com to learn more.

The SocialSpec project was originally inspired by my work on [recommended feeds in HyperTexting], powered by [OPML subscription lists]. 
So it's no wonder that HyperTexting is also the first app to add support for @aboutspec.org and @contactspec.org with today's announcement of [HyperTexting version 0.28].[^1]

<figure medium>
  <img src='https://hypertexting.com/blog/newsfeed-network-effects/hypertexting-contacts.png'>
  <figcaption>The new Profile "Contact" tab and Contacts Provider in HyperTexting</figcaption>
</figure>

My goal with HyperTexting has been to rethink what kind of experiences are possible in the world of RSS feed readers and the open web.
I wrote about my thought process in ["The social-media-like interface"]: 

> For the past few years I've spent an inordinate amount of time thinking about whether a "social-media like interface" is possible for "RSS" (and Atom, and JSON Feed, and OPML). The conclusion I've reached is that this requires more than just a departure from the three-column/inbox-style feed reader and obligation-inducing unread counts. It means taking inspiration from social media profiles, responses, mentions, threads, video, discovery, and even personalization. It also means embracing user privacy and the unique attributes of the open web that social media platforms ~~can't~~ refuse to give us. Finally, it should also lower the barrier to entry for publishing in addition to subscribing.

I'm excited about the progress I'm making with this release of HyperTexting, but I'm even more excited about the work on HyperTexting that led me to the SocialSpec project.
If we're going to [fix the internet], we need more experiments like HyperTexting, to create more ways for people to [escape the algorithm] and reclaim control of their news feeds.

Check out ["Newsfeed Network Effects"] on the @hypertexting.com blog to learn more.

<!-- Footnotes -->
[^1]: If you are adding support for SocialSpec to a website or CMS platform and want to use HyperTexting to test your implementation, please note the following:

      HyperTexting version 0.28.0 discovers OPML subscription lists via `<link rel='following'>` or `<link rel='blogroll'>` tags (only), and it supports these vendored endpoints: 

      * `/.well-known/hypertexting/about.md`
      * `/.well-known/hypertexting/contact.vcf`

      <mark>HyperTexting version 0.28.1 with full support for @followspec.org, @aboutspec.org, and @contactspec.org is available to download on TestFlight</mark>, with an App Store release coming soon.
      Visit [hypertexting.dev/downloads] to join the public TestFlight.

      HyperTexting had both an unfair advantage _and_ an unfair disadvantage in that it was the prototype for what eventually became the SocialSpec project.
      In my attempt to announce @socialspec.org in concert with the new \@hypertexting.dev website, the HyperTexting CLI v0.24.0 release, and the HyperTexting App, I fell into a classic chicken and egg problem. 
      I had gotten an earlier build of the new HyperTexting App approved through Apple's [App Store Review] process so it would be ready to publish in the App Store, and I couldn't figure out how to submit a follow-up version 0.28.1 for App Store Review without canceling the already-approved 0.28.0 release. 

      Anyway, this should all be sorted out over the next few days. 

      _Special thanks to @rickymoorhouse.uk for noticing this while implementing SocialSpec on his website, for not giving up when HyperTexting wasn't working as advertised, and for reminding me that I hadn't actually documented this anywhere._ 🙏🏽

      🐓 🥚 🤦🏽‍♂️


<!-- Links -->
[rfc8615]: https://www.rfc-editor.org/info/rfc8615/
[recommended feeds in HyperTexting]: https://hypertexting.com/blog/the-open-webs-hidden-social-graph/
[HyperTexting version 0.28]: https://hypertexting.com/blog/newsfeed-network-effects/
[OPML subscription lists]: https://opml.org/spec2.opml#subscriptionLists
[App Store Review]: https://developer.apple.com/app-store/review/guidelines/
[hypertexting.dev/downloads]: https://hypertexting.dev/downloads/
["The social-media-like interface"]: https://calebhailey.com/blog/the-social-media-like-interface/
["Newsfeed Network Effects"]: https://hypertexting.com/blog/newsfeed-network-effects/
[fix the internet]: /news/introducing-socialspec-dot-org/#the-internet-is-broken
[escape the algorithm]: https://hypertexting.com/blog/welcome-to-the-feediverse/
