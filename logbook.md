This log book keeps track of the experiments and activities on this project.

## Logs

<hr>



### Thur 13th Jan 23




### Wed 12th Jan 23
- Did some initial EDA to see what the data is like. Also started brainstorming on how to structure the classification, i.e. which fields to predict from the images. Current contendars are: `genus`, `species` and `country`. I will then use that info to predict whether the snake is venomous or not, which is the goal of this project.
- Also started doing some reading around snakes to gain some domain knowledge. Currently reading [The Book of Snakes](https://www.amazon.com/Book-Snakes-Life-Size-Hundred-Species/dp/022645939X) by Mark O'shea.


### Tue 11th Jan 23
- Downloaded the datset from: https://www.aicrowd.com/challenges/snakeclef2021-snake-species-identification-challenge
- Brainstormed on what the goal of the project should be. Used the [DriveTrain](https://www.oreilly.com/radar/drivetrain-approach-data-products/) approach. Here is the drivetrain info for the classification part of the project:

**Objective**: To determine whether a snake is venomous or not.

**Levers**: We can use image classification to identify the genus, species and country of the snake, then use that information to infer whether the snake is venomous or not. 

**Data**: AI Crowd Species Identification Project.
