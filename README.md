# Stock Price Behavior Prediction With Top Twenty News Headlines With Deep Learning
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
<img src="https://github.com/NavinBondade/Stock-Price-Behavior-Prediction-With-News-Headlines/blob/main/Graphs%20&%20Pictures/Distribution%20Of%20Dependent%20Variable.png?raw=true" >
<h2>Model Details</h2>
<p>For the prediction of the stock price behaviors with top twenty news headlines, I have created a deep learning model that is divided into two sections, the first section uses two one dimensional convolutional layers each followed by a max-pooling and dropout layer, and the second section uses three fully connected dense neural network layers. All the layers use RELU as an activation function except the last dense layer that uses the sigmoid activation function to map predicted values to probabilities between 0 and 1.</p>
<h2>Model Traning</h2>
<img src="https://github.com/NavinBondade/Stock-Price-Behavior-Prediction-With-News-Headlines/blob/main/Graphs%20%26%20Pictures/Loss%20and%20Accuracy%20Combine.jpg" alt="loss_accuracy">
<p>The model has been trained for five epochs. During training, the model uses Adam as an optimizer. The loss function used was mean square error to penalize the model more whenever it makes false predictions.</p>
<h2>Model Evaluation on Development Dataset</h2>
<ul>
  <li><b>Training Data Accuracy: 98%</b></li>
  <li><b>Training Data Loss: 0.014</b></li> 
  <li><b>Test Data Accuracy: 99%</b></li>
  <li><b>Test Data Loss: 0.026</b></li> 
</ul>
<br>
<h3>Confusion Matrix</h3>
<img src="https://github.com/NavinBondade/Stock-Price-Behavior-Prediction-With-News-Headlines/blob/main/Graphs%20%26%20Pictures/Confusion%20Matrix.png">
<h3>Classification Report on Development Dataset</h3>
<img src="https://github.com/NavinBondade/Stock-Price-Behavior-Prediction-With-News-Headlines/blob/main/Graphs%20%26%20Pictures/Classification%20Report.png">   
