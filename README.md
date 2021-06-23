# Health_Insurance_Cross_Sell_Prediction
<h4>Final Project of my Data Analytics training at ShapeAI .</h4>
<h4>To open Jupyter Notebook click on rendered display blob 📃.</h4>
<h2>Context :</h4>
My client is an Insurance company that has provided Health Insurance to its customers now they need my help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.<br>
<br>
An insurance policy 📜 is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.<br>
<br>
My task is to build a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.<br>
<br>
In order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.<br>
<br>
This dataset is taken from <a href="https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction">Kaggle</a> . 
<br>
<h5>Data Description</h5>
<br>
<b>id</b> : Unique ID for the customer<br>
<b>Gender</b> : Gender of the customer<br>
<b>Age</b> : Age of the customer<br>
<b>Driving_License</b> :<br>
  0 : Customer does not have DL*<br>
  1 : Customer already has DL*<br>
<b>Region_Code</b> : Unique code for the region of the customer<br>
<b>Previously_Insured</b> :<br>
  1 : Customer already has Vehicle Insurance*<br>
  0 : Customer doesn't have Vehicle Insurance*<br>
<b>Vehicle_Age</b> : Age of the Vehicle<br>
<b>Vehicle_Damage</b> :<br>
  1 : Customer got his/her vehicle damaged in the past.*<br> 
  0 : Customer didn't get his/her vehicle damaged in the past.*<br>
<b>Annual_Premium</b> : The amount customer needs to pay as premium in the year<br>
<b>PolicySalesChannel</b> : Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.<br>
<b>Vintage</b> : Number of Days, Customer has been associated with the company<br>
<b>Response</b> :<br>
  1 : Customer is interested*<br>
  0 : Customer is not interested*<br>
<br>
<br>
While considering this information we will also provide other insights like :

* Which age group people prefers to take insurance ?
* What are the conditions of vehicle which are registered for insurance ?
* What kind of people like to take the insurance ?
* How much amount need to be paid as Annual Premium ?
<br>
<h4>Note : pkl file of RFModel unable to upload due to size restriction</h4>
