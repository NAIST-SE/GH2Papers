# GitHub Repositories with Links to Academic Papers: Open Access, Traceability, and Evolution

## Abstract

Traceability between published scientific breakthroughs and their implementation is essential, especially in the case of open-source scientific software which implements bleeding-edge science in its code. However, aligning the link between GitHub repositories and academic papers can prove difficult, and the impact created by publishing both academic papers and their associated software remains unknown. This paper investigates the role of academic paper references contained in these repositories. We conduct a large-scale study of 20 thousand GitHub repositories to establish prevalence of references to academic papers. We use a mixed-methods approach to identify Open Access (OA), traceability and evolutionary aspects of the links. Although referencing a paper is not typical, we find that a vast majority of referenced academic papers are OA. These repositories tend to be affiliated with academic communities. More than half of the papers do not link back to any repository. A case study of referenced arXiv paper shows that most of these papers are high-impact, influential, and do align with academia, being referenced by repositories written in different programming languages. From a software evolution standpoint, we find very few changes of papers being referenced and links to them.

## Qualitative coding
  Our coding results of 377 links to GitHub repositories for RQ1 (Prevalence and Open Access), RQ2 (Relationship and Traceability), and RQ3 (Evolution) are available [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7gkxqJpzsa4T2ZuZg-VfAvD9U4r-XbpmwdlkK3k_RZ5Jc8bhgLK6I6xHj_KSTHTZaoJg-SqcE2yPj/pubhtml).
  
 **coding guide for RQ1.2**
 - *open access* - the referenced academic paper is available online including authors' preprint.
 - *not open access* - the referenced academic paper is not OA, and authors do not provide their preprint.
 
 **coding guide for RQ2.1**
- *deep learning* - the repository is specifically focused on the deep neural network architecture.
- *computer vision* - the repository implements algorithms that solve computer vision tasks such as analyzing images or videos for object recognition and tracking.
- *natural language processing* - the repository is concerned with the processing and/or understanding of human natural languages (e.g., English).
- *other machine learning* - the repository is related to machine learning, but does not fit any of the previous three codes.
- *quantum* - the repository is related to quantum computing.
- *robotics* - the repository is related to robotics, but not from a machine learning or computer vision aspect.
- *networks* - the repository is related to analyzing the properties of network structures and their applications.
- *sensors* - the repository is related to sensor technologies.
- *other* - anything that does not fit any of the previous codes.

 **coding guide for RQ2.2**
- *university* - the owners are affiliated with universities.
- *industry* - the owners are affiliated with companies.
- *both* - the owners are affiliated with universities and companies at the time we investigated.
- *unknow* - we cannot determine the affiliation from the profile of the owner of the GitHub repository.

 **coding guide for RQ2.3**
- *official* - the owner of the repository is one of the authors of the referenced academic paper.
- *fork of official* - the owner of the repository is not one of the authors of the referenced academic paper, and the target repository is forked from the official repository that belongs to one of the authors of the referenced paper.
- *independent unofficial* - the owner of the repository is not one of the authors of the referenced academic paper, and there is no obvious relationship between the target repository and the official repository of the paper, if it exists.
- *miscellaneous* - the owner of the repository is not one of the authors of the referenced academic paper, and the repository was created for other purposes (e.g., education).

 **coding guide for RQ2.4**
- *link to official* - the referenced paper has a link to the official repository, which is different from the targeted GitHub repository.
- *link to the same repository* - the referenced paper has a link to the same GitHub repository.
- *404* - the referenced paper has a link to a software repository, but the repository cannot be accessed.
- *no link* - the referenced paper does not have a link to a software repository.

 **coding guide for RQ3.1**
- *no update* - the referenced academic paper did not get updated after being referenced.
- *update* - the referenced academic paper was updated after being referenced.

 **coding guide for RQ3.2**
- *different paper* - the README.md file referenced a different academic paper before. 
- *changes to metadata* - the meta data of the paper was changed, e.g., from 'to appear' to the publication information.
- *link changes* - a link to the referenced academic paper was updated, e.g., from a pdf stored on GitHub to an arXiv or DOI link.
- *no update* - the reference had not evolved.

 
