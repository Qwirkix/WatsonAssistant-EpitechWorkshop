
# WatsonAssistant-EpitechWorkshop
Watson Assistant Tutorial
---

Welcome to this tutorial! Here the firsts steps:
___

1:  Create an account on IBM Cloud
    https://www.ibm.com/us-en/?lnk=m
    
2:  Create a conversation
 1. Go on Profile/MyIBM/Launch(IBM Cloud)
 2. Create a ressource
 3. Search "Watson Assistant" in the search bar and click on the widget
    found
 4. Create and Launch Watson Assistant

Exercices
-
The objective will be to create a conversation for a Restaurant. The bot will be able to tell the menu to a client.
___
1: Create a Intent which is call "Menu_Questions". Add a few sentences similar to "What's the menu?".
  
2: Create few Entities: 
 - "Yes"
 - "No"
 - 4 aliments
 - 4 drinks
 
 Complete these entities, you are free to choose your aliments.
___

3: Create a new node. Her condition will be your Intent "Menu_Questions". In this node, you will answer the question of the previous Intent.
___

4: Create a child node of the previous one. In this node, use the entities that you previously create to explain what are each aliments in the menu.
Tips: Try to find "enable multiples responses".
After an answer, the client could be able to ask for another aliments.
___

5: Your objective is now to handle error case. (What it's going on if the bot don't understand the question ?)
Ask to the client if he want more information about another aliment.
___

6: Create an Intent and different node for the end of the conversation. (The client dosn't want more informations)
___

7: Create a variable which is a counter for error case. Use this counter to redirect the conversation after the count is 2. (Like an advisor)
___

8: Create a new branch where the client can know the hours of the restaurant.
___

9: Create a node where the client can take a reservation. The bot should answer with a summary of the client said.
___

Want to go further ? Create a new conversation and try to do a QA.
If you don't know where to start, here's some links:

 - [https://www.juritravail.com/Actualite/conformite-rgpd/Id/286384](https://www.juritravail.com/Actualite/conformite-rgpd/Id/286384)
 - [https://msc-pro.epitech.eu/faq/](https://msc-pro.epitech.eu/faq/)


