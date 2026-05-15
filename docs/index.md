# TensorFlow

[TensorFlow](https://www.tensorflow.org/) is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of [tools](https://www.tensorflow.org/resources/tools), [libraries](https://www.tensorflow.org/resources/libraries-extensions), and [community](https://www.tensorflow.org/community) resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML-powered applications.

TensorFlow was originally developed by researchers and engineers working within the Machine Intelligence team at Google Brain to conduct research in machine learning and neural networks. However, the framework is versatile enough to be used in other areas as well.

TensorFlow provides stable [Python](https://www.tensorflow.org/api_docs/python) and [C++](https://www.tensorflow.org/api_docs/cc) APIs, as well as a non-guaranteed backward compatible API for [other languages](https://www.tensorflow.org/api_docs).

## Install

See the [TensorFlow install guide](https://www.tensorflow.org/install) for the [pip package](https://www.tensorflow.org/install/pip), to [enable GPU support](https://www.tensorflow.org/install/gpu), use a [Docker container](https://www.tensorflow.org/install/docker), and [build from source](https://www.tensorflow.org/install/source).

To install the current release, which includes support for [CUDA-enabled GPU cards](https://www.tensorflow.org/install/gpu) (Ubuntu and Windows):

    $ pip install tensorflow

A smaller CPU-only package is also available:

    $ pip install tensorflow-cpu

### Try your first TensorFlow program

```python
import tensorflow as tf
tf.add(1, 2).numpy()
# 3
hello = tf.constant('Hello, TensorFlow!')
hello.numpy()
# b'Hello, TensorFlow!'
```

For more examples, see the [TensorFlow Tutorials](https://www.tensorflow.org/tutorials/).

## Contribution guidelines

Review the upstream [Contribution Guidelines](https://github.com/tensorflow/tensorflow/blob/master/CONTRIBUTING.md). This project adheres to TensorFlow's [Code of Conduct](https://github.com/tensorflow/tensorflow/blob/master/CODE_OF_CONDUCT.md).

## Resources

- [TensorFlow.org](https://www.tensorflow.org)
- [TensorFlow Tutorials](https://www.tensorflow.org/tutorials/)
- [TensorFlow Official Models](https://github.com/tensorflow/models/tree/master/official)
- [TensorFlow Blog](https://blog.tensorflow.org)
- [TensorBoard Visualization Toolkit](https://github.com/tensorflow/tensorboard)

## License

[Apache License 2.0](https://github.com/tensorflow/tensorflow/blob/master/LICENSE)
