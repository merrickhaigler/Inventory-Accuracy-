# Inventory-Accuracy

Effectively displaying Inventory Accuracy with Circles

Inventory Accuracy is a simple thing to define. Without being overly redundant, it is the accuracy of one's inventory. To break it down even further, it is the amount of inventory one believes they have, versus what they actually have.

But, this idea has lost meaning due to the differences in ways it is calculated. When one is using exact match, total magnitude, SAV, SMAPE, or any other approach, they are not gettinig the full story.

In this visualization, we can effectively view the data with no metric attached. Each circle represents a single SKU, and the size of that circle is derived from the depth of the SKU. The rest is simple; Green is good, grey and blue are okay, and red is bad. There is no further interpretation needed.

We have given the user the ability to seperate the inventory based on the overstated, equal, and understated. We can also isolate the frozen out-of-stock SKUs to focus on those that are causing the most harm to our store.

There is also the option to grade each SKU based on its individual eror using SMAPE (Symmetric Mean Absolute Percentage Error). We also included a severity heatmap based on the SMAPE formula which we encourage you to read about here: https://towardsdatascience.com/choosing-the-correct-error-metric-mape-vs-smape-5328dec53fac

Again, the purpose of this visual is to effectively display the Inventory Accuracy of a large amount of SKUs without numeric values.
