# UuPZ

## Laboratorijske vježbe
Laboratorijske vježbe se nalaze u folderu [Lab](https://github.com/BritishMenofLetters/UupZ/tree/main/Lab)<br>


## Seminar
Seminar se nalazi u folderu [Seminar](https://github.com/BritishMenofLetters/UupZ/tree/main/Seminar).

U projektu su vremensko ovisni podaci električne energije prikazani na više načina pomoću [Seaborn](https://seaborn.pydata.org/) i [Plotly](https://plotly.com/python/). Pri tom je moguće postaviti filtiranja kao što je naziv dana, redni broj dana, sata i sl. 
što se tiče modula za prikazivanje, Seaborn se koristio za razne komplicirane prikaze jer ih ima već gotove po defaultu, dok Plotly se koristio za interaktivne prikaze. 


Na kraju je napravljen model za predviđanje koristeći [XGBoost](https://xgboost.readthedocs.io/) (Extreme Gradient Boosting).

Postoje dvije .txt datoteke - `Intraday.txt` i `dummy.txt`. 

`Intraday.txt` sadrži potpune podatke za ovaj seminar dok `dummy.txt` sadrži samo dio podatka zbog boljih performansi za vrijeme testiranja kôda.
