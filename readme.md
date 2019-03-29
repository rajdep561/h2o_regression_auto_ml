## Regression

For the AutoML regression demo, we use the  [Combined Cycle Power Plant](http://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant)  dataset. The goal here is to predict the energy output (in megawatts), given the temperature, ambient pressure, relative humidity and exhaust vacuum values. In this demo, you will use H2O's AutoML to outperform the  [state-of-the-art results](https://www.sciencedirect.com/science/article/pii/S0142061514000908)on this task.

In this tutorial, you will:

-   Split the data into train/test sets.
-   Specify a training frame and leaderboard (test) frame.
-   Specify the response variable.
-   Run AutoML where stopping is based on max runtime, using training frame (80%).
-   Run AutoML where stopping is based on max runtime, using original frame (100%).
-   View leaderboard (based on test set metrics).
-   Compare the leaderboards of the two AutoML runs.
-   Predict using the AutoML leader model.
-   Compute performance of the AutoML leader model on a test set.
