# Temporally Layered Architecture

This repository is the official implementation of [Optimizing Attention and Cognitive  Control Costs Using Temporally-Layered Architectures](https://doi.org/10.1162/neco_a_01718). 
<p align="center">
    <img src="Images/TLA Architecture.jpg" alt="Temporally Layered Architecture" width="500"/>
</p>
<!-- 📋  Optional: include a graphic explaining your approach/main result, bibtex entry, link to demos, blog posts and tutorials -->

## Citation

The paper can be cited with the following bibtex entry:

```
@article{10.1162/neco_a_01718,
    author = {Patel, Devdhar and Sejnowski, Terrence and Siegelmann, Hava},
    title = "{Optimizing Attention and Cognitive Control Costs Using Temporally Layered Architectures}",
    journal = {Neural Computation},
    pages = {1-30},
    year = {2024},
    month = {10},
    issn = {0899-7667},
    doi = {10.1162/neco_a_01718},
    url = {https://doi.org/10.1162/neco\_a\_01718},
    eprint = {https://direct.mit.edu/neco/article-pdf/doi/10.1162/neco\_a\_01718/2474695/neco\_a\_01718.pdf},
}
```


## Requirements

To install requirements:

```setup
pip install -r requirements.txt
```

>📋  Describe how to set up the environment, e.g. pip/conda/docker commands, download datasets, etc...

## Training

To train the model(s) in the paper, run this command:

```train
python train.py --input-data <path_to_data> --alpha 10 --beta 20
```

>📋  Describe how to train the models, with example commands on how to train the models in your paper, including the full training procedure and appropriate hyperparameters.

## Evaluation

To evaluate my model on ImageNet, run:

```eval
python eval.py --model-file mymodel.pth --benchmark imagenet
```

>📋  Describe how to evaluate the trained models on benchmarks reported in the paper, give commands that produce the results (section below).

## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth) trained on ImageNet using parameters x,y,z. 

>📋  Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.

## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

>📋  Pick a licence and describe how to contribute to your code repository. 