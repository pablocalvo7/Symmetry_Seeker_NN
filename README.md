# Finding discrete symmetry groups via Machine Learning

Pablo Calvo-Barlés, $^{1, 2}$ Sergio G. Rodrigo, $^{1, 3}$ Eduardo Sánchez-Burillo, $^{4}$ and Luis Martín-Moreno $^{1, 2}$

+ $^{1}$ Instituto de Nanociencia y Materiales de Aragón (INMA), CSIC-Universidad de Zaragoza, 50009 Zaragoza, Spain
+ $^{2}$ Departamento de Física de la Materia Condensada, Universidad de Zaragoza, 50009 Zaragoza, Spain
+ $^{3}$ Departamento de Física Aplicada, Universidad de Zaragoza, 50009 Zaragoza, Spain
+ $^{4}$ PredictLand S.L., 50001 Zaragoza, Spain

[arXiv:2307.13457](https://arxiv.org/abs/2307.13457)

# Abstract

+ This Jupyter notebook provides an implementation of the **Symmetry Seeker Neural Network (SSNN)** model based on Tensorflow-Keras. The NN model has been designed to identify discrete symmetries. With this code you will be able to:
 - Determine the matrix representation of all elements within a system's symmetry group by solving a supervised learning task.
 - Solve inverse design problems that entail symmetry-related, multivalued solutions.
+ In this notebook, we illustrate the functionality of the SSNN model by solving an inverse problem and unveiling their symmetries. The task involves determining the value of $z$ (a complex number) based on the given functional relationship $w=z^3$, where $w$ is also a complex number. With the SSNN method will get the group of symmetries for this transformation.
