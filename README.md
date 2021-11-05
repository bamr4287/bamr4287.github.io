---
title: Home
description: This is where you start your journey
permalink: /index.html
categories:
  - Readme
  - Home
  - Start
  - Jekyll
  - Github
  - Pages
  - Markdown
toc: true
toc_sticky: true
lastmod: '2021-11-05T22:37:15.627Z'
sidebar: toc
---
# Hello World

_This is my Jekyll site with all my documentation and journals_

## Feature List: 

- [x] Code Copy button
- [x] Side table of contents
- [x] Add quick edit links to GitHub and VS Code
- [ ] Dark Mode toggle
  - [ ] [JTD](https://pmarsceill.github.io/just-the-docs/docs/customization/)
- [x] Navigation bar dropdown
- [x] auto genereate sidebar
- [ ] alternate TOC structures (easy/med/hard) (pc/mac/linux) (by role)
- [ ] Tool box page
- [ ] Contribution Instructions
- [ ] Search engine
- [x] Programming Language cheat sheets
- [x] Accordion TOC
- [x] bootstrap4
- [x] auto navbar 
  - [ ] [Just the Docs](https://pmarsceill.github.io/just-the-docs/docs/navigation-structure/)
- [ ] Add back to [top button](https://jun711.github.io/web/how-to-highlight-code-on-a-Jekyll-site-syntax-highlighting/) in cellphone view
- [ ] add [plugins](https://jekyllcodex.org/without-plugins/) without plugins
- [ ] Auto integrate/embed source code files into documentation
- [ ] UI testing automation - [Selenium](https://www.selenium.dev/)
- [ ] code snippet syntax [highlighting](https://jun711.github.io/web/how-to-highlight-code-on-a-Jekyll-site-syntax-highlighting/) 

```javascript
document.write('Hello, world!');

```
[Java Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Edit in [VSCode](vscode://file/C:/Users/AmrAbdel-Motaleb/OneDrive/Documents/GitHub/{{ page.path}})

this page's path is {{ page.path}}

```powershell
vscode://file/C:/Users/AmrAbdel-Motaleb/OneDrive/Documents/GitHub/{{ page.path}}

```
```bash
code $HOME/Github/
```

```liquid
{% raw %}
{{site.github.repository_url}}
{% endraw %}
```

```html
{%raw %}
<div class="sidebar__top">
  <a href="'''liquid{{site.github.repository_url}}'''/blob/gh-pages/{{page.name}}">
    <i class="fab fa-github-square"></i>
  </a>
  <a href="vscode://file{{ site.local_git_pc}}/{{ site.local_repo }}/{{ page.path }}">
    <i class="fas fa-laptop-code"></i>
  </a>
  <a href="vscode://file{{ site.local_git_mac}}/{{ site.local_repo }}/{{ page.path }}">
    <i class="fas fa-laptop-code"></i>
  </a>
  <a href="#page-title" class="back-to-top">{{ site.data.ui-text[site.locale].back_to_top | default: 'Back to Top' }} &uarr;</a>
</div>
{% endraw %}
```


[source](https://stackoverflow.com/questions/48641921/is-it-possible-to-use-the-vscode-hyperlink-to-open-a-file-or-directory-in-code)

## Project List:

- [ ] Jekyll Theme - Zer0-Mistakes
- [ ] Documentation site [it-journey](../it-journey/)
  - [Jekyll Doc Theme](https://idratherbewriting.com/documentation-theme-jekyll/index.html)
  - [Markdown Guide](https://www.markdownguide.org/) 
- [ ] Create Github Lab Course
- [ ] Initializing your world

# Info

This is your static site where you store all your tools/tips/tricks and any other piece of information your fellow citizens can leverage.

To even get to this point, you need to complete the following quests:
   1. Command and Conquer
   2. Git you shit
   3. Dr. Jekyll and Mr. Hub

[Local Site Address](http://127.0.0.1:4001/)

[Public Site Address](http://bamr87.github.io/)

If you want to customize the theme, copy the _layouts folder into your gihub root dir.

Currently using the [Minimal Mistakes Theme](https://mmistakes.github.io/minimal-mistakes/).

You can use the [editor on GitHub](https://github.com/bamr87/bamr87.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Markdown Guide](https://www.markdownguide.org/)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/bamr87/bamr87.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

The source code for this theme is at [Minima](https://github.com/jekyll/minima)

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
