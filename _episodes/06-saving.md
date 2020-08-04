---
title: "Exporting and Saving Data from OpenRefine"
teaching: 5
exercises: 5
questions:
- "How can we save and export our cleaned data from OpenRefine?"
objectives:
- "Save an OpenRefine project."
- "Export cleaned data from an OpenRefine project."
keypoints:
- "Cleaned data or entire projects can be exported from OpenRefine."
- "Projects can be shared with collaborators, enabling them to see, reproduce and check all data cleaning steps you performed."
---

# Lesson

## Saving and Exporting a Project

In OpenRefine you can save or export the project. This means you're saving the data and all the 
information about the cleaning and data transformation steps you've done. Once you've saved a project, you can
open it up again and be just where you stopped before.

### Saving

By default OpenRefine is saving your project continuously. If you close OpenRefine and open it up again,
you'll see a list of your projects. You can click on any one of them to open it up again.

### Exporting and importing projects

You can also export a project. This is helpful, for instance, if you wanted to send your raw data and cleaning steps to a collaborator, 
or share this information as a supplement to a publication. 

You can import an existing project into OpenRefine by clicking `Open...` in the upper right > `Import Project` and selecting the `tar.gz` 
project file. This project will include all of the raw data and cleaning steps that were part of the original project.

## Exporting Cleaned Data 

You can also export just your cleaned data, rather than the entire project.

1. Click `Export` in the top right and select the file type you want to export the data in. `Tab-separated values` (`tsv`) or `Comma-separated values` (`csv`) would be good choices.
2. That file will be exported to your default `Download` directory. 

{% include links.md %}
