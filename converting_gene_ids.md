# Converting Gene Identifiers

A very common task in genomics is converting between the most popular gene identifiers. A good way of dealing with this I have found is to use the `annotables` package, coupled with `dplyr` for table joins (typically `left_join()` or `inner_join()`, depending on what you want to do with non-matches)

* [stephenturner/annotables](https://github.com/stephenturner/annotables)
* [dplyr](http://dplyr.tidyverse.org/)
