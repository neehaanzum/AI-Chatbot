# 🏥 Healthcare Assistant Chatbot  

### AI-Powered Medical Consultation  

check here : https://ai-chatbot-ms89xuazlmj9jqwykxstrh.streamlit.app/

  

---

## Table of Contents  
- [ Introduction](#-introduction)  
- [ Features](#-features)  
- [ Installation Guide](#-installation-guide)  
- [ How to Use](#-how-to-use)  
- [ Technology Stack](#-technology-stack)  
- [ AI & NLP Model](#-ai--nlp-model)  
- [ Future Enhancements](#-future-enhancements)  
- [ Contributing](#-contributing)  
- [ License](#-license)  

---

##  Introduction  
The **Healthcare Assistant Chatbot** is an AI-driven chatbot that provides basic medical assistance by responding to user queries about symptoms, appointments, and medications. It uses **Natural Language Processing (NLP)** and **Deep Learning** to generate responses, ensuring an interactive and informative experience.  

 Built with **Streamlit** for an intuitive user interface and powered by **Transformers (DistilGPT-2)** for AI-based responses.  

---

##  Features  
 **Symptom Guidance** - Offers preliminary advice for symptoms.  
 **Appointment Scheduling** - Assists in setting up doctor consultations.  
 **Medication Reminders** - Provides general medication adherence advice.  
 **AI-Generated Conversations** - Uses GPT-based text generation for responses.  
 **User-Friendly Interface** - Built with Streamlit for ease of use.  

---

##  Installation Guide  

### Clone the Repository  
```sh
git clone https://github.com/your-username/healthcare-chatbot.git
cd healthcare-chatbot
```

### Set Up Virtual Environment  
```sh
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### Install Dependencies  
```sh
pip install -r requirements.txt
```

### Run the Chatbot  
```sh
streamlit run app.py
```
 Open **http://localhost:8501/** in your browser to use the chatbot.  

---

## How to Use  
   Open the chatbot interface.  
   Enter a query (e.g., "I have a headache and fever").  
   The chatbot will provide guidance based on the input.  
   If relevant, it will suggest consulting a doctor or scheduling an appointment.  

---

## Technology Stack  
  **Language:** Python  
  **AI Model:** DistilGPT-2 (Transformers)  
  **NLP Libraries:** NLTK (Tokenization, Stopwords)  
  **Framework:** Streamlit (UI)  
  **Dependency Management:** Pip  

---

## AI & NLP Model  
 The chatbot utilizes:  
 - **Hugging Face’s Transformers** (`distilgpt2`) for AI-based text generation.  
 - **NLTK** for processing user input (tokenization & stopword removal).  
 - **Rule-Based Logic** for handling symptom-related queries.  

### Chatbot Behavior  
 If a user mentions **symptoms**, it suggests consulting a doctor.  
 If a user asks about **appointments**, it provides scheduling guidance.  
 If a user inquires about **medications**, it reminds them to consult their doctor.  
 Otherwise, it uses AI text generation for a conversational response.  

---

## Future Enhancements  
 **Multi-language Support** - Expand chatbot capabilities for global users.  
 **Integration with EHR Systems** - Connect to electronic health records.  
 **Personalized Health Insights** - Use AI to track patient history.  
 **Mobile App Deployment** - Bring the chatbot to iOS & Android.  

---

## Contributing  
Contributions are welcome! Feel free to submit an issue or pull request if you'd like to contribute.

---




