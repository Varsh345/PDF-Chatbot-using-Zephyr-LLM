# PDF-Chatbot-using-Zephyr-LLM

📖 **About**  
PDF-Chatbot-using-Zephyr-LLM transforms static documents into dynamic conversations. Upload a PDF and interact using natural language to extract insights, summaries, and answers instantly—all powered by Zephyr 7B Alpha and a user-friendly Gradio web interface.

✨ **Features**  
- **PDF Upload:** Drag-and-drop for instant document access.  
- **Conversational AI:** Ask questions and receive intelligent, context-aware answers.  
- **Custom Insight Engine:** Powered by Zephyr 7B Alpha for deep document comprehension.  
- **Cloud-based Deployment:** Runs seamlessly on Google Colab.  
- **Easy UI:** Gradio web interface for intuitive chats.  

🧰 **Tech Stack**  
- Zephyr 7B Alpha  
- LangChain  
- ChromaDB  
- Gradio  
- Google Colab  

🏁 **Setup & Usage**  

1. **Clone Repository**
git clone https://github.com/Varsh345/PDF-Chatbot-using-Zephyr-LLM
2. **Open in Google Colab**  
Open the provided `.ipynb` notebook in Google Colab.
3. **Install Dependencies**
```!pip install langchain chromadb gradio```
4. **Model Initialization**  
Follow notebook instructions to load Zephyr 7B Alpha.
5. **Start Chatting**  
Use the Gradio interface to upload PDFs and begin querying!

### Code Overview
- `file_preprocessing(file)`: Parses and chunks PDF content.  
- `llm_pipeline(filepath)`: Handles conversational queries using Zephyr 7B Alpha.  
- `displayPDF(file)`: Preview PDF in the UI.  
- `main()`: Orchestrates the Gradio interface and user interaction.  

### Screenshots
#### Interface 
<img width="1343" height="621" alt="Screenshot 2025-09-09 181755" src="https://github.com/user-attachments/assets/58ee22e2-cfd0-4e5d-9867-9fb3331432c5" />
#### Answering View
<img width="687" height="500" alt="Screenshot 2025-09-09 182202" src="https://github.com/user-attachments/assets/174673b8-4c50-49da-81aa-4600d1aa48c3" />

### Contact & Resources
- LangChain Documentation  
- Zephyr 7B Alpha @ HuggingFace  
- For questions, contact via GitHub issues.
