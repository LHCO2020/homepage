## Welcome to the home of the LHC Olympics 2020!

Despite an impressive and extensive effort by the LHC collaborations, there is currently no convincing evidence for new particles produced in high-energy collisions.  At the same time, there has been a growing interest in machine learning techniques to enhance potential signals using all of the available information.  

In the spirit of the first LHC Olympics (circa 2005-2006) [1st, 2nd, 3rd, 4th], we are organizing the 2020 LHC Olympics.  Our goal is to ensure that the LHC search program is sufficiently well-rounded to capture "all" rare and complex signals.  The final state for this Olympics will be more focused (generic multijet events) but the observable phase space and potential BSM parameter space(s) are large: all hadrons in the event can be used for learning (be it "cuts", supervised machine learning, or unsupervised machine learning).

We provide two types of files (from this Zenodo [link](https://doi.org/10.5281/zenodo.3547721)):

"Monte Carlo Simulation Background": This is a simulated sample that does not have signal. Be warned that both the physics and the detector modeling for this simulation may not exactly reflect the “Data”.
"Data": These are the LHCO 2020 black boxes. These samples may contain some new signal(s). We will release three black boxes during this challenge.  The first one was released on November 19. The second one was released on December 4. 
Both the "Simulation" and "Data" have the following event selection: at least one anti-kT R = 1.0 jet with pseudorapidity |η| < 2.5 and transverse momentum pT > 1.2 TeV.   For each event, we provide a list of all hadrons (pT, η, φ, pT, η, φ, ...) zero-padded up to 700 hadrons.

What you should report:

A p-value associated with the dataset having no new particles (null hypothesis).
As complete a description of the new physics as possible. For example: the masses and decay modes of all new particles (and uncertainties on those parameters).
How many signal events (+uncertainty) are in the dataset (before any selection criteria).
Partial submissions in only a subset of the categories are welcome! You can submit your findings at this Google form. The deadline for the challenge will be Sunday, January 12, 2020 at 5pm Eastern US Time. Results will be presented in a dedicated session at the ML4Jets2020 conference. 

Outcomes will be judged based on the optimality of the p-values and the accuracy of the new physics characterization. In particular the "best" p-value will be the lowest reported p-value that is above the fully optimal p-value (as determined with a fully supervised deep learning classifier).  For accuracy, we will use the # of sigmas |(your answer - right answer) / your uncertainty| from the right answer wherever applicable.

For setting up, developing, and validating your methods, we provide background events and a benchmark signal model.  You can download these from this page.  To help get you started, we have also prepared simple python scripts to read in the data and do some basic processing.   The page describing the R&D phase of the challenge can be found here.

We strongly encourage you to publish your original research methods using these datasets. Anyone who participates will be part of a summary paper to be prepared following the workshop.

Please do not hesitate to ask questions: we will use the ML4Jets slack channel to discuss technical questions related to this challenge. 

Good luck!

You can use the [editor on GitHub](https://github.com/LHC-Olympics-2020/homepage/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/LHC-Olympics-2020/homepage/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
