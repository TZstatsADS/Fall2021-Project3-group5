# Project: Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Fall 2021

+ Team Group 5
+ Team members
	+ Ayati-Ghaffari, Arya (aa4663)
	+ Cook, Kerry (ksc2138)
	+ Sun, Jialiang (js5951)
	+ Zhang, Qian (qz2416)
	+ Zou, Yixuan (yz4004)

+ Project summary: In this project, we created a model I and model II. For model I, we used a basic CNN structure: two 2D convolutional layers, a max pooling layer, a flatten layer, a dense layer and the classficication layer. For model II, we trained a label cleaning network that follows a similar architecture as the paper suggests. We used a pre-trained CNN (VGG16) for the base network, and tried to match the rest of the architecture to the paper. The test accuracy on clean labels of model I and model II is around 51% and 58%, respectively.
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) 

Kerry Cook (ksc2138) and Qian Zhang (qz2416): the major contributors of project 3. Kerry and Qian designed the model together. They tried different feature extractors, predictive models, optimizers, learning rate strategies and methods of reduceing overfitting (all of them are mentioned in the appendix) and found the best model structure and values of hyperparameters for model I and II. Kerry and Qian wrote all the codes, comments and explanations in the pdf.

Jialiang Sun managed to provide an idea with CNN for model 1 but compared with the final/main part,  it is denied and begins to follow the main document. Meantime, do a lot of researches, structure the presentation ideas and give the final presentation.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
