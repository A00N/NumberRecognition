## Week 2

This week went by experiementing with different upgrades to network code. Changed quadratic cost function to CrossEntropy cost function. Before I achieved 95% training data accuracy, while now achieving 97%. 
However, validation data accuracy is still, for some reason about 10%. I am lookkin to fix the issue by experiementing with hyperparameters values. The issue might have something to do with overfitting.

Currently the  algorithm is able to recognize some images made in Aseprite that are 28x28. The amount of hidden layers, epochs, batch sizes etc needs still some testing to find optimal values.

### Tasks done this week:
- Changed cost function to CrossEntropy
- Created more tests
- Added pylint
