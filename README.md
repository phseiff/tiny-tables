<h1 align="center"><img height="200px" alt="tiny-tables" src="images/repository-open-graph-image.png"></h1>

<p align="center">Stop your website's tables from overflowing on mobile with this fancy tiny trick with CSS & Javascript</p>

<p align="center">[ww](https://phseiff.com/)</p>

---

## Why (should I care)?

Tables are a great way of visualising data on a website and making sense of the clutter that countless data points and numbers tend to make.

Wikipedia, for example, tends to be quite full of tables, as are GitHub READMEs.
Most of these tables look like this:

![a large table with some lines, one of whom is pretty full](images/illustration-table-large.png)

When you view these tables on mobile, however, or on an otherwise really small screen, they tend to look like this:

![the same table, but the screen is so small that it overflows horizontally](images/illustration-table-small-crammed.png)

The tables overflow horizontally!

This hinders readability, forces users to scroll horizontally, and generally makes the mobile table experience a nuisance, plus it is, in my opinion, pretty unaesthetic.
Horizontal scrollbars should be used as a last resort and not as the standard way of doing something, especially since 60% of website visitors are mobile users nowadays.

One solution I came up with (which this repository demonstrates) is to stack the table columns once the viewport gets so small the table tries to overflow, like this:

![the same table, but for every row, the cells are shown beneath each other with different indentions](images/illustration-table-small-stacked.png)

I think this is a really neat solution, and I don't get why no website I have ever seen does this (please feel free to correct me on this if you know any).

---

<p align="center"><img src="images/resize-recording.gif" alt="GIF of a recording where the demo page is resized"/></p>

ToDo:
* Note that you need to use `display: block` with your tables in order for this to work.