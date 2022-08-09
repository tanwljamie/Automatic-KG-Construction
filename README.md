# Automatic-KG-Construction

This is the code implementation for my bachelor's research thesis, Automatic Construction Knowledge Graph Construction for Fine-grained Image Classification. There are two notebooks, the first notebook is for the KG construction, and the second notebook is used to evaluate the KG in a zero-shot learning image classification task. There are two parts to the second notebook. The first part is used to create the knowledge graph embeddings, which is generated using Ampligraph [1]. The second part uses these knowledge graph embeddings in the Embarrassingly Simple Approach to Zero-shot Learning Model [2] and the implementation from https://github.com/chichilicious/embarrassingly-simple-zero-shot-learning. 

In this research, we used the Caltech-UCSD 200-2011 Bird DataSet (CUB). Additionally, we contributed a second dataset of bird descriptions that correspond to the classes in the CUB dataset. We also used two domain-specific ontologies, Uberon[3] and Pato[4]. 

The datasets can be downloaded from this link. 

CUB Dataset, Image Features and Proposed Split: https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/research/zero-shot-learning/zero-shot-learning-the-good-the-bad-and-the-ugly/

Text Descriptions Dataset: https://drive.google.com/drive/folders/1p7lGDhOrplwWR38CknxCviLtWG80QPEu?usp=sharing

References

[1] L. Costabello, S. Pai, C. L. Van, R. McGrath, N. McCarthy, and P. Tabacof,
“AmpliGraph: a Library for Representation Learning on Knowledge Graphs,” Mar. 2019.
[Online]. Available: https://doi.org/10.5281/zenodo.2595043

[2] B. Romera-Paredes and P. H. S. Torr, “An embarrassingly simple approach to zero-shot
learning,” in Proceedings of the 32nd International Conference on International Conference
on Machine Learning - Volume 37, ser. ICML’15. JMLR.org, 2015, p. 2152–2161.

[3] Uberon, an integrative multi-species anatomy ontology,” Genome Biology, vol. 13, no. 1,
p. R5, 2012. [Online]. Available: https://doi.org/10.1186/gb-2012-13-1-r5

[4] G. V. Gkoutos, P. N. Schofield, and R. Hoehndorf, “The anatomy of phenotype ontologies:
principles, properties and applications,” Computer, Electrical and Mathematical Sciences
and Engineering Division. [Online]. Available: https://academic.oup.com/bib/article-
abstract/19/5/1008/3108819

