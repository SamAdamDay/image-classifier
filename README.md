Image Classification
====================

In this repo, I work to build an image classifier, starting first with the CIFAR-10 dataset [[Kri]](#1). I follow Andrej Karpathy's [Recipe for Training Neural Networks](https://karpathy.github.io/2019/04/25/recipe/). This is a long and thorough process designed to avoid many common pitfalls encountered while training neural nets.


The Recipe
----------

1. **Become one with the data**. Exploring the data, looking for patterns. I do this in [data-exploration.ipynb](data-exploration.ipynb).
    - I look at 300 examples, 30 from each class.
    - I also look at these with greatly reduced resolution, to get a sense of the main colours involved.
    - I take colour histograms across each class.


References
----------

<a id="1">[Kri]</a>
Alex Krizhevsky (2009),
Learning Multiple Layers of Features from Tiny Images. [https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf](https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf)