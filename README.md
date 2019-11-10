
# CapsNet
## CapsNet for MNIST Kannada dataset

Reference Paper - *[KANNADA-MNIST: A NEW HANDWRITTEN DIGITS DATASET FOR THE KANNADA LANGUAGE](https://arxiv.org/pdf/1908.01242.pdf)*

There are two datasets mentioned in the paper - MNIST-10k-Test dataset and the Kannada-MNIST-Test dataset.

For the Kannada MNIST dataset, with 60, 000 − 10, 000 train-test split, CNNs achieved 97.13% top-1 accuracy.
**While the CapsNet achieves 98% accuracy.**

The pre-trained CNN achieved 76.2% top-1 accuracy on the dig-10k dataset. **While the CapsNet achieves 80.03% for the same.**

## CapsNet for Traffic Signal classification

Final test acc: 94.81

## CIFAR dataset

Batch Size 10

N_epochs =5

acc = 66.53%

## To Do

- [ ] Stack more convolutional layers before capsule layers.

- [ ] Increase the size of the capsule layers (more capsules, larger capsules etc.). Note that it may take a lot of time.

- [x] Play with number of routing iterations in forward pass.

- [ ] Play with kernel size of convolutions in the first layer.

- [ ] Play with kernel size of capsules in the second layer.

- [x] Try different variants of original implementation's loss function (change m+, m-, lambda, get rid of square etc.).

- [ ] Try different loss functions (make it pure Hinge or pure MSE, maybe even cross-entropy!).

- [ ] Try different weights for reconstruction loss.

- [ ] Data Preprocessing and Shuffle data. (See Kaggle Kernel of Kannada MNIST)



