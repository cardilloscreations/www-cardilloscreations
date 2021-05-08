# Data for the Cardillo's Creations Website

This is the repository that is used to generate my website: [Cardillo's Creations](https://www.cardilloscreations.com). The content is transformed to a static content site by [Jekyll](https://github.com/mojombo/jekyll) whenever I push it to [GitHub](https://github.com) and it is hosted for free using [GitHub Pages](https://pages.github.com).

So basically, thanks to GitHub, and some cool OpenSource tech, I'm able to host this website for free, and have backups and version control. Static content is not for everyone, but it's perfect for tech savvy folks running blogs and websites like this. Of course, we can still have dynamic elements using JavaScript, etc.

### Warning - Work In Progress

**Please do not use this site as an example of best practices with Jekyll nor as an example of my best work.** I had to rush through a manual recovery operation to rebuild my site from a snapshot on [archive.org](https://archive.org/web) after I accidentally lost my hosting account during a relocation. The site was previously a WordPress site with a commercial theme and lots of extras so I'm slowly migrating and refactoring it to follow best practices as I need more going forward. In the meantime, it's more of a **mashup** than a properly designed Jekyll site (although it's getting better over time).

### Services Used

 * [Jekyll](https://github.com/mojombo/jekyll) - A static web site generator that is the engine behind [GitHub Pages](https://pages.github.com/) (a service that allows you to host a static website for free by uploading to a [GitHub](https://github.com) account).
 * [Grizzly](https://grizzly.wegrass.com/) - My favorite theme for an App Developer website. It is a commercial theme which I have a license for, but it's currently only available for WordPress, so I've been hacking it for Jekyll.
 * [QR Code Generator](http://goqr.me/api/) - The Grizzly theme uses QR codes to make it easy to locate an app on the smartphone if the user is browsing from the web on a PC. Since a static site cannot run code dynamically, this service does the job well.
 * [Cloudflare](https://www.cloudflare.com/) - This service offers a lot, but for the most part, I like to think of it as a CDN with content specific optimizations, security features, and the ability to route your content through HTTPS (for free if you use their certificate).

### Useful References

 * [Jekyll Documentation](https://jekyllrb.com/) - Everything from getting started through the first pass of details you'll need to be productive. For more advanced use, you'll also need to master some form of Markdown and probably Liquid as well, but all of the references are there.
 * [GitHub Pages with Cloudflare](https://blog.cloudflare.com/secure-and-fast-github-pages-with-cloudflare/) - This is a great article that not only goes through all of the steps required to get started with GitHub Pages, but more importantly, how to configure Cloudflare properly for routing everything through HTTPS.
 * [Bash on Ubuntu on Windows](https://msdn.microsoft.com/en-us/commandline/wsl/about) - If you're using Windows for development, WSL allows you to run a Linux shell in a Windows console. Without this, trying to use Jekyll on Windows is a royal pain. With this, it's very simple. Plus, you get to use Linux style development workflows and tools. :)

### License & Copyright

While Jekyll itself is open source, and I'm using several free services as well, all of this content is proprietary. The styling is actually a quickly ported version of a commercial Wordpress theme (Grizzly) that requires a license to use, which I have obtained. Everything else is Copyright since 2018 by Raymond Cardillo (*working under Cardillo's Creations, LLC*).

You may not reuse any of this proprietary or Copyright content without my explicit permission (e.g., html, images, text, stylesheets).
