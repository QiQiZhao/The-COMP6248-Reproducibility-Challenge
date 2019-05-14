# The COMP6248 Reproducibility Challenge

This work is a part of COMP6248 Reproducibility Challenge. Our goal is replicating the 
experiments described in the conference submission by \cite{opaper}: \textit{Interpretable Counting for Visual 
Question Anwersing.} This paper propose a new method to count in visual question answering, which increases accuracy.
In addition, authors built a subset named How-Many-QA to filter questions which are not suitable to the method.
In the details of reproduction, we have some places that are different from the original paper,
including decrease the size of dataset, the structure of language model and the types of counting models.

# Run
Firstly, download all of the .py files and put them in the root directory, then run **Perpare Data.ipynb**. When it is ready, run **Training IRLC.ipynb** and **Training SoftCount.ipynb.**
I write them on colab.

# Acknowledge


Github repository \url{https://github.com/sanyam5/irlc-vqa-counting} and \url{https://github.com/hengyuan-hu/bottom-up-attention-vqa} 
greatly helped our work. Their codes are useful to reproduce the paper.
