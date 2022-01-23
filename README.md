## Kalyani Rajguru

You can use the [editor on GitHub](https://github.com/RajguruKalyani/rajgurukalyani.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
<div class="container">
    <header>
        ...
    </header>
    <main class="container__main">
        <!-- Left sidebar -->
        <aside class="container__left">...</aside>

        <!-- Main content -->
        <article class="container__middle">...</article>

        <!-- Right sidebar -->
        <nav class="container__right">...</nav>
    </main>
    <footer>
        ...
    </footer>
</div>
.container {
                        display: flex;
                        flex-direction: column;
                    }

                    .container__main {
                        /* Take the remaining height */
                        flex-grow: 1;

                        /* Layout the left sidebar, main content and right sidebar */
                        display: flex;
                        flex-direction: row;
                    }

                    .container__left {
                        width: 25%;
                    }

                    .container__middle {
                        /* Take the remaining width */
                        flex-grow: 1;
                    }

                    .container__right {
                        width: 20%;
                    }

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Systems 2022
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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/RajguruKalyani/rajgurukalyani.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
