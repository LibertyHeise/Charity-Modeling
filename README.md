# deep-learning-challenge

Alphabet Soup Classification Model Report
Liberty Heise


Overview 
The analysis was created to understand more about which factors would improve the success of particular charity organization over others.  The data contained a wide variety of charity organizations with many different attributes which were then narrowed down to reflect which charity organizations would succeed and which would not.

Results
- Data Preprocessing
The target for this model is: Is_Successful.

The features for this model are: Application_Type, Affiliation, Classification, Use_Case, Organization, Status, Income_Amt, Special_Considerations, Ask_Amt.

The variables removed (neither targets or features) are: EIN and Name.

- Compiling, Training, and Evaluating the Model (Round One)
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?  The target was .75, here is what I achived  Loss: 0.5988993048667908, Accuracy: 0.6997084617614746
What steps did you take in your attempts to increase model performance?
I then created a second model (called Charity_Model_Two) and began to change the following in order to get a better response.  

My first decision was to change the cutoff for both App_Type and and Class_Count.  Initially, I set it at 100 for both and then changed it on my second model to 1000 and also 200.  

When determining what to change 
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

