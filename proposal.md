## Project Proposal

This page contains the project proposal for my senior capstone project. [Click here](https://github.com/jacksexauer/SeniorCapstone/edit/gh-pages/proposal/) to return to the main page.

### Background

Hilcorp is one of the largest privately-held, independent oil and natural gas exploration and extraction companies in the United States. It has operating areas across the country, including a natural gas field in Kenai, Alaska. As a natural gas extraction company, Hilcorp has an interest in optimizing its extraction efforts in order to minimize costs. One potential area for optimization is that of "soap" interventions. As a well extracts gas, it can also draw up dirt, small stones, and water. This additional debris can clog the well, decreasing the flow rate of the gas. In order to reinvigorate the gas flow rate, well operators perform an "intervention" by dropping a specialized bar of soap into the well, which loosens the dirt, water, and other debris.

Currently, the choice of when to perform a soap intervention, how much soap to use, and which type of soap to use is up to the active well operator. Hilcorp has a business interest in optimizing their soap interventions because an optimal process would save the business on soap costs and sustain an ideal gas flow rate.

### Project Idea

This project will analyze data metrics collected from Hilcorp's Kenai natural gas wells in order to optimize the soap intervention process. 

Among these data metrics are the well's gas flow rate, pressure, and temperature. Since a soap intervention is generally conducted in response to an undesirable decrease in gas flow rate, the optimal time to perform the intervention could be related to the flow rate or other variables. For this project, optimization algorithms will be used to predict the ideal intervention time. The success of an intervention will be evaluated by the resulting increase in flow rate.

### Project Scope 

The majority of the scope of this project will involve performing machine learning optimization on the well datasets. This will include the standard steps of a machine learning project:
- Procuring and accessing well data
- Cleaning and preparing well data
- Identifying and selecting appropriate optimization algorithms
- Training the algorithms
- Testing the algorithms

Due to the information present in the well data, there are a couple different datasets that could be analyzed. The first dataset will contain just the metric data relating to flow rate, temperature, and pressure. This first dataset will be used to determine the optimal time to perform a soap intervention. A second possible dataset would contain additional data about the type and amount of soap used in each intervention. 

The limitation with this second dataset is that not every intervention has been labelled with the type and amount of soap used, which limits the ability to answer the question at hand. There have been discussions about creating an easier way to record this soap data to bolster the existing dataset, but that may not happen in time for the end of the semester. As such, the questions of the amount of soap and the type of soap are "possibly in-scope".

Once the well data has been optimized, the results will need to be presented/delivered to Hilcorp's Kenai group. I have not yet determined the most appropriate way to do this, and I will establish how to do so with conversations with my Hilcorp contacts.

### Technical Elements

There are several technical elements necessary to the success of the project. In order to access Hilcorp's well data, I will use whatever system is available for my use. For data exploration, I will likely use Excel or an RDMS, depending on the size of the data sets. For preparing, cleaning, and processing the data, I will use Python 3 and machine learning/data science libraries written in such. I have used scikitlearn before, but I may also us Pytorch or TensorFlow, depending on what my needs end up being. I will use Jupyter notebooks for data exploration, initial development, and testing because they are flexible and retain variables in memory.

### Timeline
- Feb. 07: Get access to data from Hilcorp
- Feb. 14: Data preparation
- Feb. 21: Data preparation
- Feb. 28: Algorithm Selection
- Mar. 07: Model training
- Mar. 14: Model training
- Mar. 21: Model testing/validation
- Mar. 28: Model testing/validation
- Apr. 04: Results preparation/delivery
