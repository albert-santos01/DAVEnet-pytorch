This markdown is meant to be the notes for reproducing the results of Harwarh et al. 2018
# run.py
## Argspars
- --exp_dir is the place to dump all the experiments
- Considering data-train and data-val, these are the paths for the json
 all the rest of values can be by default

--exp_dir will save all the models
- They use ``8 workers``...

# traintest.py
- they don't calculate the val_loss: [Done]
    - We can introduce it at validate[Done]
    - 