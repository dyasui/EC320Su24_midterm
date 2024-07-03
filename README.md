# Summer Econometrics Take-home Midterm Exam

This github repository contains the materials you will need to complete the 
take-home portion of the midterm exam.

## Instructions

First, download the repository by downloading the zip file from the green "Code" button. 
Unzip/extract the zip file.
It is a good idea to do this in a directory dedicated to this class.
An example of a file path to save this zip file in would be:
`~/Documents/classes/EC320S24/problem_sets/`.
Once unzipped, open the `EC320S24_PS04.Rproj` which will open RStudio.

Navigate to the Files tab in the bottom right panel of RStudio. 
You should see the following files:

```
.
├── EC320Su24_midterm.Rproj
├── R
│   └── midterm.Rmd
└── README.md

2 directories, 3 files
```

You will edit the file `midterm.rmd` with `R` code inside of code blocks,
and your explanation of your code and responses to the questions in text.
Once you have satisfactorily completed your answers, 
you will use the 'Knit' button in Rstudio (or the hotkey `Shift Cmd/Ctrl K`)
to compile your work as an html document.
You should find the resulting `midterm.html` document in the same folder 
(assuming you opened the project using the `EC320Su24_midterm.Rproj` file).

Please review the module 'Rmarkdown' on Canvas for an explanation of how to
write and compile R markdown documents.

### Data

The data from this problem set are a sample of district level data from the state of Massachusetts in 1998.
It can be loaded into memory through installing the `AER` package from CRAN
(i.e., `install.packages("AER")`).
By default, the Rmd will do this for you. 
After downloading, simply knit the document (cmd/ctrl + shift + k) and make sure 
everything looks okay.

The Massachusetts data are district-wide averages for public elementary school districts in 1998.
The data analyzed here are the overall total score, which is the sum of the scores on the English, Math, and Science portions of the test.
Data on the student-teacher ratio, the percent of students receiving a subsidized lunch and on the percent of students still learning english are averages for each elementary school district for the 1997–1998 school year and were obtained from the Massachusetts department of education.
Data on average district income are from the 1990 US Census.

