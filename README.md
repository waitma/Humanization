# Humanization
A humanization method for antibody and nanobody.


# Model Structure


# Antibody 
## Training
`python scripts/train.py`
## Sampling
`python scripts/sample_v3.py`
## Evaluation
`python scripts/tmp_eval.py`
and
`python scripts/humab25_eval.py`
for different test dataset.

# Nanobody
## Training
`python scripts/nanotrain.py`
## Fine-tuning
`python scripts/nanofinetune.py`
## Sampling
`python scripts/nanosample.py`  
if you wanna design for a sequence, you can exec:  
`python scripts/nano_sample_for_fa.py`
## Evaluation
`python scripts/nano_eval.py`
