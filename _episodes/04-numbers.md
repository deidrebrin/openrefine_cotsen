---
title: "Examining Outliers in OpenRefine"
teaching: 5
exercises: 5
questions:
- "How can we see numeric outliers?"
objectives:
- "Transform a values for a subset of the data."
keypoints:
- "OpenRefine also provides ways to get overviews of numerical data."
---

# Lesson

## Dates

Dates often cause issues in datasets when entered by hand. Let's examine the `date` column next! Quickly glancing over the column shows that the dates have been entered in various formats, even though the registry manual clearly states dates should be entered day/month/year. But we should be able to correct that easily!

1. Click the down arrow at the top of the `date` column. Choose `Edit cells` and then `Common transformations` and then `To date`.
2. Uh oh...it looks like OpenRefine wasn't able to distinguish between the month/day and the day/month entries! Undo the transformation.
3. Let's try a different approach then. Click the down arrow at the top of the `date` column and this time select `Facet` then `Text facet` since these values appear to have been entered as text fields. 
4. We can now edit all of the month/day values to match the format that was outlined in the registry manual! 

## Finding outliers - numbers

As we saw with the text faceting, OpenRefine allowed us to easily see typos and entry errors in our text fields. Using the  facet tool can also bring to light numeric outliers. 

It appears as though Jane Doe didn't read the registry manual very carefully and we're concerned the weights might have also been misentered. So let's look at our `weight` column next but using a numeric facet this time. 

1. Click on the down arrow at the top of the `weight` column.
2. Select `Facet` then `Numeric facet`.
3. Adjust the slider bars to see the two outliers.

Now that we can see the data associated with the outliers, it appears all of the weight values by Jane Doe were entered in grams instead of kilograms. Let's correct them all!

1. We know we need to correct all of Jane's entries so remove the numeric facet and create a text facet on the `recorder` column instead.
2. Restrict the records to just those entered by `Jane Doe`.
3. Once again, click on the down arrow at the top of the `weight` column and this time select `Edit cells` then `Transform`.
4. We know that there are 1000 grams in a kilogram so we can edit the entries to the correct unit by dividing the current value by 1000. Let's use Python this time!
5. Select `Python / Jython` then enter `return value/1000.00` so that we have two places after the decimal point returned. Check the results in the preview pane. 
6. Click `Ok`.


{% include links.md %}
