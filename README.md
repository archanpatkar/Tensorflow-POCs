## Tensorflow Proof of Concept


### Tensorflow

TensorFlow is an open-source software library for dataflow programming across a range of tasks. 
It is a symbolic math library, and also used for machine learning applications such as neural networks.

It is used for both research and production at Google.

### Introduction

#### `Tensorflow is a libary in which there are 4 Fundamental Abstractions`
 
 1. Nodes
 
 2. Operations
 
 3. Tensors
 
 4. Links / Flows


### Start

> Before you start with the POCs please see the Requirements and Installation

* ### [Requirements](https://github.com/archanpatkar/tensorflow/wiki/Requirements)

* ### [Installation](https://github.com/archanpatkar/tensorflow/wiki/Installation)


### `Simple Code to Start With`

``` 
import tensorflow as tf

node1 = tf.constant(1);
print(node1);
node2 = tf.constant(3);
print(node2);
node3 = node1 + node2;
print(node3);

with tf.Session() as session:
    output = session.run(node3);
    print(output);
```

<script src="https://gist.github.com/archanpatkar/830d7b309f8c22ac52ef21ab7e3dadad.js"></script>

### Support

archanpatkar@gmail.com /
archan@rajeshpatkar.com
