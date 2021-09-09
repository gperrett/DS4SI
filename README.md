# DS4SI

```
packages <- c('shiny', 'tidyverse, 'shinyWidgets 'DT', 'gridExtra', 'shinyjs', 'shinyBS', 'viridis')


lapply(packages, require, character.only = TRUE)


shiny::runGitHub("DS4SI", "gperrett", subdir = 'DS4SI-tool-JH', launch.browser = TRUE)
```