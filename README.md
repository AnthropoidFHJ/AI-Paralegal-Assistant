📦 **Setup Instructions**

1. **Clone the Repository**
```bash
git clone https://github.com/AnthropoidFHJ/AI-Paralegal-Assistant.git
cd AI-Paralegal-Assistant
```

2. **Create Python Environment**
```bash
python -m venv venv

#Linux/macOS:
source venv/bin/activate

#Windows: 
venv\Scripts\activate
```

3. **Install Requirements**
```bash
pip install -r requirements.txt
```

4. **Configure Environment Variables**
Create a `.env` file in the root directory:
```env
PINECONE_API_KEY="Your_Pinecone_API_Key"
GROQ_API_KEY="Your_Groq_API_Key"
```

5. **Run the Application**

```bash
python pinecone_db.py  
python app.py 
```

Visit: [http://localhost:7654](http://localhost:7654)

---