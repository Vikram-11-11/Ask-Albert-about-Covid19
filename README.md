# Ask-Albert-about-Covid19
Problem Statement:
As we all know that this pandemic that took place because of this corona virus disease 2019 (Covid-19) has impacted lives of so many people all around the world in some or the other way. People have stopped moving out, they are not able to go to colleges, schools, offices and not even to buy their everyday essentials. Everybody is stuck to their own places and thus this is one of the worst situations that ever happened.
During this situation there are people who are not even aware of the basic information about this dangerous disease which can always lead to their carelessness behavior and thus it would end up affecting a greater number of people.

Solution Brief Overview:
The best partner that we have, on whom we can rely upon during these crucial days is ‘Technology’ by which we can actually help them by providing sufficient information to curb on things caused by this dangerous disease and from where it started. Also, how to deal with all those necessary things that could be done to stop this spreading of disease.
We believe that technology is such a powerful tool that has expanded itself so much in all the domains and thus it has made itself more flexible for the users. 
By using this beautiful tool, we would be creating a platform (CHATBOT) where our chatbot would be acting as a bodyguard as well as an advisor to its user.

Solution Description:
There are three essential steps involved to tackle a problem-

Detection of real-world problem


                                 Finding a solution 


Working on that solution under some project











Similarly, we came across the problem that people are not fully aware about the situations that are happening in this world and to help them we are building our CHATBOT named – ‘ Albert‘.
Albert has the ability-
•	To take any questions in the form of text related to corona virus disease as its input function and provide the user with a proper solution which will act as an output function. 
•	To answer questions during any time of the day, without any issue of non-availability of customer services.
•	To answer various customers at once, as it would be quite difficult to handle when it comes to manual customer services.
•	To provide the best advice in milli-seconds to the user regarding the safety measures that are to be kept in mind while going out for some important work.
•	To provide the information related to Covid-19 tests.

So, in a nutshell it would act as your personal BOT who would assist you with various issues. 
Chatbot architecture
So how our chatbot basically works?


		

The above block diagram is a simple representation of how our chatbot functions. The chatbot basically uses 3 main components to determine how to interpret the user input and how to respond to it.
So basically while creating a chatbot we first need a dialog skill that contains all the three mentioned components which are:
•	INTENTS
•	ENTITIES
•	DIALOGS
INTENTS
Within a chatbot intent refers to the goal the customer has in mind when typing in a question or comment.With the help of intents they try to determine what the user wants? what are they asking for? In other words they capture the intent or goal of the user.
So here we have defined intents for every type of user request we want our application to support:

Introduction to Coronavirus
Origin
Prevention
Spread
Symptoms
Etc.

ENTITIES
Entities allow us to capture specific value within the user utterance or input. Entities are knowledge repositories used by the bot to provide personalized and accurate responses. Entities can be fields, data, or text describing just about anything — a time, place, person, item, number, etc. we can also define synonyms in the sense that user might refer to the entity value. So here we have defined the following entity:

Fullforms
Etc.


DIALOGS
The dialog determines the response based on the detected intents and/or entities in the input.The dialog allows us to to issue response to the user based on the basis of their intent and specifies of their request which we captured through entities we defined, it is simply a tree of nodes where each node will typically handle one particular scenario. So these are the following dialogs defined in our bot:
Welcome
Start Asking
Origin
What is Covid-19
Fullform of Covid-19
Symptoms
Spread
Prevention
Vaccine
Etc.

IBM SERVICES
IBM Watson Assistant is a white label cloud service that allows enterprise-level software developers to embed an artificial intelligence (AI) virtual assistant (VA) in the software they are developing and brand the assistant as their own. The service, which gives consumers access to Watson AI , is delivered through the IBM Cloud. Watson Assistant uses Watson AI machine learning (ML) and natural language understanding (NLU), is marketed to businesses that want to have the option of keeping the data that flows through their virtual assistant private. While creating a chatbot in Watson assistance the first thing we do is create a dialog skill which will contain all the three components discussed above. Watson assistant was a very prominent tool that helped us in creating our albert we really thank IBM Services for providing us with such a wonderful tool. 


