# DS4SI


packages <- c('shiny', 'tidyverse, 'shinyWidgets 'DT', 'gridExtra', 'shinyjs', 'shinyBS', 'viridis')
install.packages(packages)
shiny::runGitHub("thinkCausal_dev", "gperrett", subdir = 'DS4SI-tool-JH', launch.browser = TRUE)
