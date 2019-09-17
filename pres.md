
# Motivation

1. Create a presentation :microphone:
  - for a tutorial
  - for conference

2. Use Markdown to quickly format your content

3. :Insert code examples :gear:

4. Insert your R figures :bar_chart:


# Examples

Several [formats](https://rmarkdown.rstudio.com/formats.html) available

## [ioslides](https://bookdown.org/yihui/rmarkdown/ioslides-presentation.html)

```
---
title: "ResearchDown"
author: Liam Beauchesne
output: ioslides_presentation
---
```

## [Slidy](https://bookdown.org/yihui/rmarkdown/slidy-presentation.html)

```
---
title: "ResearchDown"
author: Liam Beauchesne
output: slidy_presentation
---
```

# Usage

## [Beamer](https://bookdown.org/yihui/rmarkdown/beamer-presentation.html)

```
---
title: "ResearchDown"
author: Liam Beauchesne
output: beamer_presentation
---
```

## [PowerPoint](https://bookdown.org/yihui/rmarkdown/powerpoint-presentation.html)


```
---
title: "Habits"
author: John Doe
date: March 22, 2005
output: powerpoint_presentation
---
```

# Usage

## [xaringan](https://slides.yihui.name/xaringan/#1)

```r
install.packages("xaringan")
```

```
---
title: "Talk"
subtitle: "Symposium"
author: "Liam Beauchesne"
output:
  xaringan::moon_reader:
---
```



# Resources

- [QCBS R workshops](https://qcbsrworkshops.github.io/)
- [ioslides](https://kevcaz.github.io/pres_Rmarkdown_fr/#1)
- [xaringan](https://slides.yihui.name/xaringan/#1)


# Get started

## [xaringan](https://slides.yihui.name/xaringan/#1)


```
---
title: "Workshop 1: Introduction to R"
subtitle: "QCBS R Workshop Series"
author: "Liam Beauchesne"
output:
  xaringan::moon_reader:
    includes:
      in_header: qcbsR-header.html
    lib_dir: assets
    seal: true
    css: ["default", "qcbsR.css", "qcbsR-fonts.css"]
    nature:
beforeInit: "qcbsR-macros.js"
---

# Slides 1

1. cool
2. cool

# Slides 2

```


