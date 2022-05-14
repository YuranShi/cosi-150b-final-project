COSI 150B Final Project Report
==
This repository was adapted and modified from the code
from [A Deep Multimodal Approach for Cold-start Music Recommendation](https://dl.acm.org/doi/10.1145/3125486.3125492).

## Dataset

The dataset can be downloaded
from [this link]([https://doi.org/10.5281/zenodo.831348](https://doi.org/10.5281/zenodo.831348)).

Untar it and point DATA_DIR in common.py to the full path of the dlrs-data/ folder

## Run Experiments

Then you can run the experiments by calling `run_experiments.py`, for example:
For the audio model:

    python run_experiments.py rec_multi audio-emb

For multimodal recommendation:

    python run_experiments.py rec_multi a-sem-emb audio-emb
