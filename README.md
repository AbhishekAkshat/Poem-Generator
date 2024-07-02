# Poem Generator

Data Collection:

First, we needed to collect the poems that would be the source for our project. To do this we created a web-scraper in Python, that gathers the poems of a specific writer from "mypoeticside.com" and saves them to a ‘.csv’ file.

Data Pre-processing:

We created a function that takes our previously created .csv file and splits the poems into verses, based on a regular expression that we choose. Then, we also erased and replaced some undesired characters from the verses (colons, for example) to make the resulting poem look more well-connected and cohesive. We then saved the verses in a new ‘.csv’ file.
The step-by-step process and explanation of data collection and its pre-processing are in the Python Juptyer Notebook file ‘dataCollection_and_preProcessing.ipynb’.

Implementation:

The step-by-step implementation and explanation of our poem generator are in the Python Juptyer Notebook file ‘implementation_PoemGenerator.ipynb’.
