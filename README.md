# HDFC HYBRID FAQ CHATBOT ( DistilBERT + GPT-2 FALLBACK)
- **Description:**  
   Built a hybrid chatbot for HDFC Bank FAQs using DistilBERT for retrieval-based matching and GPT-2 Medium for fallback answers.  

- **Technologies Used:**  
   - DistilBERT (for similarity matching)  
   - GPT-2 Medium (for generative fallback)  
   - FAISS (for fast similarity search)  
   - Streamlit (for UI)  

- **Approach:**  
   - DistilBERT retrieves answers from the FAQ dataset using FAISS-based similarity search.  
   - If the similarity score is low, GPT-2 generates a context-aware response.  
   - Implemented similarity thresholding for switching between retrieval and generative responses.  

- **Results:**  
   - High accuracy in retrieval-based answers with smooth fallback for unknown queries.  
   - Fast response time with accurate similarity matching.  

![image](https://github.com/user-attachments/assets/350d33db-421c-4fc7-8db0-5c35bc69d27a)
![image](https://github.com/user-attachments/assets/2d0b1d09-894f-4464-af52-06698f370e6f)
![image](https://github.com/user-attachments/assets/f05ee82c-2d8e-4e0e-ad80-7163068040d0)

