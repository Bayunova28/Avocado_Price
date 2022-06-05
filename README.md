# Iowa Department Avocado Price
## Table of Contents
* [Background](#background)
* [Requirement](#requirement)
* [Inspiration](#inspiration)
* [Schema](#schema)

## Background
<img src="https://github.com/Bayunova28/Iowa_Department_Avocado_Price/blob/master/images/iowa-cover.png" height="500" width="1100">

<p align="justify">The Iowa Department of Commerce is an organization or trading company located in Des Moines, Iowa, United States. The organization was created to 
coordinate and manage the various regulatory, service, and licensing functions of the state related to business or trade in the state. The department is 
administratively organized into several divisions, namely banking, credit union, utilities, insurance and agriculture. Within the banking division, the organization 
regulates and oversees various state banks, regulates loans, such as corporate loan industry, mortgage bankers, mortgage brokers, real estate closing agents, corporate
debt management, financial services companies and pending deposit services businesses and performs other tasks given to the division by legal institutions and the Act.
In addition, the division manages and coordinates the activities of professional licensing boards, such as the engineering and land surveying board, Iowa accounting
board, real estate commission, architectural examiner and interior design examiner. The credit union division is in charge of regulating and overseeing the operations
of the credit union or providing financial services, such as share capital within a state that are coordinated by the credit union review board.<p> 
  
<p align="justify">In addition, the division carries out other tasks assigned by legal institutions and laws. The insurance division is in charge of regulating and 
overseeing the conduct of the insurance business in the state and enforcing laws that have been made by the United States government, particularly under the Iowa 
government. The agriculture division is in charge of supervising and regulating as well as serving permits and regulations for the business of selling vegetables and 
fruits as well as food ingredients. In the five divisions, to organize and manage an organization, valid data is needed in making decisions from each division, especially
the agriculture division. The distribution or sale of this type of avocado must have a lot of data regarding the sale of these products and there needs to be effective 
data processing from the four divisions so that they are stored properly and not mixed with other divisions. In processing this data, it is necessary to apply 
classification so that the agriculture division can distinguish between the types of avocados that customers want. The utilities division is in charge of supervising and 
regulating public utilities, where services are aimed at customer satisfaction in consuming goods and services.<p>
  
## Requirement
### SAS® OnDemand for Academics (ODA) Registration
* To gain access to ODA, you need to register with SAS Institute. Part of the registration process is to create a [SAS profile](https://welcome.oda.sas.com/login)
* Create a SAS Profile
* Verify the SAS Profile
* Register for SAS OnDemand for Academics with SAS Profile credentials

### SAS® Visual Data Mining & Machine Learning (VDMML)
* Open [SAS®Studio](https://auth.sas.com/) & login from your SAS® OnDemand for Academics (ODA) account
* Click tab on the top left
* Choose Explore and Visualize 
* Import data in your local computer
* Save data in your public host repository dataset
  
## Inspiration
* Classification of avocado types from Agriculture Division
* Using 2 machine learning algorithms and model selection
  
### Gradient Boosting
<img src="https://github.com/Bayunova28/Iowa_Department_Avocado_Price/blob/master/images/gradient-boosting-model.png" height="600" width="1100">
  
### Neural Network
<img src="https://github.com/Bayunova28/Iowa_Department_Avocado_Price/blob/master/images/neural-network.png" height="600" width="1100">
  
### Model Selection & Scoring
<img src="https://github.com/Bayunova28/Iowa_Department_Avocado_Price/blob/master/images/model-selection.png" height="600" width="1100">

## Schema
* `Date` - The date of the observation
* `AveragePrice` - The average price of a single avocado
* `type` - Conventional or organic
* `year` - The year
* `Region` - The city or region of the observation
* `Total Volume` - Total number of avocados sold
* `4046` - Total number of avocados with PLU 4046 sold
* `4225` - Total number of avocados with PLU 4225 sold
* `4770` - Total number of avocados with PLU 4770 sold
