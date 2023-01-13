This log book keeps track of the experiments and activities on this project.

## Key
- #nbs - Notebook path location. Unless mentioned otherwise, it is located at: `nbs/_research`.
- #idea - An idea I want to search later on.
- #report - wandb report of some experiments I ran.

## Logs

<hr>


## Friday 14th Jan 23
- Continued doing some experiments on a sliced down version of the dataset. I picked the 10 most common `genus` classes and did some experiments and fit models to predict the 10 classes.
- #report : https://wandb.ai/jimmiemunyi/the-snake-project-cls/reports/Baseline-10-Classes--VmlldzozMzI4ODI5
- I will now create a small primitive demo to showcase what I have so far and then iterate on it and improve it.

### Thur 13th Jan 23
- Continued with EDA. Extrapolated these fields from the dataset: `species`. 
- #nbs --> `00_EDA.ipynb
- #idea: Scrap Data from Wikipedia?
- Created a public `wandb` project to track the image classification: https://wandb.ai/jimmiemunyi/the-snake-project-cls
- Started training small models with a fraction of the data to see how models perform. Predicting only a single target: `genus`. Since I picked a fraction of the data, I will randomly select the training and the validation. I will resume using the ones provided once I start training on a significant number of images on the dataset. Nbs --> `01_tiny_baselines.ipynb`
- Created a library with nbdev where I will place commonly used functions and variables called `tsp`. Location same with the github location for the project.



### Wed 12th Jan 23
- Did some initial EDA to see what the data is like. Also started brainstorming on how to structure the classification, i.e. which fields to predict from the images. Current contendars are: `genus`, `species` and `continent`. I will then use that info to predict whether the snake is venomous or not, which is the goal of this project.
- Also started doing some reading around snakes to gain some domain knowledge. Currently reading [The Book of Snakes](https://www.amazon.com/Book-Snakes-Life-Size-Hundred-Species/dp/022645939X) by Mark O'shea.


### Tue 11th Jan 23
- Downloaded the datset from: https://www.aicrowd.com/challenges/snakeclef2021-snake-species-identification-challenge
- Brainstormed on what the goal of the project should be. Used the [DriveTrain](https://www.oreilly.com/radar/drivetrain-approach-data-products/) approach. Here is the drivetrain info for the classification part of the project:

**Objective**: To determine whether a snake is venomous or not.

**Levers**: We can use image classification to identify the genus, species and country of the snake, then use that information to infer whether the snake is venomous or not. 

**Data**: AI Crowd Species Identification Project.
