# al_project

## Objective

The objective of this project is to support research in the field of Active Learning by conducting a detailed study on the effectiveness of some of its techniques for collecting and classifying information about an on-going event. This project aims to examine how these techniques can be used to improve the data collection process during a dynamic and rapidly changing situation, to achieve an accurate and useful information system.


![data-pipeline](https://imgur.com/cCeLhxJ.png)


In particular, the Coreset approach is studied in two different approaches:

* Farthest-First

This algorithm selects a randomly labeled data point and it searches for the furthest unlabelled data point from it and it is labelled and added to the list. This process is repeated until it has reached the budget.


![Farthest-First](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExN2liNjU5ZDRmNWhpbnN2aHdwdGJkMXFuMzJmZnlrY3NzYjlzMDlwYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/GdMt9KYd8TfEgsZTut/giphy.gif)

* Minimax

This algorithm’s focus is on the unlabelled elements, since in every iteration it searches for the data point that is the furthest from its nearest labeled element, and it is later labeled and added to the set with the others.

![Minimax](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmFlNXY2d3F4NGNmbDU4dWluZm5kZzB4ZWsxeHU2ZmJ0emc3eTNubyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/FyerejItnyFOhEga8b/giphy.gif)

## Repository information

The development of the models can be seen in the [al_project](https://github.com/Crippius/al_project/blob/main/al_project.ipynb) notebook, while the results are analyzed in the [al_analysis](https://github.com/Crippius/al_project/blob/main/al_analysis.ipynb) one.

Inside the [report](https://github.com/Crippius/al_project/blob/main/report.pdf), an in-depth explanation of the project is found; for a more visual description, there is also a [presentation](https://github.com/Crippius/al_project/blob/main/presentation.pptx) that can be looked at.

Finally, in the models folder, the neural networks are saved inside each .h5 file, with some additional information about the parameters used and metrics performance, they can be further analyzed with the Model class inside the al_analysis folder.

N.B. the datasets used for training can't be shared.