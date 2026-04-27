---
# Do not edit the text between these lines!
layout: default
---

# COMP 110 Course Analysis from Surveys

<!-- This is a comment. Below, you'll see code for inserting an image. To make this image appear, update <custom-path>. To add an image, save it inside the imgs folder of this repository. -->
<img src="EX09-Repository-2-TG/static/imgs/logo.png" alt="Image of Comp110 rainbow logo. "  width="500"/>

## Hypothesis

The core hypothesis is as follows: The course should include more smaller, structured activities practicing coding outside of the larger EX assignments.

## Analysis

In order to test this hypothesis, I primarily used three data sets: programming_effective, difficulty, and understanding. The first step was to load the datasets, convert them into column-based tables, and combine them. Then, I selected the most relevant columns outlined above and counted how students rated progrmaming assignments to understand perceived effectiveness, and I made a histogram to display this. 

<img src="EX09-Repository-2-TG/static/imgs/program_effective count" alt="Image of Comp110 rainbow logo. "  width="500"/>

Then, I made a scatterplot comparing course difficulty with perceived effectiveness of progrmaming assignments. 

<img src="EX09-Repository-2-TG/static/imgs/difficulty" alt="Image of Comp110 rainbow logo. "  width="500"/>

Afterwards, I made a box plot comparing student understanding with programming assignment effectiveness. 

<img src="EX09-Repository-2-TG/static/imgs/understanding" alt="Image of Comp110 rainbow logo. "  width="500"/>

## Conclusion

The data are not definitively conclusive, but they lean towards refuting my hypothesis, indicating that current programming assignments might be effective for learning. The first chart plotting the count of survey responses for each program_effective rating is the most conclusive, as it shows a consistent uphill trend. As the ratings for programming assignment effectiveness progress from 1-7, the number of students who voted for that rating increases signficantly. 

However, this should not be taken as a conclusive takeaway. The dataset simply asks students to place their agreeement with the following statement on a scale: "Programming assignments are effective in helping student learn the topics of the course." Even if they are effective, we have no data for what could make the course even more effective. Furthermore, one of the goals of having smaller assignments outside of EX programming ones was to reduce overwhelm, and we also have no data to analyze this. The next two the graphs plotted programming effectiveness with understanding and difficulty, and these had no observable trend. As a result, the overall analysis is relatively inconclusive for this particular hypothesis. 

I believe the change of having smaller programming assignments throughout would be more effective because students could practice the specific concepts or tasks, like defining head() functions, before implementing them in a broader assignment where they have to do several other tasks as well. A potential negative impact could be that this creates more homework for students, and that could lead to lower grades or even increase overwhelm, which is what we hope to avoid. As a result, this change would need to occur in conjunction with others, such as reducing LS assignments or spending less time on memory diagrams and more on active practice. 
