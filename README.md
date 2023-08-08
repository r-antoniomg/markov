# Markov chain text generator

This Jupyter notebook goes step by step through the process of creating a text generating application.
This notebook is intended for beginners without a strong coding background.
As such, most of the explanation has to do with basic aspects of the code.
The notebook doesn't go into much detail about all the code, especially the more complex functions that make up the text generator.

The code was adapted from from Luciano (StrikingLoo's) [ASOIAF-Markov repository](https://github.com/StrikingLoo/ASOIAF-Markov).
He also wrote an article called ['Markov Chains: How to Train Text Generation to Write Like George R. R. Martin'](https://www.kdnuggets.com/2019/11/markov-chains-train-text-generation.html), where he goes into more detail around what Markov chains are and how they work in the context of his text generator.

Another great resource for learning about different methods of machine learning (including Markov chains) is the book [You look like a thing and I love you](https://www.janelleshane.com/book-you-look-like-a-thing) by Janelle Shane.
The book is a good introduction to Artificial Intelligence full of humour and meant for a broad audience (without assumptions about previous coding skills).

This Markov chain model takes input in the form of .txt files, and uses prompts to generate new text.