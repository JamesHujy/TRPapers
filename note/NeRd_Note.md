## ReClor: A Reading Comprehension Dataset Requiring Logical Reasoning

### General View
A reader followed by a programmer.

The reader is an encoder, e.g. BERT. 

The programmer takes the output of the reader as input, decodes the programmer. In paper, they use LSTM with attention and self-attention.

### Training with weak supervision

not very clear about these two tricks

* Huge search space ---> data augmentation.
* filter the spurious answer ----> Hard EM

### 