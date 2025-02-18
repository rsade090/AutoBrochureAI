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
## Installation & Usage  

Install dependencies, set up API keys, and run the project:  

```bash
pip install -r requirements.txt
echo "OPENAI_API_KEY=your_api_key_here" > .env
python autobrochure.py --company "HuggingFace" --website "https://huggingface.co"
 
```
---

## Example Output  

🔹 **Company Name**: Tesla  
🔹 **Industry**: Automotive, Renewable Energy  
🔹 **About**: Tesla is a global leader in electric vehicles and clean energy solutions, dedicated to accelerating the world’s transition to sustainable energy.  
🔹 **Products & Services**: Electric Cars, Solar Energy, Energy Storage  

_(Full brochure sample available in the repository.)_  



