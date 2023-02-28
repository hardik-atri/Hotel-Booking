# Business Problem
This project is about a resort hotel, who wants to predict whether a customer will cancel the booking or not. If the owner of the hotel is Being able to predict whether a customer will cancel their booking or not can provide several benefits to your hotel business, including:  

**Revenue Management**: By knowing which customers are likely to cancel, we can adjust your pricing and inventory management strategies accordingly. For example, we could offer last-minute deals to fill up rooms that would otherwise go empty, or allocate more rooms to customers who are less likely to cancel.  

**Customer Satisfaction**: By predicting which customers are more likely to cancel, we can engage with them and offer personalised services that address their concerns or needs. This can help build stronger relationships with the customers.  

# Business objectives
* Interpretability is important.  

* Errors can be very costly. We have to specially keep an eye on FN value i.e. customer has cancelled the booking, but model is predicting, its not. It can cause loss to the hotel, since they are not able to make last - minute deals.
  * Also FP values can be dangerous because it gives false information that a customer is going to cancel the booking and it can cause issues of under-    staffing.
* Probability of a data-point belonging to each class is needed since it will give a clear idea of how likely a customer will cancel the booking.  

# Data Overview
This data set contains booking information for a hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

# Performance Metrics  
F1- Score
