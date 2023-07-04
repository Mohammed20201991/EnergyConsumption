# EnergyConsumption
## Using Deep Learning, Machine Learning or Algorthims way to predict energy Consumption 
The task here is signal decomposition: different ideas can be applied, supported by mathematical representation. 
In the Excel file, you can see we have a total load of power consumption for a house over two months (or one year) as a beginning. The task is to 
identify the presence of different electrical devices inside the house from the only knowledge of the total consumption. 
For personal trials, we can use the power consumption of appliances but in the end, the purpose is to be able 
to know the appliances inside the house only by their total load consumption. This is called Disaggregation. 

Here, four different ideas can be used. 
One is shown in the PowerPoint attached. 
The second one is related to mathematical representation, 
The third one is related to graphical analysis, and the last one is related to signal decomposition.

(maybe the other option is to solve it in un-suppervisod way.) 
Disaggregation algorithms can be used to break down household energy consumption data into 
appliance-level measurements and predict the appliance state and energy consumption.
Widespread deployments of residential smart meters have caused energy disaggregation to be a popular research topic and a potential tool for electric utilities to develop demand-side incentives to 
modify customer energy consumption behavior. 
This project uses cutting-edge deep-learning techniques to develop algorithms that predict individual 
appliance energy usage using only aggregate residential smart meter interval load data.

One of the disaggregation algorithms that could be used is to divide the total load into events (event detection) and then have a mathematical model 
for each event. Using this mathematical model, and some machine learning algorithm (preferably an unsupervised approach) to detect the mathematical model of 
each event,  in the total load in this way, for example, we can say that the fridge that has this specific mathematical model is detected in the total load. 
Another idea could be to detect the presence of appliances based on their frequencies, have a histogram, and then have a  method that can detect the presence of 
each appliance based on the frequency


in the end, we have Jupiter notebook with more explanation, math models, and visualization.

## License 
This work has been done as a freelancer task. <br> 
Lara Rachidi : laraazarra21@gmail.com 
## What is the next step ? 
Collect more data like 5 years at least. And my advice will be to use Transformers In addition to using a cloud like Google Cloud (IOT) so in this case we will have a complete project cycle. And the last step is the deployment.
