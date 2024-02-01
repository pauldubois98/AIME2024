# Phantom Reinforcement Learning Dosimetrist Agent
## A submission to the ICCR2024 conference

This repository contains the source code and the LaTex template for the submission to the ICCR2024 conference.
Our goal is to present a reinforcement learning agent that can be used to optimize the treatment plan of a patient.
The agent is trained and tested on phantoms patients.

**Submission rules**
- Submission only in pdf format
- two column format
- font size 11 for main text, abstract and references can use font size 9
- Maximum 4 A4 pages including everything (strict limit)
- In addition: prepare short abstract (max 150 words) to be entered in online submission system! This will only be used for the program. It will **not** be used for the review process **nor** for the final proceedings.

## How to build the LaTex template

You can manually build the latex template by executing
```
pdflatex iccr2024_template.tex
bibtex   iccr2024_template.aux
pdflatex iccr2024_template.tex
pdflatex iccr2024_template.tex
```

Alternatively, simply run the build chain including pdflatex and bibtex of your favorite LaTex editor or use [latexmk](https://mg.readthedocs.io/latexmk.html).
