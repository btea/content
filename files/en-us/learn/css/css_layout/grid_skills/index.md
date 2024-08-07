---
title: "Test your skills: Grid"
slug: Learn/CSS/CSS_layout/Grid_skills
page-type: learn-module-assessment
---

{{LearnSidebar}}

The aim of this skill test is to assess whether you understand how a [grid and grid items](/en-US/docs/Learn/CSS/CSS_layout/Grids) behave. You will be working through several small tasks that use different elements of the material you have just covered.

> [!NOTE]
> You can try solutions in the interactive editors on this page or in an online editor such as [CodePen](https://codepen.io/), [JSFiddle](https://jsfiddle.net/), or [Glitch](https://glitch.com/).
>
> If you get stuck, you can reach out to us in one of our [communication channels](/en-US/docs/MDN/Community/Communication_channels).

## Task 1

In this task, you should create a grid into which the four child elements will auto-place. The grid should have three columns sharing the available space equally and a 20-pixel gap between the column and row tracks. After that, try adding more child containers inside the parent container with the class of `grid` and see how they behave by default.

Your final result should look like the image below:

![A three column grid with four items placed into it.](grid-task1.png)

Try updating the live code below to recreate the finished example:

{{EmbedGHLiveSample("css-examples/learn/tasks/grid/grid1.html", '100%', 700)}}

> [!CALLOUT]
>
> [Download the starting point for this task](https://github.com/mdn/css-examples/blob/main/learn/tasks/grid/grid1-download.html) to work in your own editor or in an online editor.

## Task 2

In this task, we already have a grid defined. By editing the CSS rules for the two child elements, cause them to span over several grid tracks each. The second item should overlay the first as in the image below:

![A box with two items inside one overlaying the other.](grid-task2.png)

Try updating the live code below to recreate the finished example:

{{EmbedGHLiveSample("css-examples/learn/tasks/grid/grid2.html", '100%', 900)}}

Additional question:

- Can you now cause the first item to display on top without changing the order of items in the source?

> [!CALLOUT]
>
> [Download the starting point for this task](https://github.com/mdn/css-examples/blob/main/learn/tasks/grid/grid2-download.html) to work in your own editor or in an online editor.

## Task 3

In this task, there are four direct children in this grid. The starting point has them displayed using auto-placement. Use the grid-area and grid-template-areas properties to lay the items out as shown in the image below:

![Four items displayed in a grid.](grid-task3.png)

Try updating the live code below to recreate the finished example:

{{EmbedGHLiveSample("css-examples/learn/tasks/grid/grid3.html", '100%', 800)}}

> [!CALLOUT]
>
> [Download the starting point for this task](https://github.com/mdn/css-examples/blob/main/learn/tasks/grid/grid3-download.html) to work in your own editor or in an online editor.

## Task 4

In this task, you will need to use both grid layout and flexbox to recreate the example as seen in the image below. The gap between the column and row tracks should be 10px. You do not need to make any changes to the HTML in order to achieve this.

![Two rows of cards, each with an image and a set of tags.](grid-task4.png)

Try updating the live code below to recreate the finished example:

{{EmbedGHLiveSample("css-examples/learn/tasks/grid/grid4.html", '100%', 2000)}}

> [!CALLOUT]
>
> [Download the starting point for this task](https://github.com/mdn/css-examples/blob/main/learn/tasks/grid/grid4-download.html) to work in your own editor or in an online editor.
