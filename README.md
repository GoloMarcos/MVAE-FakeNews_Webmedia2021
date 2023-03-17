# Learning Textual Representations from Multiple Modalities to Detect Fake News Through One-Class Learning
- Marcos Gôlo (ICMC/USP) | marcosgolo@usp.br
- Mariana Caravanti (ICMC/USP) | mariana.caravanti@usp.br
- Rafael Rossi (UFMS) | rafael.g.rossi@ufms.br
- Solange Rezende (ICMC/USP) | solange@icmc.usp.br
- Bruno Nogueira (FACOM/UFMS) | bruno@facom.ufms.br
- Ricardo Marcacini (ICMC/USP) | ricardo.marcacini@icmc.usp.br

# Citing:

If you use any part of this code in your research, please cite it using the following BibTex entry
```latex
@inproceedings{ref:Golo2021,
  title={Learning textual representations from multiple modalities to detect fake news through one-class learning},
  author={G{\^o}lo, Marcos and Caravanti, Mariana and Rossi, Rafael and Rezende, Solange and Nogueira, Bruno and Marcacini, Ricardo},
  booktitle={Proceedings of the Brazilian Symposium on Multimedia and the Web},
  pages={197--204},
  year={2021}
}
```

# Abstract
Fake news can rapidly spread through internet users. Approaches proposed in the literature for content classification usually learn models considering textual and contextual features from real and fake news to minimize the spread of disinformation. One of the prominent approaches to detect fake news is One-Class Learning (OCL), as it minimizes the data labeling effort, requiring only the labeling of fake news documents. The performance of these algorithms depends on the structured representation of the documents used in the learning process. Generally, a textual-based unimodal representation is used, such as bag-of-words or representations based on linguistic categories. We propose MVAE-FakeNews, a multimodal representation method to detect fake news in OCL. The proposed approach uses a Multimodal Variational Autoencoder, learns a new representation from the combination of two modalities considered promising for fake news detection: text embeddings and topic information. In the experiments, we used three datasets considering Portuguese and English languages. Results show that the MVAE-FakeNews obtained a better F1-Score for the class of interest, outperforming another nine methods in ten of twelve evaluated scenarios. MVAE-FakeNews presented a better average ranking and statistical difference from other representation models. The proposed method proved to be promising to represent the texts in the OCL scenario to detect fake news.

# Datasets
We use the FKTC (FakeNews text collections) library https://github.com/GoloMarcos/FKTC that has information about the datasets

# MVAE-FakeNews
![Proposal](/images/MVAE-FK.png)

# Results
![Results](/images/results.png)

# Critical Diference
![Results](/images/nemeny.png)

# TSNE on FCN
![TSNE](/images/FCN-TSNE.png)








