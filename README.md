## Hi there 👋

# 🚀 AI SEO-Gen API
**Turn content into high-ranking SEO metadata instantly.** Professional FastAPI backend using GPT-4o to automate Titles, Meta Descriptions, and Keywords.

### ⚡ Quick Start
1. `pip install fastapi uvicorn openai`
2. `export OPENAI_API_KEY='your_key_here'`
3. `uvicorn main:app --reload`

### 🛠️ API Endpoint
`POST /generate-seo`
**Payload Example:**
```json
{
  "content": "Your blog post text here...",
  "target_keywords": ["seo", "python", "ai"]
}
