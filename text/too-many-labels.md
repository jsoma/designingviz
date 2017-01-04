# Too many labels

If you have a lot of data points and every single one of them is labeled, **get rid of some of those labels!** They aren't all important, I promise.

![](assets/ai-too-many-labels.png)

The point of a visualization is you're **presenting a curated view of the data underneath**. If someone really wants to note every single datapoint, point them towards a spreadsheet.

## Other options

Another good solution might be **interactivity**. It can be a crutch, but if you want people to be able to explore each and every data point, you can make them click or hover.

## In the wild
  
[This Vice piece](https://news.vice.com/story/american-educators-teach-longer-for-less-pay-than-their-foreign-peers) by [Spe Chen](http://spepechen.github.io/) has a lot of dots but **only labels the important ones** (outliers + averages + a few others).

![](assets/teacher-pay-1.png)

## Example

You've mapped the 100 largest cities in the world, sizing the circles according to their population. If **you've labeled each city with its name**, it's too many labels. Heck, if you have *twenty* circles and you've labeled all of them it's still too many.

Instead, pick the largest (or most interesting) five and give them annotations.

If you'd really like to include the other information, you can:

  * **Static graphic:** Provide a chart to the side of the graphic, listing each city and their population
  * **Interactive graphic:** Allow people to hover over the circles, and get a little hover explaining what the city with population details.

## Example

You have a **pie chart** of city expenditures. The city spends money on 25 different things, but most of the categories are only 0.2% of the budget.

Those super-small slices really don't matter, since they'll be dwarfed by the large categories. Combine them together into an **Other** category, and explain what the category contains in a footnote.