# LosCalis at PoliticEs 2022: Political Author Profiling using BETO and MarIA

## PoliticES 2022

Political ideology is a psychographic trait that can be used to understand individual and social behaviour, including moral and ethical values as well as inherent attitudes, appraisals, biases, and prejudices (Verhulst et al., 2012). The relationship between personality traits and political ideology was demonstrated in Fatke (2017). The author gathered data from 21 countries and found a correlation between political ideology and the big five personality traits. For instance, he found that conscientiousness was strongly correlated with the right wing, whereas openness to experience and agreeability were notably more correlated to the left wing. Moreover, our political ideology has a great influence in our daily lives. For example, Baumgaertner et al. (2018) found a correlation between political ideology and the attitude of citizens to vaccination campaigns of infectious diseases.

[PoliticES 2022](https://codalab.lisn.upsaclay.fr/competitions/1948) is a shared task which aims to extract political ideology information from texts. For this, an author profiling task is proposed. It is focused on the identification of the gender, the profession, and the political spectrum from a binary and multi-class perspective.

## Challenges 
The challenges involved are:

1. Extracting political ideology from a text collection. To the best of our knowledge, this is the first Spanish shared task focused on this.

2. Multi-class classification. The author profiling task should be addressed from a binary and multi-class perspective with four different classes.

## Proposed Solution

Here a deep learning architecture for the identification of gender, profession and political ideology in social media is proposed. The architecture is based on pre-trained Spanish BERT and RoBERTa. The proposed system participated in PoliticEs and obtained a micro-F1 of 90.28% achieving first place in the shared task.

## Data Extension
During our participation in PoliticEs 2022, it was decided to extend the original dataset, collecting tweets from Spanish politicians and journalists posted between January 2021 and February 2022. The result can be found [here](https://github.com/ssantamaria94/PoliticES2022/tree/main/data)

## Results

Classification Task | Macro F1-score|
--- | --- 
Gender | 0.902868
Profession | 0.944327
Ideology Binary | 0.961623
Ideology Multiclass | 0.800229
--- | --- 
Average Macro F1 | 0.902262

## Citation
[LosCalis at PoliticEs 2022: Political Author Profiling using BETO and MarIA](http://ceur-ws.org/Vol-3202/politices-paper1.pdf)
To cite this resource in a publication please use the following:

```
@inproceedings{carrasco2022loscalis,
  title={LosCalis at PoliticEs 2022: Political Author Profiling using BETO and MarIA},
  author={Carrasco, Sergio Santamaria and Rosillo, Roberto Cuervo},
  booktitle={Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2022). CEUR Workshop Proceedings, CEUR-WS, A Coruna, Spain},
  year={2022}
}

```
