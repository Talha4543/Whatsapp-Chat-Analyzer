Whatsapp-Chat-Analyzer
Live Demo: https://whatsapp-chat-analyzer1.streamlit.app/
📊 WhatsApp Chat Analyzer (with Machine Learning)
=================================================

Analyze your WhatsApp chat history using Python, Pandas, NLP, and Machine Learning to uncover insights like message patterns, emoji usage, most active users, sentiment trends, and more.

🚀 Features
-----------

*   📈 Basic Chat Statistics
    
    *   Total messages, words, media, and links shared
        
    *   Most active users and activity distribution
        
*   😀 Emoji Analysis
    
    *   Most frequently used emojis
        
    *   Emoji distribution charts
        
*   🕒 Time-based Analysis
    
    *   Activity by day, week, and month
        
    *   Heatmaps of chat activity
        
*   🧠 Machine Learning / NLP Features
    
    *   Sentiment Analysis of messages (positive, negative, neutral)
        
    *   Topic Modeling to discover main discussion themes
        
    *   Word Clouds of most frequent terms
        
    *   Spam / non-spam message detection (optional)
        
*   📊 Interactive Dashboard
    
    *   Built with Streamlit for an easy-to-use web interface
        

🛠️ Tech Stack
--------------

*   Python 3.9+
    
*   Libraries:
    
    *   pandas, numpy → Data processing
        
    *   matplotlib, seaborn, plotly → Visualization
        
    *   emoji → Emoji extraction
        
    *   nltk, scikit-learn, textblob → NLP & ML
        
    *   streamlit → Web-based dashboard
        

📂 Project Structure
--------------------

whatsapp-chat-analyzer/│── app.py # Streamlit app entry point│── helper.py # Helper functions for analysis│── preprocess.py # Data preprocessing functions│── models/ # ML models (sentiment, clustering, etc.)│── data/│ └── chat.txt # Exported WhatsApp chat file│── requirements.txt # Python dependencies│── README.md # Project documentation

⚙️ Installation & Setup
-----------------------

1.  Clone the repogit clone [https://github.com/Talha4543/whatsapp-chat-analyzer.git](https://github.com/Talha4543/whatsapp-chat-analyzer.git)cd whatsapp-chat-analyzer
    
2.  Create virtual environment & install dependenciespip install -r requirements.txt
    
3.  Export your WhatsApp chatOpen WhatsApp → Chat → More → Export Chat (without media)Save the .txt file inside the data/ folder
    
4.  Run the appstreamlit run app.py
    

📊 Example Insights
-------------------

*   Most Active User: 📌 Ali with 2,340 messages
    
*   Top Emoji Used: 😂, ❤️, 👍
    
*   Chat Sentiment: 68% Positive, 22% Neutral, 10% Negative
    
*   Busiest Hour: ⏰ 9 PM – 11 PM
    

🔮 Future Improvements
----------------------

*   Advanced topic modeling (LDA, BERTopic)
    
*   Deep learning-based sentiment classifier (BERT, RoBERTa)
    
*   Network graph of user interactions
    
*   Multilingual chat analysis
