# Python-Final-Project

print("This is Technowledgy Trivia! This multiple choice trivia quiz will test your knowledge on technology in business and common programming frameworks.")

print("When answering each question, put the letter of the multiple choice option you believe is correct.")

print("After each question, answer 'YES' if you'd like to see background information on the topic you were quizzed on.")

print("Click on the link at the end of each background information summary to learn more about the topics you were quizzed on!")

# set quiz score to 0

score = 0
score = int(score)

print("You have two categories to choose from. Enter '1' for Business Technology or enter '2' for Programming Frameworks.")

chooseCategory = input("Choose a Category")
if chooseCategory == 1:

# question 1
   print("Question 1: What was the name of the software created by Steve Jobs that was eventually adapted by Apple?")
   
   print("A.) NextStep (NS)")
   
   print("B.) Apple Uno")
   
   print("C.) Objective - C programming language")
   
   print("D.) None of the above")

    Q1C1Answer = "A" # right answer to question 1
    Q1C1Response = input("Your Answer: ")
    

    if Q1C1Response == "A" or Q1C1Response == "a":

    print("Well done, " + Q1C1Response + " is correct!")
    
    score = score + 3
    
    backgroundResponse = input("Would you like to see background information on this question?")
    
       if backgroundResponse == "YES":
       
        print("Question 1 Background Response: NextStep, commonly referred to as NS, was the original software Apple used behind their technology. The late Steve Jobs originally created the technology and Apple ultimately decided to re-hire Jobs and use his technology after initially firing him. The prefix of NextStep (NS) is used in the Objective - C programming language as part of the syntax. LINK: https://simson.net/ref/NeXT/aboutnext.htm")
        
        else:
        
        print("Sorry, " + Q1C1Response + " is incorrect!")
        
        score = score - 1
        
        backgroundResponse = input("Would you like to see background information on this question?")
        
        if backgroundResponse == "YES":
           print("Question 1 Background Response: NextStep, commonly referred to as NS, was the original software Apple used behind their technology. The late Steve Jobs originally created the technology and Apple ultimately decided to re-hire Jobs and use his technology after initially firing him. The prefix of NextStep (NS) is used in the Objective - C programming language as part of the syntax. LINK: https://simson.net/ref/NeXT/aboutnext.htm")
           
      # question 2
        print("Question 2: What was Snapchat’s original name when the company was initially formed?")
        
           print("A.) PhotoGhost")
           
           print("B.) SnapTalk")
           
           print("C.) Picaboo")
           
           print("D.) Ghost Record")
           
           Q2C1Answer = "C" # correct answer to question 2
           Q2C1Response = input("Your Answer: ")
           
          if Q2C1Response == "C" or Q2C1Response == "c":
print("Well done, " + Q2C1Response + " is correct!")

score = score + 3
     backgroundResponse = input("Would you like to see background information on this question?")
     
      if backgroundResponse == "YES":
      
   print("Snapchat’s original name was Picaboo. Picaboo was removed as the name of the social media giant after Snapchat underwent a re-design and launched to become one of the most successful iOS apps in history. LINK: https://www.theguardian.com/technology/2013/nov/13/snapchat-app-sexting-lawsuits-valuation")
          
     else:
          
     print("Sorry, " + Q2C1Response + " is incorrect!")
     
     score = score - 1
     
     backgroundResponse = input("Would you like to see background infromation on this question?")
          
      if backgroundResponse == "YES":
      print("Snapchat’s original name was Picaboo. Picaboo was removed as the name of the social media giant after Snapchat underwent a re-design and launched to become one of the most successful iOS apps in history. LINK: https://www.theguardian.com/technology/2013/nov/13/snapchat-app-sexting-lawsuits-valuation")
          
      # question 3
          
  print("Question 3: How much did Facebook offer to buy Snapchat for?")
  
    print("A.) $100 million")
    
   print("B.) $3 billion")
          
   print("C.) $1 billion")
   
   print("D.) $400 million")
          
  Q3C1Response = input("Your Answer: ")
          
   Q3C1Answer = "B" # correct answer to question 3
          if Q3C1Response == "B" or Q3C1Response == "b":
          
          print("Well done, " + Q3C1Response + " is correct!")
          score = score + 3
          backgroundResponse = input("Would you like to see background information on this question?")
          if backgroundResponse == "YES":
          print("Facebook offered to buy Snapchat for $3 billion. Snapchat co-founders Evan Spiegel and Bobby Murphy met with Mark Zuckerberg in a secret apartment in Los Angeles and ultimately turned down his offer, stating the potential to build something big was too much to turn down. Fun fact: Google offered to acquire Snapchat for $4 billion, and the Snapchat founders turned that down as well! Turned out to be a smart move, as SNAP is now trading on the stock market and went public for approximately $20 billion dollars. LINK: http://mashable.com/2014/01/06/snapchat-facebook-acquisition-2/#2NTcklevkiqk")
          
          else:
          
          print("Sorry, " + Q3C1Response + " is incorrect!")
          score = score - 1
          backgroundResponse = input("Would you like to see background infromation on this question?")
           if backgroundResponse == "YES":
                     print("Facebook offered to buy Snapchat for $3 billion. Snapchat co-founders Evan Spiegel and Bobby Murphy met with Mark Zuckerberg in a secret apartment in Los Angeles and ultimately turned down his offer, stating the potential to build something big was too much to turn down. Fun fact: Google offered to acquire Snapchat for $4 billion, and the Snapchat founders turned that down as well! Turned out to be a smart move, as SNAP is now trading on the stock market and went public for approximately $20 billion dollars. LINK: http://mashable.com/2014/01/06/snapchat-facebook-acquisition-2/#2NTcklevkiqk")
                   
   # question 4
     print("Question 4: What was the name and basis of the app that eventually became Instagram?")
     
        print("A.) Insta, photo sharing app that had no filters")
            
         print("B.) Burbn, location sharing app similar to FourSquare")
            
            print("C.) Photobook, photo app where you can apply filters but can't share photos")
            
            print("D.) Picagram, entertainment app that enabled photo and video sharing in a variety of ways")
            
            Q4C1Response = input("Your Answer: ")
            Q4C1Answer = "B" # correct answer to question 4
            
            if Q4C1Response == "B" or Q4C1Response == "b":
            
            print("Well done, " + Q4C1Response + " is correct!")
            score = score + 3
          backgroundResponse = input("Would you like to see background information on this question?")
          if backgroundResponse == "YES":
          print("Instagram was first called ‘Burbn,’ and it's core purpose was to act as a location check - in app similar to Foursquare. Instagram founder Kevin Systrom and CTO Mike Krieger saw that Burbn users shared photos on the app more than anything else, so they decided to only use the photo-sharing portion of the app and turn it into Instagram. Systrom said he named the original app ‘Burbn’ because of how much he likes whiskey! LINK: https://www.theatlantic.com/technology/archive/2014/07/instagram-used-to-be-called-brbn/373815/")
          
          else:
          
          print("Sorry, " + Q4C1Response + " is incorrect!")
          score = score - 1
          backgroundResponse = input("Would you like to see background information on this question?")
          if backgroundResponse == "YES":
          print("Instagram was first called ‘Burbn,’ and it's core purpose was to act as a location check - in app similar to Foursquare. Instagram founder Kevin Systrom and CTO Mike Krieger saw that Burbn users shared photos on the app more than anything else, so they decided to only use the photo-sharing portion of the app and turn it into Instagram. Systrom said he named the original app ‘Burbn’ because of how much he likes whiskey! LINK: https://www.theatlantic.com/technology/archive/2014/07/instagram-used-to-be-called-brbn/373815/")
          
          # question 5, final question of category 1
          
 print("Question 5: What is the name of the VR company that Facebook acquired?")
 
 print("A.) WhatsApp")
 
 print("B.) HTC")
 
 print("C.) Sony")
 
 print("D.) Oculus")
 
 Q5C1Response = input("Your Answer: ")
 Q5C1Answer = "D" # correct answer to question 5
 if Q5C1Response == "D" or Q5C1Response == "d":
 
 print("Well done, " + Q5C1Response + " is correct!")
 score = score + 3
 backgroundResponse = input("Would you like to see background information on this question?")
 if backgroundResponse == "YES":
 
 print("Oculus is the name of the VR company that was acquired by Facebook. The acquisition price was $2 billion and allowed FB to become a power player in the VR industry. LINK: https://techcrunch.com/2014/07/21/facebooks-acquisition-of-oculus-closes-now-official/")
 
 else:
 
 print("Sorry, " + Q5C1Response + " is incorrect!")
 score = score - 1
backgroundResponse = input("Would you like to see background information on this question?")
 if backgroundResponse == "YES":
 
 print("Oculus is the name of the VR company that was acquired by Facebook. The acquisition price was $2 billion and allowed FB to become a power player in the VR industry. LINK: https://techcrunch.com/2014/07/21/facebooks-acquisition-of-oculus-closes-now-official/")
            
            
if chooseCategory == 2:

# question 1 of Category 2 (Programming Frameworks)

print("Question 1: What programming language was originally used to program iPhone apps such as Snapchat, Vine, and Instagram?")

print("A.) Swift")

print("B.) Objective - C")

print("C.) Python")

print("D.) HTML")

Q1C2Response = input("Your Answer: ")
Q1C2Answer = "B" # correct answer to question 1

if Q1C2Response == "B" or Q1C2Response == "b":

print("Well done, " + Q1C2Response + " is correct!")
score = score + 3
 backgroundResponse = input("Would you like to see background information on this question?")
 if backgroundResponse == "YES":
 print("Objective - C was used to program iPhone apps such as Snapchat, Vine, and Instagram. Why not Swift? Swift was first released to the public in the summer of 2014 and is still a relatively new language compared to Objective - C. With that being said, many apps have changed their codebases from Objective - C to Swift due to the latter language’s versatility. LINK: https://www.toptal.com/swift/from-objective-c-to-swift")
 
 else:
 
 print("Sorry, " + Q1C2Response + " is incorrect!")
 
 score = score - 1
 
 backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("Objective - C was used to program iPhone apps such as Snapchat, Vine, and Instagram. Why not Swift? Swift was first released to the public in the summer of 2014 and is still a relatively new language compared to Objective - C. With that being said, many apps have changed their codebases from Objective - C to Swift due to the latter language’s versatility. LINK: https://www.toptal.com/swift/from-objective-c-to-swift")
 
 # question 2 
 
 print("Question 2: What is considered the beginner programming language for building websites and web frameworks?")
 
 print("A.) Ruby on Rails")
 
 print("B.) Python")
 
 print("C.) Objective - C")
 
 print("D.) PHP")
 
 Q2C2Response = input("Your Answer: ")
 Q2C2Answer = "A" # correct answer to question 2
 
 if Q2C2Response == "C" or Q2C2Response == "c":
 
 print("Well done, " + Q2C2Response + " is correct!")
 score = score + 3
 
backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("Ruby on Rails is considered the most flexible language for beginner programmers looking to start web development. LINK: https://www.coursereport.com/blog/ruby-vs-python-choosing-your-first-programming-language")
 
 else: 
 
 print("Sorry, " + Q2C2Response + " is incorrect!")
 score = score - 1
 
backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("Ruby on Rails is considered the most flexible language for beginner programmers looking to start web development. LINK: https://www.coursereport.com/blog/ruby-vs-python-choosing-your-first-programming-language")
 
 # question 3
 
 print("Question 3: What are the three programming languages commonly associated with developing smartphone applications?")
 
 print("A.) PHP, Java, Swift")
 
 print("B.) Java, Objective - C, Swift")
 
 print("C.) Python, PHP, HTML")
 
 print("D.) Objective - C, Swift, PHP")
 
 Q3C2Response = input("Your Answer: ")
 Q3C2Answer = "B" # correct answer to question 3
 
 if Q3C2Response == "B" or Q3C2Response == "b":
 
 print("Well done, " + Q3C2Response + " is correct!")
 score = score + 3
 
 backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("Java, Objective - C, and Swift are the three central languages used to program smartphone applications. Objective - C and Swift are used to create iPhone apps, while Java is the programming language for Android developers. No link for this question.")
 
 else:
 
 print("Sorry, " + Q3C2Response + " is incorrect!")
 score = score - 1
 
  backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("Java, Objective - C, and Swift are the three central languages used to program smartphone applications. Objective - C and Swift are used to create iPhone apps, while Java is the programming language for Android developers. No link for this question.")
 
 # question 4
 
 print("Question 4: What tasks do for and while loops accomplish?")
 
 print("A.) For loops run a specified task once and while loops run a task repetitively.")
 
 print("B.) For loops run a specified task multiple times and while loops run a task for a certain amount of time.")
 
 print("C.) For loops run a specified task once and while loops run a task repetitively.")
 
 print("D.) For loops run a specified task multiple times and while loops run an undefined set of conditions.")
 
 Q4C2Response = input("Your Answer: ")
 Q4C2Answer = "B" # correct answer to question 4
 
 if Q4C2Response == "B" or Q4C2Response == "b":
 
 print("Well done, " + Q4C2Response + " is correct!")
 score = score + 3
 
 backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("For loops run a specified task multiple times and while loops run a task for a certain amount of time. For loops have parameters that run the code more than once, and while loops run code for only a certain amount of time depending on the parameters set in the code. LINK: http://www.pythonforbeginners.com/control-flow-2/python-for-and-while-loops")
 
 else: 
 
 print("Sorry, " + Q4C2Response + " is incorrect!")
 score = score - 1
 
  backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("For loops run a specified task multiple times and while loops run a task for a certain amount of time. For loops have parameters that run the code more than once, and while loops run code for only a certain amount of time depending on the parameters set in the code. LINK: http://www.pythonforbeginners.com/control-flow-2/python-for-and-while-loops")
 
 # question 5
 
 print("What are constants and where do they get defined within a code document?")
 
 print("A.) Constants are class variables that can be applied to any method and they get defined outside the scope of the main code document.")
 
 print("B.) Constants are specific variables that are defined within specific functions inside the scope of the main code document and can only be applied to certain methods.")
 
 print("C.) Constants are specific variables that are defined outside the scope of the main code document and can only be applied to certain methods.")
 
 print("D.) Constants are class variables that can only be applied to specific methods and they get defined outside the scope of the main code document.")
 
 Q5C2Response = input("Your Answer: ")
 Q5C2Answer = "A" # correct answer to question 5
 
 if Q5C2Response == "A" or Q5C2Response == "a": 
 
 print("Well done, " + Q5C2Response + " is correct!")
 score = score + 3
 
 backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("Constants are class variables that can be applied to any method and they get defined outside the scope of the main code document. When defining a constant before your main code methods, it can be used anywhere within the main scope of the code as long as the constant (hard - coded variable) is referenced correctly. LINK: http://stackoverflow.com/questions/24122798/what-are-constants-and-literal-constants")
 
 else: 
 
 print("Sorry, " + Q5C2Response + " is incorrect!")
 score = score - 1
 
 backgroundResponse = input("Would you like to see background information on this question?")
 
 if backgroundResponse == "YES":
 
 print("Constants are class variables that can be applied to any method and they get defined outside the scope of the main code document. When defining a constant before your main code methods, it can be used anywhere within the main scope of the code as long as the constant (hard - coded variable) is referenced correctly. LINK: http://stackoverflow.com/questions/24122798/what-are-constants-and-literal-constants")
 
 
 
 





       
        
        
