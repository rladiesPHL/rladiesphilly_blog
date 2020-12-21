# rladiesphilly_blog update

Tested under most updated blogdown (0.21.50) and hugo (0.79.0)
Theme documentation: https://wowchemy.com/docs/page-builder/

## Install blogdown and hugo
```R
devtools::install_github('rstudio/blogdown')
blogdown::install_hugo("0.79.0")
# blogdown::update_hugo()
```

## Set hugo run 0.79.0
```R
options(blogdown.hugo.version = "0.79.0")
```

## Useful troubleshoot method

```R
blogdown::build_site()
```

(sh) figure out hugo theme

```sh
cd rladiesphilly_blog2
hugo mod graph
``` 


## serve site

```R
blogdown::serve_site()
```

### solve resize and float
https://mangolassi.it/topic/21564/how-can-i-scale-an-image-in-a-hugo-page/24
https://wowchemy.com/docs/writing-markdown-latex/
