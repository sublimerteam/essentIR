
### Abstract
The literature on coronaviruses counts more than 300000 publications.
Finding relevant papers concerning arbitrary queries is essential to the discovery of new potentially helpful knowledge. 
Current best information retrieval solutions use deep learning approaches and need supervised train sets with labeled data, namely to know a priori the queries and the relevant papers for each of them.
Creating such labeled datasets is time-expensive and requires prominent experts' efforts, resources
insufficiently available under a pandemic time pressure. 
We present a new self-supervised solution, called SUBLIMER, 
that does not require labels to learn to search on corpora of scientific papers for most relevant against arbitrary queries.
SUBLIMER is a novel light-weight IR engine trained on the 
unsupervised COVID-19 Open Research Dataset (CORD19),
using deep metric learning. 
The core point of our self-supervised approach is that it uses no labels but exploits the bibliography citations from papers to create a latent space where spatial proximity is a metric of semantic similarity; for this reason, it can also be applied to other domains of papers corpora. 
SUBLIMER reaches equivalent results to the state-of-the-art on CORD19, which, differently from our approach, require both labeled datasets and several trainable parameters that is an order of magnitude higher than ours.


### WebApp

[SUBLIMER Web Application](http://137.204.107.153:50000/) 



### Support or Contact

The team is composed by: 
* Dr. Lorenzo Valgimigli (Ph.D. Student ) (lorenzo.valgimigli@unibo.it)
* Prof. Gianluca Moro (Ph.D.) (gianluca.moro@unibo.it)

_Department of Computer Science and Engineering, University of Bologna, Campus of Cesena._
