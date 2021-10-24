# AdversarialNLP
RL based adversarial attack on RoBERTA toxicity classifier.

This attack is performed with a Reinforce algorithm in a black-box setting. It takes about 60k queries to the model to converge. The success rate on Jigsaw benchmark is 0.89.

The algorithm generates an injection which being inserted in the text "detoxifies" it, even if it contains offencive lexic.

The proposed algorithm is suitable for any deep text classifier.

### Requirements:
* python 3.7
* torch 1.10
* transformers 4.6.1


### How to use:
Run all cells in Attack_on_RoBerta.ipynb notebook.

## Example
![Adversarial Detoxification Example](https://github.com/razzant/AdversarialNLP/blob/main/example.png)
