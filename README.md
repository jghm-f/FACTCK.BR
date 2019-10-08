# FACTCK.BR

A dataset to study Fake News in Portuguese, presenting a supposedly false News along with their respective fact check and classification.

The data is collected from the [ClaimReview](https://www.schema.org/ClaimReview), a structured data schema used by fact check agencies to share their results in search engines, enabling data collect in real time.

## Dataset Description

The FACTCK.BR corpus is a dataset in the form of a 9 column table with 1309 lines, each one corresponding to a claim.

The corpus is storage in a text file with tabs separating the columns, encoded in UTF-8. 

### Fact Check Agencies
- [Aos Fatos](https://aosfatos.org/)
- [Lupa](https://piaui.folha.uol.com.br/lupa/)
- [Truco](https://apublica.org/tag/truco/)


### Corpus Attributes

| Columns             | Description               |
|---------------------|---------------------------|
| URL                 | Check article web address |
| Author              | Initiative id.            |
| datePublished       | Check publication date    |
| claimReviewed       | Claim analyzed            |
| reviewBody          | Check text                |
| Title               | Title of the article      |
| ratingValue         | Numerical classification  |
| bestRating          | Lenght of the scale       |
| alternativeName     | Text label                |

### Dataset Update Script

The dataset can be updated using a Python script. The script get new articles from the RSS feed of the fact check agencies and update the dataset locally.

## Reference

This work will be published at WebMedia '19, Brazilian Symposium on Multimedia and the Web, October 29 - November 1, 2019, Rio de Janeiro , Brazil.
If you are using FACTCK.BR, please cite our paper.
https://doi.org/10.1145/3323503.3361698

## Licence
The dataset are licensed under the MIT License by the author; you may not use FACTCK.BR except in compliance with the License. A copy of the License is included in the project, see the file LICENSE.txt.
The paper Publication rights licensed to ACM.

## Acknowledgments

This study was financed in part by the Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brasil (CAPES) - Finance Code 001.


