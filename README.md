# tafar
Human action recognition plays a pivotal role in various
real-world applications, including surveillance systems,
robotics, and occupant monitoring in the car interior.
With such a diverse range of domains, the demand
for generalization becomes increasingly crucial. In this
work, we propose a cross-attention-based encoder-decoder
approach for unsupervised 3D skeleton-based action recognition.
Specifically, our model takes a skeleton sequence
as input for the encoder and further applies masking and
noise to the original sequence for the decoder. By training
the model to reconstruct the original skeleton sequence,
it simultaneously learns to capture the underlying patterns
of actions. Extensive experiments on NTU and NW-UCLA
datasets demonstrate the state-of-the-art performance as
well as the impressive generalizability of our proposed approach.
Moreover, our experiments reveal that our approach
is capable of generating conditioned skeleton sequences,
offering the potential to enhance small datasets
or generate samples of under-represented classes in imbalanced
datasets.

# Principle
![image](https://github.com/davidjlerch/tafar/assets/61084566/d86afd4e-c9dc-40ef-99bc-5dc44f5416f3)

# Architecture
![image](https://github.com/davidjlerch/tafar/assets/61084566/0d10f6c3-ff03-42c6-a809-761b2ff01eff)

The paper is accepted at WACV 2024 (https://wacv2024.thecvf.com/)
