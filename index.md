For now (and probably forever) I'll just use plain text, Thank you.

2020-07-07

yrc, or Gyrc, is an app I've been looking for, for years, to control my Yamaha network receiver from my computer (in addition to the great apps for iPhone).

I found pymusiccast on Github, it is a library for doing so in Python.   So I had to write my own GUI for it, and it is now working (for me anyway).  The only configuration is to enter the ip address or hostname of your receiver, which if you use Linux, you can probably locate.   If you decide to try the app, please do so using the button at the top-right that says IP.  After you've entered something, like say 192.168.1.130 (mine, not yours probably), it will be written to a simple text file at ~/.gyrc.cfg.  Thereafter, the app will try to get the receiver's IP address from that file.  If you need to change it, just delete the file and next time you start Gyrc (Yamaha Receiver Control) it will once again show the IP button.

For now, once you've done that, edit the source code in wherever you git cloned the app in libgyrc/gyrc.py.  You'll see it at the top of the first (Yamawin) class.   If you can figure that out, you're ready to go, the rest should be obvious, but please be patient as it is under development (not fully functional and probably has bugs). Definitely has bugs, I'm sure.   It works great for me, though.

Also, please feel free to browse my code.

Thank you,

balinbob

Bob Allred

[Link to Gyrc code](https://github.com/balinbob/yrc)







## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/balinbob/balinbob.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/balinbob/balinbob.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
