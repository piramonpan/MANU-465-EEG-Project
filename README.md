# MANU-465-EEG-Project

# Motivation
A long-standing and perpetuated myth is that doing a creative task activates a different hemisphere of the brain than doing an analytical task. This myth has been debunked and proven that both activities use both hemispheres of the brain. It is, however, still of interest to know if different types of brain waves are produced when each activity is undertaken, as this provides knowledge and a better understanding of cognitive processing.

This information could then be applied in educational settings, such as a better understanding of students’ learning styles. Further, this could be taken to enhance focus and creativity, in that by understanding the brain waves produced by a person doing either a creative or analytical task, measures could be taken to recreate or tailor an environment to either help a person hone in on a mathematics problem or promote a creative environment.

Using machine learning (ML) algorithms and artificial intelligence (AI), this project will aim to explore the differences in brain waves produced between a person doing a creative task (drawing) and the brain waves produced when a person performs a more analytical task (mathematics).

# Objective
In this project, the main objective is to implement a machine-learning classification model to distinguish whether someone is currently performing a creative or analytical task from brainwave data. Previous research suggests that different brain waves are linked to these activities. Analytical tasks are associated with activated gamma waves, while creativity tasks are associated with alpha waves. The goal of this project is to determine if machine learning can be used to prove if this pattern is observed and further find underlying connections that might have gone unnoticed.

Another goal is to determine if task enjoyment is linked to any brain wave markers. For example, what brainwave pattern emerges when someone finds a mathematical problem easier while they might find drawing? This can be achieved by surveying the participants first to see which activity they prefer (drawing/mathematics) and classifying their brain waves based on that (Like/Dislike).

# Material, Methodology, and Schedule

## Materials
The materials that will be used in this project are:
- **The MUSE 2 Headband EEG Monitor**: This is an important device used to collect brainwave data. The MUSE 2 is an electroencephalogram (EEG) capable of measuring the electrical activity of the brain. From this device, we can collect different types of brainwaves such as delta, theta, alpha, beta, and gamma. The Mind Monitor app will be used to record the data from the headband.
- **Stationery for drawing**: Pen, pencil, colored pencils, and paper.
- **Past Waterloo Math Contests**: Waterloo Math Contests are online, multiple-choice tests that aim to introduce mathematical and computer science concepts to secondary students. Rather than complex theories, the test itself focuses on applying logic and critical thinking to solve the problems. Therefore, making it a great tool for representing analytical tasks.

## Proposed Methodology

### Data Collection
To complete this project, each member will collect data from 7-10 people, such as their friends and family. For each participant, we will record their age, gender, and their preference (whether they prefer creative or analytical tasks). These are supplementary information that may be later explored.

Then, the MUSE 2 headband will be used to collect data. Each participant will receive:
- **3 creative drawing prompts** and
- **3 Waterloo Math problems**, with **5 minutes** given for each individual problem.

This brings the total time to **30 minutes** and 6 datasets from each participant.

Furthermore, to ensure that external variables are controlled, data collection should take place in a quiet location, with everyone receiving the same sets of drawing prompts and math problems. Each person should also be given the same amount of time.

With this specification, we will have an estimate of **150 datasets**, which is sufficient for this project level.

### Data Processing
Afterward, using the collected data, we can train different machine learning models to classify creative and analytical tasks. This step will involve:
1. **Pre-processing data**: Eliminating outliers, removing irrelevant features, scaling, etc.
2. **Signal processing techniques**: May be explored to smooth out the data.
3. **Exploratory Data Analysis (EDA)**: To identify patterns in the data.

After EDA, different classification models will be trained, optimized, and compared to find the best result. Specific potential ML algorithms will be explored in the next section.
