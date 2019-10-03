# Malaria-Bounding-Box-
<h3> Dataset </h3> 
https://www.kaggle.com/kmader/malaria-bounding-boxes
<h3> Conclusion </h3>
There are 4 Infected cell 'gametocyte', 'ring', 'difficult', 'schizont', 'trophozoite' and 2 uninfected cell 'red blood cell' and 'leukocyte'<br>
We divide it into Infected and Uninfected classfication problem <br>
Crop each cells from the actual image data (`80,000 cells`) . Each cell is labeled either 0 or 1 .<br>

<b>Metrics</b><br>
As class is heavily imbalanced We will use F1- Score as a metric . First we will check with Random forest classifer and use a neural network to determine the score . 
