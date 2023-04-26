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

### Test 2 

Finding the optimal learning rate

Start with: 0.01 (default)

Accuracy didnt go above 2% so we shall decrease the LR to 0.001 
0.001 plateaued around 24-25% accuracy so we shall decrease to 0.0001 and see how it is
0.0001 plateaued around 34-35% accuracy so we will decrease to 0.00001 and see how it is
0.00001 got around 37-38% accuracy so we will decrease to 0.000001 and see how it is
0.000001 plateaued around 33% so the optimal learning rate is between 0.00001 and 0.000001
