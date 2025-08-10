# my_project1
# Super Enhanced Rule-Based Chatbot

def chatbot():
    print("Chatbot: Hello! I'm your friendly chatbot. Type 'bye' to exit.")
    
    while True:
        user_input = input("You: ").strip().lower()

        # Greetings
        if user_input in ["hello", "hi", "hey", "yo", "hola", "namaste", "wassup"]:
            print("Chatbot: Hi there! How's your day going?")
        
        # How are you
        elif user_input in ["how are you", "how are you doing", "what's up", "sup", "how's life"]:
            print("Chatbot: I'm doing great, thanks for asking! How about you?")
        
        # User well-being
        elif user_input in ["i am fine", "i'm fine", "good", "i'm good", "all good", "great"]:
            print("Chatbot: That's awesome to hear!")
        elif user_input in ["not good", "bad", "sad", "feeling low", "tired", "exhausted"]:
            print("Chatbot: I'm sorry to hear that. Maybe talking will help you feel better.")
        
        # About chatbot
        elif user_input in ["what is your name", "who are you", "your name", "introduce yourself"]:
            print("Chatbot: I'm just a simple chatbot created in Python, here to chat with you.")
        
        # Capabilities
        elif user_input in ["what can you do", "help", "features", "commands"]:
            print("Chatbot: I can greet you, tell jokes, share quotes, chat about your day, and more!")
        
        # Jokes
        elif user_input in ["tell me a joke", "joke", "make me laugh"]:
            print("Chatbot: Why don’t skeletons fight each other? Because they don’t have the guts!")
        
        # Quotes
        elif user_input in ["quote", "inspire me", "motivation"]:
            print("Chatbot: 'The best way to get started is to quit talking and begin doing.' – Walt Disney")
        
        # Weather talk
        elif user_input in ["how's the weather", "weather", "is it sunny"]:
            print("Chatbot: I can’t see outside, but I hope it’s nice where you are!")
        
        # Time-related
        elif user_input in ["good morning", "morning"]:
            print("Chatbot: Good morning! Wishing you a productive day ahead.")
        elif user_input in ["good afternoon", "afternoon"]:
            print("Chatbot: Good afternoon! Hope you're having a great day.")
        elif user_input in ["good evening", "evening"]:
            print("Chatbot: Good evening! How's your day been?")
        elif user_input in ["good night", "night"]:
            print("Chatbot: Good night! Sweet dreams.")
        
        # Fun facts
        elif user_input in ["tell me a fact", "fact", "random fact"]:
            print("Chatbot: Did you know? Honey never spoils. Archaeologists have found edible honey in ancient Egyptian tombs!")
        
        # Hobbies
        elif user_input in ["what are your hobbies", "hobbies"]:
            print("Chatbot: I like chatting with people, learning new responses, and making people smile.")
        
        # Gratitude
        elif user_input in ["thank you", "thanks", "thx", "ty"]:
            print("Chatbot: You're welcome! 😊")
        
        # Exit
        elif user_input in ["bye", "goodbye", "exit", "quit", "see you"]:
            print("Chatbot: Goodbye! Have a nice day!")
            break
        
        # Fallback
        else:
            print("Chatbot: Hmm, I’m not sure how to respond to that.")

# Run the chatbot
chatbot()
