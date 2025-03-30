# Chapter 1 - Machine learning landscape

## Lexicon
1) *Label*: result/class. Can be compared to $y$
2) *Feature*: what $x$ is to $y$
3) *Model rot/data drift*: When the world evolves but not the model. See Batch/Online learning

## Notes

* What is machine learning: 
    * A program learns from experience **E**, doing a task **T** measured by **P**, if **P** gets better over time doing **T** from **E**
* Why use machine learning:
    * Great at doing adaptative program, things that requires updating reasonning a lot (filters, analyses, etc..)
    * Getting insights
    * Evaluate fine tuning

### Supervision types
* Supervised learning:
  * Classification
  * Regression
* Unsupervised learning:
  * Clustering
  * Visualisation
* Semi-supervised:
  * Google photo face labeling
* Self-supervised learning
  * from fully unlabeled set to fully labeled: remove parts of a photo set and regenerate it.
* Reinforcement learning:
  * Agent that loses points when making error and gain points when it avoids them
  
### Continuous/ on the fly learning
* Batch learning : Learn from data in batches, no continuous learning. Will most likely create model rot/data drift
* Online learning : adapt itself from continuous data integration

### Comparison/detection

