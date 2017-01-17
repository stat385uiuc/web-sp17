# STAT 385 Course Website for Spring 2017

Within this repository, the source code that is behind the [STAT 385 @ UIUC](http://stat385.thecoatlessprofessor.com) Spring 2017 Course Website can be found.

Generally speaking, the website is made using the following tools:

- The backend of the site is powered by [`hugo`](https://gohugo.io/), which enables the static generation of files from [markdown](https://daringfireball.net/projects/markdown/) documents.
- The service that is hosting the website is [GitHub Pages](https://pages.github.com/) via the `gh-pages` branch. 
- To locally preview the website and convert `.Rmd` files to `.md` files, the [`blogdown`](https://github.com/rstudio/blogdown) package is employed which provides an interfaces with [`rmarkdown`](https://cran.r-project.org/web/packages/rmarkdown).
- The display of LaTeX math is done via [MathJax](https://www.mathjax.org/) code snippet that must be enabled within the post front matter with the option `mathjax:true`
- The custom domain name of `stat385.thecoatlessprofessor.com` instead of `username.github.io/repo` is done using the `CNAME` configuration file.

For more information, please refer to a future post on <http://thecoatlessprofessor.com/>.

# Structure

The folder structure of the website is given as:

- Hugo specific
    - **`_layouts`:** HTML Layout Structure
    - **`_blogdown`:** Posts converted to `.md` from `.Rmd`
    - **`_public`:** Rendered version of site
    - **`_themes`:** Installed [hugo themes](http://themes.gohugo.io/)
- Course Content
    - **`assets`:** Generation files for HW and Lecture Slides
    - **`_content`:** Source of _posts_ and main menu pages.

# License

![The work within this repository is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).](assets/images/cc.png)

