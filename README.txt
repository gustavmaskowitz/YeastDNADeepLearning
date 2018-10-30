Code from "Deep Learning Of The Regulatory Grammar Of Yeast 5' Untranslated Regions from 500,000 Random Sequences"

We hope that by including some of the code in our analysis it will help others repeat and build on our results. Hopefully this will be useful, and feel free to contact me if you have any questions/concerns/suggestions. -Ben

To get going, just place the Data, Jupyter_notebooks and Results folders into the same folder. If you start with Notebook_1 everything should just work (including the creation of subsequent folders). If you'd like to use our model, the .hdf5 and .json files in the /Results/Random_UTR_CNN.Hyperparam.Opt/ folder will get you there. If you'd like to just go through a specific notebook without running the others, let me know and I can provide the required files (bgroves "at" uw "dot" edu, or benjaminbgroves "at" gmail "dot" com).



Requirements:

We performed the model training on either a server with dedicated GPUs here at UW, or one of the machine learning/neural network instances on Amazon Web Services. I would recommend going this route, as using a laptop/desktop CPU may make you want to bang your head against the desk. A normal laptop should be fine for most of the other analysis.


Versions of Python packages used:

Keras:		1.2.2
Theano:		0.9.0
Hyperopt:	0.1
Scipy:		0.19.0
Numpy:		1.12.1
Pandas:		0.19.2
Seaborn:	0.8