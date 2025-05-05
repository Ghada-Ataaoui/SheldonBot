# 🧠 Building a SheldonBot: A Big Bang Theory Chatbot with NLP & DialoGPT

This project demonstrates how to build a chatbot that emulates the personality of Sheldon Cooper from the TV show "The Big Bang Theory" using natural language processing (NLP) and the DialoGPT model.

## How it Works

1. **Data Acquisition:** The project uses the "Big Bang Theory Dialogues" dataset from Kaggle, which contains transcripts of conversations from the show.
2. **Data Preprocessing:** The dataset is preprocessed to create a conversational context for the model by including a specified number of previous responses for each response row.
3. **Model Selection:** The project utilizes Microsoft's DialoGPT, a variant of GPT-2 trained on a massive dataset of Reddit conversations. DialoGPT is chosen for its ability to understand dialogue structure and maintain context across multiple turns.
4. **Fine-tuning:** DialoGPT is fine-tuned on the Big Bang Theory dataset to adapt it to the specific language and conversational style of the show's characters.
5. **Chatbot Interaction:** Users can interact with the trained chatbot, SheldonBot, by providing input text, and the chatbot will generate responses based on Sheldon's personality.

## Getting Started

To run this project, you'll need:

- **Google Colab:** The project is designed to be run in a Google Colab or Kaggle environment.
- **Libraries:** Install the necessary libraries using `pip install transformers kagglehub`.
- **Kaggle API Key:** Download your Kaggle API key (`kaggle.json`) and upload it to the Colab environment.
- **Dataset:** Download the "Big Bang Theory Dialogues" dataset from Kaggle.

## Usage

1. Follow the instructions in the notebook to set up the environment, load the dataset, and fine-tune the model.
2. Once the model is trained, you can interact with SheldonBot by running the provided code for chatting.

## Sample Conversation

User: Hey, Sheldon, want to build a quantum computer together? SheldonBot: Only if I get to name it “Quanteen.”

User: That's actually pretty clever SheldonBot: Of course it is. I have an IQ of 187.

## Conclusion

This project demonstrates how to create an engaging chatbot based on a specific character using NLP and the DialoGPT model. By fine-tuning the model on a relevant dataset, you can build chatbots that mimic the conversational style of your favorite characters or personalities.
