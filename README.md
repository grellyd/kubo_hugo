# Kubo
## A minimal custom Theme for [Hugo](https://gohugo.io)

**Kubo** is a Hugo theme written by [@grellyd](https://github.com/grellyd) for [grellyd.com](https://grellyd.com). It is insipired by the excellent minimal theme [XMin](https://github.com/yihui/hugo-xmin/) by [Yihui Xie](https://yihui.name). 

The theme prioritises static pages and blog posts. 

Kubo is still a work in progress, and should not yet be used in a production site.

## Features

- Simple and clean
- Full social linking in base bar via `params` values
- Responsive, to an extent.
    - Simply has two stages: regular and mobile
    - Detected by `@media screen and (max-width: 800px)`
- Hide sections from the sidebar
    - Within the config.yaml's `params` section, enumerate the hidden sections.
    - These sections are navigible but do not appear in the sidebar.
- Different site title and name: 
    - A site can be named 'Kubo Hugo Theme' and have the title 'Kubo - Theme for Hugo'.
    - This was done to have full instantiated title on search pages, while maintaining a short on-page title.

## Install Requrirements

## Example Configs

```yaml
baseURL: /
title: Kubo - Minimal Hugo Theme
languageCode: en-ca
theme: kubo_hugo
disableKinds: [RSS, sitemap]
params:
    AuthorName: Graham L. Brown
    GithubUsername: grellyd
    TwitterUsername: grellyd
    LinkedInUsername: grellyd
    ContactEmail: graham@grellyd.com
    SiteName: Grellyd
    HiddenSections: [demo]
```
```toml
baseurl = "/"
title = "Kubo - Minimal Hugo Theme"
languageCode = "en-ca"
theme = "kubo_hugo"
disableKinds = ["RSS", "sitemap"]

[params]
AuthorName = "Graham L. Brown"
GithubUsername = "grellyd"
TwitterUsername = "grellyd"
LinkedInUsername = "grellyd"
ContactEmail = "graham@grellyd.com"
SiteName = "Kubo Hugo"
HiddenSections = ["demo"]
```
