---
layout: post
created_at: 2026-10-13T07:00:00-07:00
title: Introducing SocialSpec.org
description: |
  APIs for social engagement on the world wide web (of websites). Based on open standards.
byline:
  name: Caleb Hailey
  username: "@calebhailey.com"
  href: https://calebhailey.com
tags: [announcement]
date: October 13, 2026
color: none
---

There are too many social media platforms.

<figure>
  <img src='https://imgs.xkcd.com/comics/standards.png'>
  <figcaption>Evergreen comic, by @xkcd.com.</figcaption>
</figure>

The abundance of social media _shouldn't_ be a problem.
It _should_ be a good thing.
But it isn't.
Giving people choices is generally considered better than taking choices away.
But the current state of social media doesn't really offer choices.

<!-- more -->

## The internet is broken

If you want to follow someone on YouTube, you have to sign up for @youtube.com. 
If you want to follow your friend on Instagram, you have to sign up for @instagram.com.
If you want to get mad, you have to sign up for @x.com.
If you were following people on Twitter, they might have abandoned ship and moved to @threads.com.
Or @bsky.social.
Or @mastodon.social.
And so on.

The problem is, every single one of these platforms is competing for your attention.
As a result, we are no longer in control what we see on social media.
First it was the ads, then the algorithms, and now the AI slop.
<mark>Today, less than half of the content in our timelines comes from the feeds we follow.</mark>
Multiply that problem times the number of different social media apps on your phone and the math gets even worse.

It doesn't have to be like this!
There is a better way.
In fact, the underlying technology has been quietly gaining momentum for decades: the humble RSS feed.
RSS feeds are the reason why ["Wherever you get your podcasts" is a radical statement](https://www.anildash.com/2024/02/05/wherever-you-get-podcasts/).
I don't have to sign up for YouTube or Instagram or X or Bluesky to follow that hot new podcast everyone is talking about.
I can just use the Podcast app I'm already using.
Once you see it you can't unsee it.

But why haven't RSS feeds (for more than just podcasts) reached escape velocity in the same way that social media has? 
It's not a technical limitation.
The entire podcasting industry is powered by RSS feeds, and podcasting doesn't have a scalability problem.
So what is it?

## The missing pieces

Ever since @anildash.com wrote about [The Lost Infrastructure of Social Media](https://www.anildash.com/2016/08/08/the-lost-infrastructure-of-social-media/) (over 10 years ago!), I have thought about the big social media platforms as _integrated infrastructure_ companies.
They provide subsidised content management systems that make it easy to publish content, and free hosting services.
And they provide tools for consumers to "follow" or subscribe to that content.
That core infrastructure is effectively a proprietary alternative to the RSS feed.
But they also provide complementary services that go beyond distribution. 
They facilitate communication (direct messaging), engagement (likes and notifications), discovery (finding new feeds), and much more.

Social media platforms also package all of this up into apps that support publishing _and_ subscribing.
It's read-write access to the internet as opposed to the read-only access offered by RSS feed readers and podcast apps.

How can the social network otherwise known as the world wide web (of websites) compete with that?
With open standards.

## Introducing the SocialSpec APIs

There are too many social media platforms!
But how do we solve that problem without creating a new one (and avoid becoming the punchline in an XKCD comic)? 
By building on the largest social network in the world: the world wide web (of websites).

<mark>The SocialSpec API project is a _documentation_ project.</mark>
Each SocialSpec API documents one missing building block around RSS feeds: @followspec.org, @aboutspec.org, and @contactspec.org. 
These building blocks restore some of the missing infrastructure needed to create compelling new social media experiences based on open standards. 
If SocialSpec is successful, it won't be because we created something new. 
It will be because we added the missing API documentation for the open social web.
SocialSpec APIs unlock access to information that millions of people are already sharing.

One of the goals for [the SocialSpec APIs](/#apis) is to extend the reach of "RSS feed readers" beyond the group of people who have already known and loved them for the past 20 years. 
Because the number of people who haven't tried an RSS feed reader is significantly larger than the number who have. 
And the group that hasn't tried RSS is made up of people who are unhappy with the current state of social media. 
These are solvable problems!

Will you join us? :rocket: 
