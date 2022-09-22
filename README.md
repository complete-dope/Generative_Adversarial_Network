# Generative_Adversarial_Network
This is a replica of paper "DCGAN" paper
I have replicated the dcgan paper "https://arxiv.org/abs/1511.06434".

## Generative Models
'What does "generative" mean in the name "Generative Adversarial Network"? "Generative" describes a class of statistical models that contrasts with discriminative models.

Informally:

Generative models can generate new data instances.
Discriminative models discriminate between different kinds of data instances.
A generative model could generate new photos of animals that look like real animals, while a discriminative model could tell a dog from a cat. GANs are just one kind of generative model.

More formally, given a set of data instances X and a set of labels Y:

Generative models capture the joint probability p(X, Y), or just p(X) if there are no labels.
Discriminative models capture the conditional probability p(Y | X).
A generative model includes the distribution of the data itself, and tells you how likely a given example is. For example, models that predict the next word in a sequence are typically generative models (usually much simpler than GANs) because they can assign a probability to a sequence of words.

A discriminative model ignores the question of whether a given instance is likely, and just tells you how likely a label is to apply to the instance.

Note that this is a very general definition. There are many kinds of generative model. GANs are just one kind of generative model.'
