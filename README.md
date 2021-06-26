# Model_Pruning
We got to know about pruning from " Proving the lottery ticket hypothesis: Pruning is all you need " authord by Eran Malach, Gilad Yehudai, Shai Shalev-Schwartz, Ohad Shamir. Pruning techniques can reduce the parameters counts of trained network by 90%. With this technique storage requirements can be decressed as well as the computational performance can be improved along with having the same accuracy as a fully trained model. But this has some downsides as well. For example produced sparse architecture are different to train from start and these networks can not be trained from scratch. There is an package called neuralmagic can help us apply the pruning on our model. If this technique is implemented appropriately then we believe that we can reach our goals.

Our goals are:
    1. Network with reduced parameters.
    2. Has application in multiple fields.
    3. Certain algorithm for different type of datasets.
