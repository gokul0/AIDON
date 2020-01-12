# AIDON

This is a proof-of-concept for the IBM call for code hackathon.

## Idea
 - Use of climatic data to predict rains and floods.
 - For PoC, we are just using Precipitation and Elevation levels in a particular lat long to predict floods.
 - When a region is predicted to be flooded, the volunteers/ donors are contacted to bring in the donations to the needy people.
 -  This proactive method helps people to connect donors and natural disaster victims.
 
 ## Working
  - The PredictionModel.ipynb uses the data to build a regression model
  - The regression is used to predict the floods in case of high precipitation and low elevation levels.
  - FlaskServer.ipynb exposes an API that when hit with precipitation and elevation info, returns flood level predictions as response.
  - DonorsDash is the client website for viewing flodded regions and contacting the donors interactively.
