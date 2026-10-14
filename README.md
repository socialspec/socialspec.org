# SocialSpec.org

[SocialSpec.org] is a collection of APIs for social engagement on the world wide web.

## The Specifications

There are currently three APIs:

* https://followingspec.org (`/.well-known/following.opml`)
* https://aboutspec.org (`/.well-known/about.md`)
* https://contactspec.org (`/.well-known/contact.vcf`)

## The Website(s)

This repository contains the source code for https://socialspec.org. 
The [socialspec.org] websites are built using the HyperTexting static-site generator. 
Please visit https://hypertexting.dev to learn more.

## Contributing

1.  **GitHub Stars**

    The easiest way to contribute to [socialspec.org] is to star all four repositories:

    * https://github.com/socialspec/socialspec.org
    * https://github.com/socialspec/followspec.org
    * https://github.com/socialspec/aboutspec.org
    * https://github.com/socialspec/contactspec.org

1.  **Adoption!**

    The best way to help contribute to [socialspec.org] is to implement support for one or more of the APIs. 
    
    * Do you have a personal or business website?
    * Do you work at a company that is building a content management system (CMS) like Wordpress?
    * Do you work on an RSS feed reader?
    
    Add support for [followspec.org], [aboutspec.org], and/or [contactspec.org]! 🙌
    If you do, please let us know: email info@socialspec.org and we may feature your work on the https://socialspec.org/news feed.

1.  **Comment on the RFCs**

    You can also help contribute to [socialspec.org] by liking or comment on the RFCs:

    https://github.com/socialspec/followspec.org/issues/1 (coming soon)
    https://github.com/socialspec/aboutspec.org/issues/1 (coming soon)
    https://github.com/socialspec/contactspec.org/issues/1 (coming soon)

1.  **Submit PRs**

    Did you notice a typo or have a suggestion for how to improve [socialspec.org]? 
    Pull requests from humans are always welcome!

    Download the [HyperTexting CLI] (`hyperctl`), then run: 

    ```
    mkdir socialspec.org
    cd socialspec.org
    git clone https://github.com/socialspec/socialspec.org
    hyperctl server --port 8080
    ```


<!-- Links -->
[socialspec.org]: https://socialspec.org
[followspec.org]: https://followspec.org
[aboutspec.org]: https://aboutspec.org
[contactspec.org]: https://contactspec.org
[HyperTexting CLI]: https://hypertexting.dev
