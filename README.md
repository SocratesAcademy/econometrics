# Econometrics

This is the repository for slides for the PhD level course in Econometrics at the Tinbergen Institute, Amsterdam. 
A short description of the course can be found on the university website: https://www.tinbergen.nl/courses/520/econometrics-ii

The outline of the course ([syllabus](https://github.com/stnavdeev/econometrics/blob/main/syllabus.pdf)):
1. [Censored regression, selection model, weak IV, and quantile regression](https://github.com/stnavdeev/econometrics/blob/main/tutorial1/tutorial1.pdf)
2. [Static linear panel data models](https://github.com/stnavdeev/econometrics/blob/main/tutorial2/tutorial2.pdf)
3. [Potential outcomes model, randomized experiments, and power analysis](https://github.com/stnavdeev/econometrics/blob/main/tutorial3/tutorial3.pdf)
4. [Natural experiments and LATE](https://github.com/stnavdeev/econometrics/blob/main/tutorial4/tutorial4.pdf)
5. [Difference-in-differences design](https://github.com/stnavdeev/econometrics/blob/main/tutorial5/tutorial5.pdf)
6. [Regression discontinuity design](https://github.com/stnavdeev/econometrics/blob/main/tutorial6/tutorial6.pdf)
7. [Summary of the course](https://github.com/stnavdeev/econometrics/blob/main/tutorial7/tutorial7.pdf)

The recommneded books are:
1. The Effect: An Introduction to Research Design and Causality by Nick Huntington-Klein: https://theeffectbook.net/index.html
2. Causal Inference: The Mixtape by Scott Cunningham: https://mixtape.scunning.com/index.html
3. Microeconometrics: Methods and Applications by Colin Cameron and Pravin Trivedi.

The slides are based on the teaching materials from:
1. Econometrics Course by Nick Huntington-Klein: https://github.com/NickCH-K/EconometricsSlides
2. Causality Inference Course by Nick Huntington-Klein: https://github.com/NickCH-K/CausalitySlides
3. Applied Empirical Methods Course by Paul Goldsmith-Pinkham: https://github.com/paulgp/applied-methods-phd

The code to generate all slides is availible in each folder in .Rmd format. If you knit these .Rmd files, you will create slides in .html format which is handy to open in a browser (there are also a few dynamic graphs that work only in a browser). If you want to compile slides in .pdf format, then:
- Knit .Rmd file that creates .html slides;
- Type "pagedown::chrome_print("tutorial1.html", output="tutorial1.pdf")" without quotation marks in the R console to create .pdf slides (notice that a name "tutorial1.html" should refer to the name of the set of slides you are creating).
