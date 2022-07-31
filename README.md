## KeymanWeb հայկական մնեմոնիկ ստեղնաշարի համար

&nbsp;&nbsp;&nbsp;&nbsp;Սա վեբ-էջի մի նմուշ է «Armenian Mnemonic R» ստեղնաշարը ցուցադրելու համար: Այս վեբ էջը հրապարակված է հետևյալ կայքում. [https://dotland.github.io/keymanweb-demo-hy-r/](https://dotland.github.io/keymanweb-demo-hy-r/):

&nbsp;&nbsp;&nbsp;&nbsp;[KeymanWeb](https://keymanweb.com/)-ը վեբի համար՝ բաց կոդով մուտքագրման մեթոդի համակարգ է, որը հասանելի է ինչպես համակարգիչների, այնպես էլ սենսորային սարքերի համար: [KeymanWeb](https://keyman.com/developer/keymanweb/)-ը կարող է ավելացվել ձեր վեբ-կայքում ընդամենը մի քանի տող կոդով:

KeymanWeb-ի նախապայման ֆայլերը.

```js
<script src="https://s.keyman.com/kmw/engine/14.0.293/keymanweb.js"></script>
<script src="https://s.keyman.com/kmw/engine/14.0.293/kmwuitoggle.js"></script>
```

Ներառեք ստեղնաշարը կոդի հետևյալ ֆրագմենտով.

```js
keyman.addKeyboards({
    id: 'armenian_mnemonic_r',
    name: 'Armenian Mnemonic R',
    languages: { 
        id: 'hy', 
        name: 'Armenian', 
        region: 'Asia',
        font: {
            family: 'Sylfaen',
            source: ['./font/Sylfaen.ttf']
        }
    }, 
    filename: 'https://github.com/dotland/mnemonic-kb-hy-r/releases/latest/download/hymr.js'
});
```

Ստեղնաշարի .js ֆայլը կարող է ստեղծվել [Keyman Developer](https://keyman.com/developer/)-ի միջոցով:


### Հղումներ

<a id="1">&nbsp;&nbsp;1.&nbsp;</a>
[«Armenian Mnemonic R» Keyman ստեղնաշարը:](https://github.com/dotland/mnemonic-kb-hy-r/blob/main/README.md) <br />

<!-- You can use the [editor on GitHub](https://github.com/dotland/keymanweb-demo-hy/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

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

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dotland/keymanweb-demo-hy/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out. -->
