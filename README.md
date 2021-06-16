# FRI Summer Fellow Poster Template

This repository contains all you need to create a poster for the end of the summer. It relies on HTML, CSS, Jinja2 and Python.

The repository is forked from Clément Pit-Claudel's `academic-poster-template` [repository](https://github.com/cpitclaudel/academic-poster-template)

## How to get started

1. Clone this repository to your local machine.
2. Open `summer_template.jinja2` in any text editor.
3. Change the poster title to your poster title on line 5.
4. Change the poster subtitle to your subtitle on line 7.
5. Change author names on lines 27-29.
6. Change the email address to your email on line 58.

## Sections to complete

* Line 68 - Executive Summary
  * Fill out your problem statement, approach, what you learned, and recommendations.
  * This should be mostly text, remember it is an industrial strength abstract.
* Line 93 - Approach
  * Give us some background on the problem (why should we care).
  * How are you solving the problem?
  * Introduce data, models, and why you decided to use this approach.
  * There are examples of how to include math and equations.
* Line 123 - Results and Lessons Learned
  * What did you find in your research?
  * What did you learn along the way?
  * This is your chance to add images, graphs, and other rad things. There are examples of how to embed images and figures into your poster in the template.
* Line 135 - Recommendations
  * What do we do now?
  * What do you recommend for future work?
  * What should the plan of action be for stakeholders?
* Line 143 - Acknowledgements
  * Time to thank those who helped you along the way

Once you have completed the sections it is time to build your poster. To do this save `summer_template.jinja2` with a different name (e.g. `transformer_team.jinja2`) in the same directory. Next, open up a terminal and `cd` into the `academic-poster-template` directory. From here you want to render your `jinja2` file into html. To do this from the terminal run `python ./render.py transformer_team.jinja2 transformer_poster.html`. This will run `render.py` and convert `transformer_team.jinja2` and associated files into a html file named `transformer_poster.html`. Last, open the html file and admire all your hard work!

For more information on formatting, images, inline math and more [check out the full tutorial](https://cpitclaudel.github.io/academic-poster-template/tutorial/poster.html).

![Energy Analytics Logo](https://github.com/jessepisel/academic-poster-template/blob/main/example_template.PNG?raw=true)
