# Week 2 reading, notes, links and assignments

This week we are doing a recap of linear algebra, and in particular, seeing how to implement all that stuff in `PyTorch` on Colab.
 
### Agenda

1. Vector spaces
2. Inner products, norms, distances
3. Eigenvalues and vectors
4. Rank
5. Tensors
6. Eigenvalues, condition numbers, ...
7. The Johnson-Lindenstrauss lemma and the curse of dimensionality
8. Limitations of linearity

### Pre-reading

The reading list may look long, but it is (mostly) a recap of material you covered earlier in your degree so I expect you will get through it really quickly. I've broken it down roughly by topic, but note there are many overlaps in the material.

Please make sure to read it before the Week 2's workshop.

Feel free to find other materials (but let me know so I can include them for others). 

Also get yourself a free account on [openai.com](openai.com), then try out
  
  + ChatGPT
  + Dall-E (Note: you can try out a free version of Dall-E at [Dall-E Mini](https://huggingface.co/spaces/dalle-mini/dalle-mini))
   
**Motivation:** I don't expect you to understand everything in these papers, but I would like you to understand a little bit about why we do what follows. And by the end of the course, you can hopefully make sense of these.

  + https://arxiv.org/pdf/1801.05894.pdf
  + https://royalsocietypublishing.org/doi/pdf/10.1098/rsta.2015.0203
  + [shannon_1948.pdf](shannon_1948.pdf)
 
**Vector spaces, inner products, norms, distances, orthogonality, basis**
    
  + https://ai.stanford.edu/~gwthomas/notes/vector-spaces-linear-maps.pdf
  + https://users.math.msu.edu/users/gnagy/teaching/05-fall/Math20F/w9-F.pdf
  + https://ai.stanford.edu/~gwthomas/notes/norms-inner-products.pdf
  + [Vector_spaces.pdf](Vector_spaces.pdf) 
  + [Norms.pdf](Norms.pdf)
  + [glossary.pdf](glossary.pdf)
  
**Linear transformations, projection**
    
  + https://users.math.msu.edu/users/gnagy/teaching/05-fall/Math20F/w3-F.pdf
  
**Rank**    
   
  + https://nhigham.com/2021/02/23/matrix-rank-relations/ 
  + [Rank.pdf](Rank.pdf)

**Tensors**

  + [Tensors.pdf](Tensors.pdf)

**Eigenvalues and vectors**

  + https://lpsa.swarthmore.edu/MtrxVibe/EigMat/MatrixEigen.html 
  + https://www.adelaide.edu.au/mathslearning/ua/media/120/evalue-magic-tricks-handout.pdf
  + [Eigenvalues\_and\_vectors.pdf](Eigenvalues_and_vectors.pdf)

**Matrix condition number**
    
  + https://nhigham.com/2019/01/23/who-invented-the-matrix-condition-number/ 
  + https://www.sciencedirect.com/science/article/pii/0024379593000669?via%3Dihub 

**The Johnson-Lindenstrauss lemma and the curse of dimensionality**

  + https://builtin.com/data-science/curse-dimensionality
  + [Johnson-Lindenstrauss.pdf](Johnson-Lindenstrauss.pdf)

We could put a lot more here in an intro to the math we will use: e.g.,

+ Vector calculus
+ Probability and stats
+ Complex numbers and spaces
+ Information Theory

There is a worksheet -- [Assignment 0](assignment_0.pdf) -- for you to test your knnowledge. It is not assessed, but might be helpful to make sure you get the foundational work.

### Code to do in the workshop

The code for the workshop is in the GitHub: 
https://github.com/AdelaideUniversityMathSciences/MathsForAI/Code/

There are a few bits to play with and these become the assignments:

+ [basic_tensor.ipynb](../Code/basic_tensor.ipynb)
+ [timing.ipynb](../Code/timing.ipynb)
+ [Einstein.ipynb](../Code/Einstein.ipynb)
+ [Gaussian_Orthogonal_Ensemble.ipynb](../Code/Gaussian_Orthogonal_Ensemble.ipynb)
+ [nearest_neighbor.ipynb](../Code/nearest_neighbor.ipynb)
+ [non-linear.ipynb](../Code/non-linear.ipynb)

### Assignments

There is a self-assessment exercise setup for you to test your understanding on paper. But the main exercises for this course will be implemented in code through Colab. All of the notebooks can be found in the GitHub. Import them to colab and complete the instructions in the workbook.

1. Basic tensor calculations described in `basic_tensor.ipynb`
2. Reproduce (using colab and PyTorch) the contour plot of the different $L_p$ vector norms.
2. Test out the Python/Colab code-timing mechanism: `timing.ipynb` 
3. Do the Einstein summation notation worksheet: `Einstein.ipynb`
4. Use similar code to the GOE code `Gaussian_Orthogonal_Ensemble.ipynb` to generate the Gaussian Unitary Ensemble (you'll have to do a little independent research to find out what that is) and look at the distributional properties of its eigenvalues.
5. Make sure you understand the nearest-neighbours code `nearest_neighbor.ipynb` (we will be using this later in the course, so better to learn it now) by doing colab notebook assignment_nearest_neighbor.ipynb.

Hand up completed worksheets to MyUni.






