# CmpdEnzymPred

The repository includes codes for reproducing work in paper _Enzyme Activity Prediction of Sequence Variants onNovel Substrates using Improved Substrate Encodings and Convolutional Pooling_, (https://proceedings.mlr.press/v165/xu22a.html). In this work, a new compound protein interaction prediction pipeline is proposed with performance tested on datasets obtained from Machine learning modeling of family wide enzyme-substrate specificity screens (arXiv:2109.03900v1, by S. Goldman and C. W. Coley). The pipeline is based on sequence embeddings generated by protein language models and count encodings of molecule fingerprints.

The figure below shows the prediction model's architechture,

<p align="center">
  <img width="600"  src="https://github.com/LMSE/CmpdEnzymPred/blob/main/Architecture_2.png">
</p>


We were able to show a substantial improvements with the new pipeline as we tested the predictions on multiple enzyme-substrate-activity datasets (i.e. aminotransferase, kinase, halogenase, phosphatase, etc. ) as shown in the table below.

<p align="center">
  <img width="600"  src="https://user-images.githubusercontent.com/47986787/167858775-a68e8706-4f7f-4aee-a368-f48f64727ea2.png">
</p>
