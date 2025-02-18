# AutoBrochureAI   

AutoBrochureAI is an AI-powered solution that automates company brochure generation by leveraging Large Language Models (LLMs), Web Scraping, and NLP. Using **OpenAI’s GPT API** and **LLaMA 3.2** for local execution, it extracts, summarizes, and structures business information from websites into professionally formatted brochures.  

Designed for businesses, marketers, and startups, this tool streamlines promotional content creation, eliminating the need for manual curation. **Multi-shot prompting** ensures refined, coherent, and structured outputs.  

###  **Key Features & Implementation**  

- **AI-Powered Summarization** – Uses **OpenAI GPT** and **LLaMA 3.2** for accurate and engaging content.  
- **Automated Web Scraping** – Extracts key business details via `requests` and `BeautifulSoup`.  
- **Multi-Shot Prompting** – Enhances text quality and consistency.  
- **Customizable Templates** – Outputs structured, ready-to-use brochures.  
- **Secure API Management** – `.env` file ensures safe key storage.  
- **Scalable & Adaptable** – Suitable for multiple industries and business types.  

---

##  Installation & Usage  

### **1️⃣ Setup Environment**  
```bash
git clone https://github.com/yourusername/AutoBrochureAI.git
cd AutoBrochureAI
pip install -r requirements.txt
```

### **2️⃣ Configure API Keys**  
Create a `.env` file for OpenAI API access:  
```bash
OPENAI_API_KEY=your_api_key_here
```
For **LLaMA 3.2 local execution**, ensure the model is installed and properly configured.  

### **3️⃣ Run the Project**  
```bash
python autobrochure.py --company "Tesla" --website "https://www.tesla.com"
```
This generates a structured brochure ready for use.  

---

## Example Output  

🔹 **Company Name**: Tesla  
🔹 **Industry**: Automotive, Renewable Energy  
🔹 **About**: Tesla is a global leader in electric vehicles and clean energy solutions, dedicated to accelerating the world’s transition to sustainable energy.  
🔹 **Products & Services**: Electric Cars, Solar Energy, Energy Storage  

_(Full brochure sample available in the repository.)_  



