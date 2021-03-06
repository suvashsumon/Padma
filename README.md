# Padma
Padma is a minimal hugo theme for blogger and writer made with bootstrap 4.
View Demo : https://padma-hugo.netlify.app/

![Screenshot](screenshot.jpg)

# Requirements
You need to connect with internet to use bootsrap 4 from their cdn.

# How to use
Download this repo and paste to themes folder. Then go to config.toml file and add content like bellow:
```
baseURL = "http://example.org/"
languageCode = "en-us"
title = "Padma"
theme = "padma"

enableInlineShortcodes = true

summarylength = 10
enableEmoji = true

[params]
author = "Suvash Kumar"
description = "Developer & Blogger"

# Builder name
builtWith = "gohugo"

copyright = "Suvash Kumar"
# license = ""
# licenseURL = ""

## Set custom CSS and/or JS to override site defaults.
customCss = ["css/blog.css"]
customJs = ["js/blog.js"]

  ## Set as many as you want.
  [[params.socialIcons]]
  icon = "fa-linkedin"
  title = "Linkedin"
  url = "https://www.linkedin.com/in/suvash-kumar-544b5917b"

  [[params.socialIcons]]
  icon = "fa-github"
  title = "GitHub"
  url = "https://github.com/suvashsumon"

  [[params.socialIcons]]
  icon = "fa-twitter"
  title = "Twitter"
  url = "https://twitter.com/SuvashK13937007"

  [[params.socialIcons]]
  icon = "fa-facebook"
  title = "Facebook"
  url = "https://facebook.com/suvashkumar.sumon"

  [[params.socialIcons]]
  icon = "fa fa-envelope"
  title = "Email"
  url = "mailto:suvashkumar.naogaon@gmail.com"

[menu]

  [[menu.main]]
  name = "Tags"
  weight = 100
  identifier = "tags"
  url = "/tags/"

 [[menu.main]]
  name = "Categories"
  identifier = "categories"
  weight = 200
  url = "/categories/"

  [[menu.main]]
  name = "About Me"
  identifier = "about"
  weight = 300
  url = "/about-me/"





[taxonomies]
  category = "categories"
  series = "series"
  tag = "tags"

[markup]

  [markup.highlight]
  codeFences = true
  guessSyntax = false
  hl_Lines = ""
  lineNoStart = 1
  lineNos = false
  lineNumbersInTable = true
  noClasses = true # if false, you need to provide you own custom CSS
  style = "monokai"
  tabWidth = 4

```
