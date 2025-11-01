# ML/Net Leaderboard Reproduction and Possible Extension of nPrint OS Detection.

## Project Participants

| First Name | Last Name | cnet ID | Project Role |
|------------|-----------|---------|--------------|
| Benjamin   | Chaplin   | bac     | everything   |

## Project Description

One paragraph description of your project. Summarize the following:
* Problem statement
* Why it is important problem
* How it relates to the theme of the course (e.g., what is the intersection
  with networking and ML?).
* Any related work you are aware of
* What is the goal? Research? Tech transfer? Reproducing a result?

### Project Summary
The problem is to identify/classify the operating system that sent each 100
packet sample in the dataset. OS detection is important for a variety of
reasons, but it ultimately depends on the scenario. It can be useful for network
administrators to identify unauthorized or vulnerable systems on their networks
(we can see if systems are out of date or if we have a mandate for a certain OS
we can see if it is being followed). It also helps with network management by
providing visibility into the variety of systems accessing network resources
which can be a step towards anomaly detection. Ultimately, the goal of the
project is to reproduce the leaderboard score.

### Machine learning: What models do you expect to try?
I plan to try out classifier models. Because this is my first ML class, I don’t
really know what models are out there. I’m not quite sure which one’s to try.
For assignment 1, I used MLPClassifier, and that seemed to work pretty well, so
I might try that again. Of course, I’ll tune hyperparameters so I get even better
metrics.

### Evaluation: How will you evaluate your models?
On the leaderboard website, it says that the metric to optimize my model is
balanced accuracy, so that is what I will use to evaluate my models.
Additionally, I will use the metrics that we have learned about in class like
f1, confusion matrix, and ROC/AUC.

### Learning objective: What are you expecting to learn from your project?
I expect to learn how to apply ML to detect different operating systems, and I
hopefully will learn how to optimize such a model to improve my results. I want
to at least reproduce the leaderboard result.

### Related Work
The [nPrint paper](https://arxiv.org/abs/2008.02695) speaks about passive OS
fingerprinting.

There is also a recent [paper](https://arxiv.org/abs/2502.09084) from 2025 that
speaks about apply tabular transformer achitectures for OS fingerprinting.

## Data

The data that I am using in this project is on the 
[website](https://nprint.github.io/benchmarks/os_detection/nprint_os_detection.html).
The data was originally from the CICIDS 2017 dataset. The website explains that
“​​The traffic was split first by the source IP address of each packet, and then
split into 100 packet samples (sequentially)”

## Deliverables

I plan to have a clean Jupyter notebook that contains all of my analysis. In
addition to this, I plan to have a Sphinx formatted project report that
includes an introduction, dataset description, methodology, results,
discussion, and conclusion.

