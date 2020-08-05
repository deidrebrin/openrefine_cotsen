---
title: "Filtering and Sorting with OpenRefine"
teaching: 15
exercises: 10
questions:
- "How can we select only a subset of our data to work with?"
- "How can we sort our data?"
objectives:
- "Filter to a subset of rows by text filter or include/exclude."
- "Sort table by a column."
- "Sort by multiple columns."
keypoints:
- "OpenRefine provides a way to sort and filter data without affecting the raw data."
---

# Lesson

## Filtering

In addition to faceting, you can subset your data and work on just that subset using filters. 

1. Click the down arrow next to `trench` > `Text filter`. A `trench` facet will appear on the left margin.
2. Type in `1` and press return. 


### Include/exclude and invert

Any filtering can be inverted by clicking on the `invert` button at the top of the filter window. Similarly, facets can be altered to either `include` or `exclude` specific entries. These tools can be combined to drill down into your data further.

Faceting and filtering look very similar. A good distinction is that faceting gives you an overview description of all of the data that is currently selected, while filtering allows you to select a subset of your data for analysis.

Remove the filter before moving on so that you again have the full dataset.

## Sort

You can sort the data by a column by using the drop-down menu in that column.
There you can sort by `text`, `numbers`, `dates` or `booleans` (`TRUE` or `FALSE` values). You can also specify what order to put `Blanks` and `Errors` in the sorted results.

You can sort by multiple columns by performing sort on additional columns. The sort will depend on the order in which you select columns to sort. To restart the sorting process with a particular column, check the `sort by this column alone` box in the `Sort` pop-up menu.

Sorts can be adjusted or removed using the `Sort` dropdown that appears along the top once a sort has been applied.


{% include links.md %}
