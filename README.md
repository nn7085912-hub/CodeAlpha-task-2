𝗡𝗮𝗺𝗲: Gurivigandla Naresh
𝗦𝘁𝘂𝗱𝗲𝗻𝘁 𝗜𝗗: CA/SE1/18253
𝗗𝗼𝗺𝗮𝗶𝗻: python programming
𝗗𝘂𝗿𝗮𝘁𝗶𝗼𝗻: 10th October 2025 to 10th November 2025
# CodeAlpha-task-2
# --- Function to generate chatbot response ---
def chatbot_response(user_input):
    user_input = user_input.lower()  # convert input to lowercase for consistency

    if user_input in ["hello", "hi", "hey"]:
        return "Hi!"
    elif user_input in ["how are you", "how are you?"]:
        return "I'm fine, thanks! How about you?"
    elif user_input in ["bye", "goodbye", "see you"]:
        return "Goodbye! Have a nice day!"
    elif user_input in ["thanks", "thank you"]:
        return "You're welcome!"
    else:
        return "Sorry, I didn't understand that."

# --- Chat Loop ---
print("Simple Chatbot (type 'exit' to quit)")
while True:
    user_input = input("You: ")
    if user_input.lower() == "exit":
        print("Chatbot: Goodbye!")
        break
    response = chatbot_response(user_input)
    print("Chatbot:", response)
<img width="557" height="477" alt="image" src="https://github.com/user-attachments/assets/d6ae3b57-03ab-4418-af8c-814188d070e6" />
