# Foretelling The Stock Price Behavior Prediction By Top Twenty News Headlines Using Deep Learning & NLP
<img src="https://www.thestreet.com/.image/t_share/MTcwMDkyODc4NDY5NTM5MTAy/stock-price-lead.jpg" alt="Fake_And_Real_News_Classification" width="970" height="510">
<p>News headline plays a critical role in determining the stock price behavior that mainly because most of the stockholder makes stock related decisions based on recent news. And that's why the sentiment of the news related to a particular company highly determines whether the stock of that company will grow up, down, or stay the same. To predict this behavior of the stocks I have created a deep learning system that helps to determine how the stock will behave based on the top twenty news headlines.</p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
  <li>Spacy</li>
  <li>BeautifulSoup</li>
  <li>Wordcloud</li>
</ul>
<h2>Target Class Distribution</h2>
<img src="https://github.com/NavinBondade/Foretelling-The-Stock-Price-Behavior-With-Major-News-Headlines/blob/main/Graphs%20%26%20Pictures/Distribution%20Of%20Dependent%20Variable.png">
<br>
<p align="center"> 
<img src="https://github.com/NavinBondade/Foretelling-The-Stock-Price-Behavior-With-Major-News-Headlines/blob/main/Graphs%20%26%20Pictures/Distribution%20Of%20Dependent%20Variable%20In%20Percentage.png">
</p>    
<h2>Model Details</h2>
<p>For the prediction of the stock price behaviors with top twenty news headlines, I have created a deep learning model that is divided into two sections, the first section uses two one dimensional convolutional layers each followed by a max-pooling and dropout layer, and the second section uses three fully connected dense neural network layers. All the layers use RELU as an activation function except the last dense layer that uses the sigmoid activation function to map predicted values to probabilities between 0 and 1.</p>
<h2>Model Traning</h2>
<img src="https://github.com/NavinBondade/Foretelling-The-Stock-Price-Behavior-With-Major-News-Headlines/blob/main/Graphs%20%26%20Pictures/loss-accuracy.png" alt="loss_accuracy">
<p>The model has been trained for five epochs. During training, the model uses Adam as an optimizer. The loss function used was mean square error to penalize the model more whenever it makes false predictions.</p>

<h2>Model Evaluation on Development Dataset</h2>
<ul>
  <li><b>Training Data Accuracy: 98%</b></li>
  <li><b>Training Data Loss: 0.014</b></li> 
  <li><b>Test Data Accuracy: 99%</b></li>
  <li><b>Test Data Loss: 0.026</b></li> 
</ul>
<br>
<h2>Confusion Matrix</h2>
<img src="https://github.com/NavinBondade/Foretelling-The-Stock-Price-Behavior-With-Major-News-Headlines/blob/main/Graphs%20%26%20Pictures/Confusion%20Matrix.png">
<h2>Classification Report on Development Dataset</h2>
<img src="https://github.com/NavinBondade/Foretelling-The-Stock-Price-Behavior-With-Major-News-Headlines/blob/main/Graphs%20%26%20Pictures/Classification%20Report.png">   
<h2>Conclusion</h2>
<p>In this project, I have created a deep learning model that foretells how the stock price of a company will behave by considering major news headlines with an impressive accuracy of 98 percent.</p>
