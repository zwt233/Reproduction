# GMLP: Building Scalable and Flexible Graph Neural Networks with Feature-Message Passing.

This repository is the official implementation of GMLP. 

## Requirements

To install requirements:

```setup
pip install -r requirement.txt --user
```


## Training

To train the model(s) in the paper:

>run the ipynb notebook file "test.ipynb" under  directory ‘examples’

>> - input:  the graph file in dir "data"
>>- output:  the test accuracy

Even with 50 propagation steps, GMLP still keeps a good performance on PunMed!

## Results

1. Transductive settings:

<img src="transductive.png" width="100%" height="100%">

2. Inductive settings:

<img src="inductive.png" width="40%" height="40%">

3. Efficiency:

<img src="performance_time.png" width="80%" height="80%">

4. Training scalability:

<img src="scalability.png" width="100%" height="100%">

5. Model scalability:

<img src="depth.png" width="80%" height="80%">
