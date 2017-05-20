# Python-Final-Project

print("This is Technowledgy Trivia! This multiple choice trivia quiz will test your knowledge on technology in business and common programming frameworks.")

print("When answering each question, put the letter of the multiple choice option you believe is correct.")

print("After each question, answer 'YES' if you'd like to see background information on the topic you were quizzed on.")

# set quiz score to 0

score = 0
score = int(score)

print("You have two categories to choose from. Enter '1' for Business Technology or enter '2' for Programming Frameworks.")

if input("Choose a Category") == 1:

   # question 1
    print("Question 1: What was the name of the software created by Steve Jobs that was eventually adapted by Apple?")
    print("A.) NextStep (NS)")
    print("B.) Apple Uno")
    print("C.) Objective - C programming language")
    print("D.) None of the above")

    Q1C1Answer = "A" # right answer to question 1
    Q1C1Response = input("Your Answer: ")
    

    if Q1C1Response = "A" or Q1C1Response = "a":

    print("Well done, " + Q1C1Response + " is correct!")
    
    score = score + 3
    
    backgroundResponse = input("Would you like to see background information on this question?")
    
       if backgroundResponse = "YES":
       
        print("Question 1 Background Response: NextStep, commonly referred to as NS, was the original software Apple used behind their technology. The late Steve Jobs originally created the technology and Apple ultimately decided to re-hire Jobs and use his technology after initially firing him. The prefix of NextStep (NS) is used in the Objective - C programming language as part of the syntax.")
        
        else:
        
        print("Sorry, " + Q1C1Response + " is incorrect!")
        score = score - 1
        backgroundResponse = input("Would you like to see background information on this question?")
        if backgroundResponse = "YES":
           print("Question 1 Background Response: NextStep, commonly referred to as NS, was the original software Apple used behind their technology. The late Steve Jobs originally created the technology and Apple ultimately decided to re-hire Jobs and use his technology after initially firing him. The prefix of NextStep (NS) is used in the Objective - C programming language as part of the syntax.")
           
      # question 2
        print("Question 2: What was Snapchat’s original name when the company was initially formed?")
           print("A.) PhotoGhost")
           
           print("B.) SnapTalk")
           
           print("C.) Picaboo")
           
           print("D.) Ghost Record")
           
           Q2C1Answer = "C" # correct answer to question 2
           Q2C1Response = input("Your Answer: ")
           
          if Q2C1Response = "C" or Q2C1Response = "c":
print("Well done, " + Q2C1Response + " is correct!")

score = score + 3
     backgroundResponse = input("Would you like to see background information on this question?")
     
      if backgroundResponse = "YES":
      
   print("Snapchat’s original name was Picaboo. Picaboo was removed as the name of the social media giant after Snapchat underwent a re-design and launched to become one of the most successful iOS apps in history.")
          
     else:
          
     print("Sorry, " + Q2C1Response + " is incorrect!")
     
     score = score - 1
     
     backgroundResponse = input("Would you like to see background infromation on this question?")
          
      if backgroundResponse = "YES":
      print("Snapchat’s original name was Picaboo. Picaboo was removed as the name of the social media giant after Snapchat underwent a re-design and launched to become one of the most successful iOS apps in history.")
          
      # question 3
          
  print("Question 3: How much did Facebook offer to buy Snapchat for?")
          print("A.) $100 million")
          print("B.) $3 billion")
          print("C.) $1 billion")
          print("D.) $400 million")
          
          Q3C1Response = input("Your Answer: ")
          
          Q3C1Answer = "B" # correct answer to question 3
          if Q3C1Response = "B" or "b":
          
          print("Well done, " + Q3C1Response + " is correct!")
          score = score + 3
          backgroundResponse = input("Would you like to see background information on this question?")
          if backgroundResponse = "YES":
          print("Facebook offered to buy Snapchat for $3 billion. Snapchat co-founders Evan Spiegel and Bobby Murphy met with Mark Zuckerberg in a secret apartment in Los Angeles and ultimately turned down his offer, stating the potential to build something big was too much to turn down. Fun fact: Google offered to acquire Snapchat for $4 billion, and the Snapchat founders turned that down as well! Turned out to be a smart move, as SNAP is now trading on the stock market and went public for approximately $20 billion dollars.")
          
          else:
          
          print("Sorry, " + Q3C1Response + " is incorrect!")
          score = score - 1
          backgroundResponse = input("Would you like to see background infromation on this question?")
           if backgroundResponse = "YES":
                     print("Facebook offered to buy Snapchat for $3 billion. Snapchat co-founders Evan Spiegel and Bobby Murphy met with Mark Zuckerberg in a secret apartment in Los Angeles and ultimately turned down his offer, stating the potential to build something big was too much to turn down. Fun fact: Google offered to acquire Snapchat for $4 billion, and the Snapchat founders turned that down as well! Turned out to be a smart move, as SNAP is now trading on the stock market and went public for approximately $20 billion dollars.")
                     
             # question 4
            print("Question 4: What was the name and basis of the app that eventually became Instagram?")
            print("A.) Insta, photo sharing app that had no filters")
            print("B.) Burbn, location sharing app similar to FourSquare")
            print("C.) Photobook, photo app where you can apply filters but can't share photos")
            print("D.) Picagram, entertainment app that enabled photo and video sharing in a variety of ways")
            
            Q4C1Response = input("Your Answer: ")
            Q4C1Answer = "B" # correct answer to question 4
            
            if Q4C1Response = "B" or "b":
            
            print("Well done, " + Q4C1Response + " is correct!")
            score = score + 3
          backgroundResponse = input("Would you like to see background information on this question?")
          if backgroundResponse = "YES":
          print("Instagram was first called ‘Burbn,’ and it's core purpose was to act as a location check - in app similar to Foursquare. Instagram founder Kevin Systrom and CTO Mike Krieger saw that Burbn users shared photos on the app more than anything else, so they decided to only use the photo-sharing portion of the app and turn it into Instagram. Systrom said he named the original app ‘Burbn’ because of how much he likes whiskey!")
          
          else:
          
          print("Sorry, " + Q4C1Response + " is incorrect!")
          score = score - 1
          backgroundResponse = input("Would you like to see background information on this question?")
          if backgroundResponse = "YES":
          print("Instagram was first called ‘Burbn,’ and it's core purpose was to act as a location check - in app similar to Foursquare. Instagram founder Kevin Systrom and CTO Mike Krieger saw that Burbn users shared photos on the app more than anything else, so they decided to only use the photo-sharing portion of the app and turn it into Instagram. Systrom said he named the original app ‘Burbn’ because of how much he likes whiskey!")
          
          # question 5, final question of category 1
          
 print("Question 5: What is the name of the VR company that Facebook acquired?")
 print("A.) WhatsApp")
 print("B.) HTC")
 print("C.) Sony")
 print("D.) Oculus")
 
 Q5C1Response = input("Your Answer: ")
 Q5C1Answer = "D" # correct answer to question 5
 if Q5C1Response = "D" or "d":
 
 print("Well done, " + Q5C1Response + " is correct!")
 score = score + 3
 backgroundResponse = input("Would you like to see background information on this question?")
 if backgroundResponse = "YES":
 
 print("Oculus is the name of the VR company that was acquired by Facebook. The acquisition price was $2 billion and allowed FB to become a power player in the VR industry.")
 
 else:
 
 print("Sorry, " + Q5C1Response + " is incorrect!")
 score = score - 1
backgroundResponse = input("Would you like to see background information on this question?")
 if backgroundResponse = "YES":
 
 print("Oculus is the name of the VR company that was acquired by Facebook. The acquisition price was $2 billion and allowed FB to become a power player in the VR industry.")
            
            



       
        
        
