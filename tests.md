### Test 1

Finding the optimal epoch to use

To do this I will start with an epoch of 4, and note down accuracy, incrementing by 2 until it is clear that the model is overfitting the data.

I will be using the accuracy on the test set, not the validation set to get the true accuracy.

- 4 epoch accuracy: %13.30
- 6 epoch accuracy: %18.02
- 8 epoch accuracy: %25.16
- 10 epoch accuracy: %28.85
- 12 epoch accuracy: %29.97
- 14 epoch accuracy: %30.48
- 16 epoch accuracy: %33.21
- 18 epoch accuracy: %30.53
- 20 epoch accuracy: %31.52
- 22 epoch accuracy: %31.63 

outcome, it looks like 16 epochs is the sweet spot, after that it just varies around lower accuracies.