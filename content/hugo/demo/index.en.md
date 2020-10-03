---
title: Notes from the demo
menuTitle: Demo
weight: 5
slides: true
output: hugodown::md_document
rmd_hash: efd1fe50145291c0

---

-   install the remotes package, `install.packages("remotes)`

-   install the hugodown package, [`remotes::install_github("r-lib/hugodown")`](https://remotes.r-lib.org/reference/install_github.html)

-   [`hugodown::hugo_install('0.66.0')`](https://rdrr.io/pkg/hugodown/man/hugo_install.html)

-   [`hugodown::create_site_academic()`](https://rdrr.io/pkg/hugodown/man/create_site_academic.html). Be happy to see everything happening automatically :sparkles:

-   [`hugodown::hugo_start(render_to_disk = TRUE)`](https://rdrr.io/pkg/hugodown/man/hugo_start.html), open localhost in the browser.

-   Change site title and [theme](https://sourcethemes.com/academic/themes/) in config/\_default/params.toml. Yes a theme for a theme!

-   Mention [academic docs](https://sourcethemes.com/academic/), all the things one can change.

-   [`hugodown::use_post("post/new-rmd-post")`](https://rdrr.io/pkg/hugodown/man/use_post.html), knit, see post.

-   say there will probably be other themes later. show [Hugo theme gallery](https://themes.gohugo.io/) and how I would choose themes.

-   [`usethis::use_github()`](https://usethis.r-lib.org/reference/use_github.html), [`hugodown::use_netlify_toml()`](https://rdrr.io/pkg/hugodown/man/use_netlify_toml.html), go to Netlify interface.

-   add URL to config

