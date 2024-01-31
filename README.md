# Introduction

This tutorial & exercise, developed in 2024, is designed for trainees interested in joining the lab directed by Dr. Suzanne Leal in [Center for Statistical Genetics at Columbia University](https://www.neurology.columbia.edu/research/research-centers-and-programs/center-statistical-genetics#:~:text=We%20are%20a%20group%20of,statistical%20genetics%20and%20genetic%20epidemiology.). It reflects our expectation on your computing skills in R, Python, Linux shell commands, and hopefully your ability in learning new tools in bioinformatics and related fields. By completing these exercise you will first set up the computational environment on your computer, then perform some data analysis of small scale using some test data. However, it is important to point out that after joining the lab, most of the research requires access to high performance computing cluster in Linux, on large-scale data such UKBiobank and All of Us data.

You may generally write in one or two languages we mentioned above, but we believe that the learning curve for things you are not that familiar with (but required in this exercise) is reasonable. You are encouraged to search online for learning new tools, and even to ask ChatGPT if necessary, as the ability to search for answers and solve the questions itself is also required in our lab. However, if there is a blocker as you go through the material, please do not hesitate to contact us (rd2972@cumc.columbia.edu).

## Task 1: Unix command shell and command tools

We assume you are comfortable with command-line interface (on Linux or Mac). In this task you are going to work with git from command shell, set up the computing environment, and install basic softwares and packages needed for data analysis of Tasks 2 and 3.

### Git

Most of our work will be saved and shared on github in public or private repositories. If you have not used git in the past, please follow the [instructions here for a 5 minutes git tutorial](https://wanggroup.org/orientation/5m-git).

As the next step please [fork](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo) this repository, add your name to the Markdown file named `hello.md`, commit it to github with a customized commit message, eg, "Add my name and github handle", and [create a pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/about-pull-requests) so we can see your update and incorporate it to the repository.

### Markdown and shell

Generate a markdown file (using any text editor you prefer), and start with a section about any research project that you have been working on, with at least two subsections, some links, *Italic text* and **bold text** (to highlight some important content) and at least one table or figure. The content of the report would not be considered in the evaluation, but it is important to make sure it is well structured and formatted, and written in English clearly.

In the same markdown file, the second section would be your answers to the questions about shell commands under `shell_commands/questions.md`. If the answer is a code, put it in the code chunk in markdown.

## Task 2: Jupyter notebook and R/Python

Please [install jupyter notebook](https://jupyter.org/install) on your own computer, and then download both notebooks under folder `notebook/`. Add a cell at the beginning of each notebook and put your name there.


## Task 3: Statistical genetics

The first notebook, `notebook/finemapping.ipynb` is an exercise with the `susieR` package in R. This is somewhat advanced material for those who has a background in statistical genetics.

Please add another section in the notebook after where you put your name, and make the section title "Summary of the SuSiE method". Then take a read at [this paper](https://academic.oup.com/jrsssb/article/82/5/1273/7056114) before you run this notebook to know some basic concepts that we might mention in the notebook. Please then summarise the SuSiE method in a paragraph and describe what it does. 





Please follow the instructions in it and run all the cells. When you run the cells one by one, you can take some notes and put them into a new section at the end of the notebook, where you can share with us any problem you have and how you solve it (for example, by some QA page on [Stack Overflow](https://stackoverflow.com) or simply get the answer from ChatGPT. 



Please follow the instructions and complete the genetic fine-mapping exercise `notebook/finemapping.ipynb`. This is somewhat advanced material for those who has a background in statistical genetics. 






## Task 3: Jupyter notebook and python

Now please download the notebook `notebook/data_analysis.ipynb` and also add a cell at the beginning with your name.

Please follow the instructions in it and run all the cells. Feel free to share anything at the end of the notebook as well.

