
# AutoBrochureAI 🚀

An AI-powered solution that automatically generates **professional company brochures** by extracting and summarizing relevant business information from a company’s website.

## 📌 Overview

AutoBrochureAI automates the process of **brochure generation** by leveraging **Natural Language Processing (NLP) and Web Scraping** to extract key details from a company’s website and transform them into a structured, ready-to-use brochure.

This tool is designed to assist **businesses, marketers, and startups** in quickly creating promotional materials, pitch decks, and company overviews without manual content curation.

## ⚙️ Key Features

✔️ **Automated Web Scraping** – Extracts key business information from a given company website using `requests` and `BeautifulSoup`.
✔️ **NLP-Based Text Processing** – Summarizes extracted content using `OpenAI GPT` for clear and engaging company descriptions.
✔️ **Customizable Brochure Templates** – Formats extracted data into structured content with clean, professional layouts.
✔️ **User-Friendly Execution** – Requires only a **company name and website URL** as input.
✔️ **AI-Powered Content Generation** – Ensures well-structured, readable output with **minimal human intervention**.

---

## 🔧 Tech Stack & Techniques Used

### 🛠️ Core Technologies

- **Python 3.9+** – Main programming language  
- **Requests & BeautifulSoup** – Web scraping for data extraction  
- **OpenAI GPT API** – AI-powered content summarization  
- **dotenv** – Secure API key management  
- **Markdown & PDF Rendering** – Formatting final output  

### 📌 Implementation Highlights

- Uses `requests` with custom headers to **fetch web page content** dynamically.
- `BeautifulSoup` is leveraged for **structured HTML parsing** and extraction of relevant business information.
- **GPT-powered text summarization** ensures that extracted content is clear, concise, and engaging.
- Outputs are structured into **predefined brochure templates**, making the final content **visually appealing and easy to use**.

---

## 🚀 Installation & Usage

### **1️⃣ Setup Environment**
```bash
git clone https://github.com/yourusername/AutoBrochureAI.git
cd AutoBrochureAI
pip install -r requirements.txt
```

### **2️⃣ Add API Key**
Create a `.env` file and add your OpenAI API key:  
```bash
OPENAI_API_KEY=your_api_key_here
```

### **3️⃣ Run the Project**
```bash
python autobrochure.py --company "Tesla" --website "https://www.tesla.com"
```
This will generate a **structured brochure** for the company, ready for use.

---

## 📜 Example Output

🔹 **Company Name**: Tesla  
🔹 **Industry**: Automotive, Renewable Energy  
🔹 **About**: Tesla is a global leader in electric vehicles and clean energy solutions, dedicated to accelerating the world’s transition to sustainable energy.  
🔹 **Products & Services**: Electric Cars, Solar Energy, Energy Storage  

_(Full brochure sample available in the repository.)_

---

## 📌 Why AutoBrochureAI?

✅ **Saves Time** – Automates brochure creation in seconds.  
✅ **AI-Powered Summarization** – Extracts only the most relevant details.  
✅ **Scalable & Customizable** – Can be adapted for different industries.  

---

## 📩 Contributions & Contact

Have ideas to improve AutoBrochureAI? Contributions are welcome! Feel free to **open an issue or a pull request**.  

🔹 **Author**: [Your Name]  
🔹 **GitHub**: [Your GitHub Profile](https://github.com/yourusername)  
🔹 **Email**: your.email@example.com  

---

