
### Model Implemenatation

In this project we will train the model with MNIST dataset and to achieve 99.40% accuracy (not once but for consistently  4 epoch ) within 5-15 epoch without using fully connected layer.

And to achieve this we have a constraint of not using more than 10K parameters.

Our Model is Based on Convolution Neural Network ( CNN ) .

So we had divided the problems into multiple parts and then tried to train the model by correcting features step by step sequentially(mentioned below) till the target accuracy is achieved.
 - Building Lighter Model.
 - Batch Normalization.
 - Use Dropout in proper place.
 - Global Average Pooling.
 - Image Augmentation techniques.
 - Learning Rate(LR) Scheduler.

Result :
  We had successfully achieve the target accuracy of 99.40% .
  1. Parameters            : 9736
  2. Best Train Accuracy   : 98.09%
  3. Best Test Accuracy    : 99.45%

And we have maintained  the model to not "OVERFIT".
We have achieved better accuracy by doing slightly image rotation and step size of LR to reduce after 5 step.
( We obtained this by hit and trail and upon rigorous analysing ).


Well "__Excess of Anything is not Bad. It is Worst ....!!__". Same thing happened,but it is worth for someone, who is in a learning phase.

But tried multiple ways to achieve the target.
While in the middle of doing so , we have learnt may things.
- Choose the batch size wisely.
- To achieve high accuracy , first epoch should give good accuracy.
- Never apply Relu , Dropout , Batch Normalization at the last convolution Layer.




### Author Info
- Email : [jagatabhay@gmail.com](jagatabhay@gmail.com)
- [![Linkedin](https://github.com/jagatabhay/TSAI/blob/master/logo.png)](https://www.linkedin.com/in/jagatnandan-prasad-240042129/)
- [![Github](https://github.com/jagatabhay/TSAI/blob/master/S13/githublogo.png)](https://github.com/jagatabhay)
