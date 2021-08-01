# Covid19
This is a 3 Layer Neural Network program to predict Malaysia cases

<h3>Project Objective</h3>
<li>
	<ul>To take the early action/ decision to reduce the covid-19 cases in Malaysia </ul>
</li>

## Project Summary
Based on Malaysia historical data（Active cases, MCO, MCO2, MCO3, CMCO, RMCO, Recover1, Public Holiday and election) to predict the Malaysia Covid-19 cases 

Historical data
<br/>
<img alt="MalaysiaCoviddataPlot" src="https://github.com/LeeChongKeat/Covid19/tree/main/Img/data.PNG?raw=true" />

After import the data we convert the data to plot, so that we can visualize the data in plot method<br/>
<img alt="MalaysiaCoviddataPlot" src="https://github.com/LeeChongKeat/Covid19/tree/main/Img/dataPlot.PNG?raw=true" />

Then Create the Deep Learning Model and train the model. In my project learning rate is 0.001 and the Iterations is 100,000 times. The final result for Training loss is 0.014 and the Validation loss is 0.022
<br/>
<img alt="MalaysiaCovidModel" src="https://github.com/LeeChongKeat/Covid19/tree/main/Img/train.PNG?raw=true" />

Finally, we can use the test data to test the Model, and the Prediction result should be close to test data<br/>
<img alt="MalaysiaCovidPredict" src="https://github.com/LeeChongKeat/Covid19/tree/main/Img/Predict.PNG?raw=true" />


## Getting Started
This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps.


### Installation
1. Clone the repo
```sh
   git clone https://github.com/LeeChongKeat/Covid19.git
 ```
2. Install the Anaconda

3. Install the Python Library
 ```sh
   i) numpy
   ii) pandas
   iii) matplotlib.pyplot
   ```

## Contact
Name: Lee Chong Keat - jerry_keat@hotmail.com

Project Link: [https://github.com/LeeChongKeat/Covid19.git](https://github.com/LeeChongKeat/Covid19.git)

Blogger: https://codeallyourlife.blogspot.com/