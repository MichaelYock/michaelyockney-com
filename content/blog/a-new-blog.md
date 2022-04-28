---
layout: blog
title: A New Blog
date: 2022-04-19T05:27:24.800Z
---

This site is built with [Gatsby](https://www.gatsbyjs.com/), hosted on [Netlify](https://www.netlify.com/), originally cloned from [Kyle Mathews](https://twitter.com/kylemathews) [Gatsby-starter-blog](https://github.com/gatsbyjs/gatsby-starter-blog).

**Repo** is at [https://github.com/MichaelYock/michaelyockney-com](https://github.com/MichaelYock/michaelyockney-com).

**CMS** is [NetlifyCMS](https://www.netlifycms.org/). I like the simplicity of pushng markdown to a git repo, but not wild about being tied to Netlify Identity as auth. Id be interested in a similar project thats platform agnostic, using your preferred source control for auth (Could that be done with Cloudflare Workers?).

**Fonts** are <span style="font-family: var(--font-heading)">Oswald</span> and Source Serif Pro, via fontsource.

**Canonical URLs** are generated with [gatsby-plugin-react-helmet](https://github.com/gatsbyjs/gatsby/tree/master/packages/gatsby-plugin-react-helmet) and [gatsby-plugin-react-helmet-canonical-urls](https://github.com/NickCis/gatsby-plugin-react-helmet-canonical-urls). Initially I just used Helmet to add a canonical link to the SEO component, but for completeness regarding https/http, www/no-www and some edge cases, I opted not to reinvent the wheel.

**Syntax Highlighting** is [Prismjs](https://prismjs.com/) with [Dracula Theme.](https://draculatheme.com/)
eg:
```python
print("Hello, world!")
for i in range(10):
    print(i)
```