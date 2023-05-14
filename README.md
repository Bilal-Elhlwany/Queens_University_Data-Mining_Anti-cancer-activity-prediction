# Queens_University_Data-Mining_Anti-cancer-activity-prediction
Anti-cancer activity prediction

![VectorVsGraph](https://github.com/Bilal-Elhlwany/Queens_University_Data-Mining_Anti-cancer-activity-prediction/assets/100938358/2e6bf1a6-1967-4b9f-bcd1-27d176965c80)
https://www.kaggle.com/competitions/cisc873-dm-w23-a6/overview

This competition is a bioassay task for anticancer activity prediction, where each chemical compound is represented as a graph, with atoms representing nodes and bonds as edges. A chemical compound is positive against non-small cell lung cancer, or negative otherwise. Up to this point, you have learned various tricks and mechanisms to be used for building neural networks/tuning models.

**✔️ Meme competition:**

Include/find a MEME that you liked related to data science/data mining/machine learning

**✔️ Understand the template:**

Put detailed comment on each line of the code to show your understanding of the template (you can find it at the Data tab). Then describe: What is the experimental protocol used and how was it carried out? How did we tune hyper-parameters in the template? What is the search space and what is the criteria to determine good/bad hyper-parameters?

**✔️ Problem Formulation:**

Define the problem. What is the input? What is the output? What data mining function is required? What could be the challenges? What is the impact? What is an ideal solution?

**✔️ Model Tuning and Documentation:**

Now based on the template, try to improve the model's performance on the public leaderboard by following the data science life-cycle for tuning. You can try different features, different hyperparameters/configurations of the model, and even a different model. For each trial, document the reason why you want to make the certain change and the expected outcome, before running the code. Record the observed performance and your thought on it. Recall that we have a DS life-cycle and we should know what to do when underfit/overfit. The final result is not important, but the process is. Documentation of your thought process is very important, since most people forgot why they test certain model/hyperparameter after they got the result (it takes time). It also helps a lot when you got stuck. You can organize the notebook by listing

thoughts and observations for trial 0, plan for trial 1

code for trial 1

thoughts and observations for trial 1, plan for trial 2

code for trial 2

…
You have to tune at least 10 times. All the tried solutions should be different (e.g. different feature sets/different preprocessing). The tried solutions should cover at least:

GCN aggregation mechanisms: Tune at least three aggregation mechanisms (aka message_passing mechanisms) used in the graph convolution layer. Explain your understanding (based on the documentation/paper) of the mechanisms you chose.

Up-sampling: adjust the training data preparation/generation part to up-sample the positive class samples (very unbalanced dataset)

**✔️ Answer the questions below (briefly):**

**🌈Based on the provided template, describe the format of the input file (sdf file).**

**🌈What are the input tensors to the neural network model (their meaning, not just symbol)? What is each of their dims and their meaning (e.g. batch_size)?**

**🌈For each dim of gnn_out, what does it symbolize? For each dim of avg, what does it symbolize?**

**🌈What is the difference between segment_mean and tf.reduce_mean? For each dim of pred, what does it symbolize?**

**🌈What is the motivation/theory/idea to use multiple gcn layers comparing to just one? How many layers were used in the template?**
