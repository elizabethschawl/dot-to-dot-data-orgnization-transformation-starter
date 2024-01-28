# DOT to Dot

Data Organization and Transformation

## Objectives

- Execute basic data organization and transformation
- Create plots from data table
- Manage files in GitHub and VS Code
- Write in Markdown

## Deliverables

- Blog post in Markdown
- six visualizations of provided data

## Instructions

### General

Make an instructional blog post about how to transform data in `blogpost.md`.

Follow along with the steps below. When they are complete, write up
your data exploration steps as an instructional blog post. This
exercise is to help you engrain the transformation steps by visualizing
each step as you go. The instructions you write should be sufficiently
detailed that another person could follow them, and understand what
is happening with the data. Typically, 3 or 4ish sentences.

Write the blog post as if it could be viewed by the public. The
next lab will create a GitHub website with blog posts that actually
_can_ be viewed online!

Record references you used in this lab.
Relevant in-line references should be included like this
[[1](https://commonmark.org/help/),
[2](https://www.markdownguide.org/extended-syntax/#tables)].
The referenced links should also appear in the Reference Section of
the deliverable markdown file as a numbered list like this:

1. https://commonmark.org/help/
2. https://www.markdownguide.org/extended-syntax/#tables

### Steps

#### Preliminary Steps (not for blog)

- TODO: download [Visual Studio Code](https://code.visualstudio.com/download)
  for your operating system
- TODO: Download (and unzip if necessary) the lab from GitHub so that you have
  a local copy.
- Optional: Move the downloaded folder to a folder dedicated to this course
- TODO: In VS Code, go to File > New Window
- TODO: Drag and drop your download lab into the New Window
- TODO: Double click on the files located on the left-hand side to view/edit
    - it will be helpful to open both README.md and blogpost.md
    - it will also help to open the preview
        - right click on top tab that shows the filename, e.g. README.md
        - select `Open Preview`
- TODO: If you have questions, post them in Discord
- TODO: Copy the data out of `data.md` into Google Sheets
    - name the sheet with something you can find again
    - if copy/paste fails, consider using helpful online conversion tools
    [3](https://tableconvert.com/markdown-to-excel)
    - If you would like to do data organization and transformation
    with code, you may.

#### Steps that will be useful for blog

- TODO: Create a top-level heading in blogpost.md that says `Data Organization and Transformation`
- TODO: Create an H2 heading in blogpost.md that says `References`
- TODO: Create at least 3 other headings with reasonable text to describe what you are doing
  between the top-level and the references. For now, say `section 1`,`section 2`, `section 3`.

<br>

- TODO: fill out the list below with the requested information and copy it into blogpost.md.

<br>

- Number of initial variables:
- Number of initial observations:
- List of variable names:
- Range of `rawdata`:
- Range of `y`:

<br>

- TODO: make a line plot of `rawdata` alone
- TODO: download or screenshot this and add the files to assets/images
- TODO: name the line plot file `line-initial`
    - the . ending can be any format (.png, .jpg, etc.)

The raw data in the `rawdata` variable needs to undergo three
transformations in order to be interpretable as `x`. The exercise here is
to plot, transform, plot, transform etc... so that you can visualize
what each transformation step does. Only steps that update the `rawdata`
variable need to be plotted as a line plot.

- TODO: Apply the transformation that counts how many times a given observation
  in `rawdata` can be split in half.
    - For example, 8 can be split in half 3 times.
    - 16 can be split in half 4 times.
    - More info on this here
      [[4](https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:logs/x2ec2f6f830c9fb89:log-intro/a/intro-to-logarithms)]
- TODO: make/name the : `line-01` (all file extensions are fine)
- TODO: from the result of the previous TODO, scale the observations
  up by 10.
- TODO: make/name the plot: `line-02`
- TODO: from the result of the previous TODO, apply the `sign`
  variable to each observation.
    - Example: the sign of -1 applied to the number 1.4 is -1.4
    - Example: the sign of 1 applied to the number 1.4 is 1.4
    - Hint: think about what happens when you apply unit scaling to any number
- TODO: make/name the plot: `line-03`

Congratulations! You have created half of the x variable needed for your final plot.
To generate the second half of the x variable needed for the final plot continue
with the TODOs below. The goal is to create a reflection of the data with respect to
a constant value of 60. (Reflection over the vertical line x=60)

- TODO: from the result of the previous TODO, find the horizontal distance to the
  value 60
- TODO: from the result of the previous TODO, shift the observations by twice that
  amount.
	- Do not change the y values
- TODO: make/name the plot: `line-04`

Now all the data exists! The next process is to organize the data by the `pattern`
and `order-in-pattern` variables.

- TODO: determine if you need to sort by range or by sheet
- HINT: consider the possible hack of selecting all the data and then sorting by
  range with advanced options 😉
- TODO: actually do the sorting, or confirm it is complete

Now the data is fully transformed and organized. A full shape will be revealed
by plotting as a scatter plot,
all the <x,y> points and the <reflected x,y> points in a
Euclidean 2D space. This may or may not be possible in Google Sheets.
Decimals can be approximated if drawing by hand.
As you plot, connect the points in the order indicated by the variable
`order-in-pattern`. Additionally, restart the point connections when the
`pattern` variable is changed. Use any tool you like, or draw by hand.

- [recommended tool](https://www.geogebra.org/classic)
- TODO: download or screenshot the final image you generate to be added to the blog post.  
- TODO: if you draw by hand, you must upload a good photo of the drawing.
- TODO: name it `final`

### Questions

In addition to writing the instructional blog post to engrain what each transformation
does and looks like, please make sure that you answer the following questions.

- TODO: what is the difference between scaling and shifting?
- TODO: what is a logarithm?
- TODO: what was most difficult about the process of transformation?

### Summary of Formulas

- TODO: complete this summary table of the formulas you typed into sheets and
  add it to blogpost.md

| Transformation Name | Formula | Visual Impact |
|---------------------|---------|---------------|
|
|
|
|
|

### Copy your data into data-complete.md

- TODO: copy and paste you fully transformed data into data-complete.md

## Resources

1. https://commonmark.org/help/
2. https://www.markdownguide.org/extended-syntax/#tables
3. https://tableconvert.com/markdown-to-excel
4. https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:logs/x2ec2f6f830c9fb89:log-intro/a/intro-to-logarithms
5. https://www.geogebra.org/classic
