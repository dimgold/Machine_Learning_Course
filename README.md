# Machine_Learning_Course
[Machine learning course at Tel-Aviv University, autumn 2016](http://ml-intro-2016.wikidot.com/course-schedule)

Machine learning algorithms implementation using Python, addressing MNIST dataset (predict handwritten digits):

Exercises:
- Ex1: kNN
- Ex2: SVM (using SGD), perceptron
- Ex3: Multiclass SVM, Kernels
- Ex4: AdaBoost, PCA


MNIST dataset can be downloaded using this [link](http://yann.lecun.com/exdb/mnist/) or by using ``sklearn`` command:

    from sklearn.datasets.mldata import fetch_mldata
    mnist = fetch_mldata('MNIST original')
