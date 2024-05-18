# SNIRP
## Structured NeuroImaging-Intensive Research Program

The SNIRP program is designed to give students an opportunity to develop novel neuroimaging research projects, or to work on an existing project with a mentor. The SNIRP program is now in its seventh year. The program started with 2 students, and has now expanded to about two dozen students per 10-week summer session. Students from high school levels and up may participate. Support has been offered from many sources, and about 18 students are expected to receive stipends to participate this summer.

This Git repository was created to help SNIRP students use reproducible science tools through code versioning. By tracking each version of the code used, and getting into the habit of inserting helpful comments in scripts and code, it is much easier to "retrace your steps," or the steps other scientists have taken.

By the way, feel free to interact with students and offer assistance. I'm sure they will learn from the Git community, too.

## The very first "Goal Project" was to create R scripts to clean and "tidy" data within the ADNIMERGE dataset so that:

1. All data files have the same number of rows (each RID and VISCODE match)
2. Data of the same "type" are listed in separate tables (e.g., clinical, imaging, demographic, dictionaries/information, etc.)
3. The class of each variable matches the data represented in the columns
4. etc....

__The final result of this work was intended to be an Rmd file that allows other users to retrace each step__

## Moving on to the current year, there are 3 student teams working on separate projects:

1.  Stroke Outcome Optimization Project (SOOP)
2.  Alzheimer's Disease Neuroimaging Initiative Traumatic Brain Injury (ADNITBI)
3.  Parkinson's Progression Marker Initiative (PPMI) -- Repository Analysis of Atypical Parkinson's (RAAP)

## We are using a "Big Memory" instance on Jetstream2 configured by Steffen Bollmann to run Neurodesk on JupyterLab via Kubernetes

__Many thanks to Steffen for his contributions to this effort, and to many others who have contributed to this work over the past 7 years!__
