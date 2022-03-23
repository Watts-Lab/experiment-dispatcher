# experiment-dispatcher
A tool for picking and launching the next experiment

Prototype here:
https://colab.research.google.com/drive/1vUTxWLq_ijZkN_aNHWoyBZgOiedVvNJt#scrollTo=uDOmZeK2CDUr&uniqifier=1

## Uses Case 1: Mapping with adaptive binary choice


## Use Case 2: Common-sense claims
In the common sense project, there are a set of claims (Items/interventions $I_i$) and individuals will answer questions such as "Do you think this is true?", "Do you think other people think it's true?" and "Do you think it's common sense?". We want to as a whole estimate beta distributions for each of these questions given the nature of the question, and also the nature of the individual answering the question.

Individuals will come into the experiment platform, and be shown a series of these questions



# Overall Architecture
## "Fast" selector
This runs either in the browser or on the server-side node, and is probably implemented as an npm package. It uses an api to request a 
