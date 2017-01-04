# Removing maximum/minimum values

If you're using a scale for quantitative data (numbers), you can sometimes delete the top and bottom values to simplify your scale.

![](assets/ai-no-outsides.png)

The basic idea is **keep numbers that are important or that your reader cannot guess**, and delete anything else.

* If we can be **absolutely sure** what the bottom number is, we can delete it.
* If we can be **relatively sure** what the top number is, we can delete it.
* If it **doesn't matter** what the bottom number is, we can delete it.
* If it **doesn't matter** what the top number is, we can delete it.

## Example

You have a graphic of data points from 0-100, with even breaks.

![](assets/ai-horizontal-standard.png)

If we deleted the top and bottom values, it would look something like this:

![](assets/ai-no-outsides.png)

It looks cleaner, but should we do that? Let's look at a few times you would or would not remove the outer bounds of a scale. **This is not a complete list**, but it should help you think through your options.

* **Being absolutely sure:** If we're counting objects, 0 is clearly the smallest number, so we can delete the bottom of our scale.
* **Being relatively sure:** If the data values *above 80* are 1200, 9000 and one million, **people can't guess that** so we should mark 1,000,000 at the end of the scale.
* **Bottom doesn't matter:** If we're measuring average temperature in a country, we **can assume the reader knows** that nowhere is -400°F, and "below 20" is meaningful enough. In that case, we can delete the bottom of our scale.
*  **Top doesn't matter:** Maybe we're mapping wealth in an area, and most people make about $40k. There are a few neighborhoods of rich people, and a few neighborhoods of poorer people. Even though making $500k is a *lot more* than the average, for this map it might just be considered "much richer than others," and **we don't care about the specifics.** In that case, we can delete the top of our scale.