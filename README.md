FishMaps
========

Producing maps for fishery data in batch mode

# Introduction

FishMaps was designed to plot fishery data (catch, effort, CPUE) into
maps. However, any kind of georeferenced data can be used.

# Installation

Download the source code and

* install via the command line

  	  R CMD INSTALL -l /path/to/your/R/library FishMaps<version>.tar.gz
or

* inside an R session

  	 install.packages("FishMaps<version>.tar.gz", repos = NULL,
                          lib.loc = "/path/to/your/R/library")

For example, a small section of my `~/.Rpackages` looks like this:

        list(
            default = function(x) {
              file.path("~/documents/", x, x)
            }, 

          "describedisplay" = "~/ggobi/describedisplay",
          "tourr" =    "~/documents/tour/tourr", 
          "mutatr" = "~/documents/oo/mutatr"
        )