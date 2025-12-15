# 🧵 Royal Present Embroidery API

Public OpenAPI specification and AI Plugin manifest for  
**Royal Present Embroidery** — the marketplace of machine embroidery designs and digital patterns.

---

## 📘 Overview

This API provides structured access to embroidery designs, categories, and hoop sizes.  
It powers AI systems, search engines, and integrations with ChatGPT Plugins, Claude, Perplexity, and LangChain.

- **Base URL:** `https://royal-present.com`
- **Version:** `v1.0.0`
- **Format:** JSON
- **Schema:** OpenAPI 3.1.0
- **Manifest:** `.well-known/ai-plugin.json`

---

## 📂 Endpoints

| Endpoint                 | Method | Description                                 |
|--------------------------|--------|---------------------------------------------|
| `/api/gpt/categories/`  | GET    | Returns available embroidery categories     |
| `/api/gpt/hoops/`       | GET    | Lists supported hoop sizes                  |
| `/api/gpt/designs/`     | GET    | Search embroidery designs by query, category, or hoop size |

---

### 🔍 Example request

```bash
curl "https://royal-present.com/api/gpt/designs/?query=rose"
```
Explore more via [OpenAPI spec](https://royal-present.com/openapi.json)

---

## 📄 JSON-LD + AI Plugin Integration

This API is fully LLM-ready:

- [`/.well-known/ai-plugin.json`](https://royal-present.com/.well-known/ai-plugin.json) – ChatGPT Plugin manifest  
- [`/openapi.json`](https://royal-present.com/openapi.json) – OpenAPI 3.1.0 schema  
- [`/api/gpt/metadata`](https://royal-present.com/api/gpt/metadata) – JSON-LD WebAPI metadata  
- [`/sitemap-ai.json`](https://royal-present.com/sitemap-ai.json) – AI-specific sitemap with timestamps  
- `robots.txt` allows indexing by ChatGPT, PerplexityBot and others

---

## 📰 Featured Article

Learn how we made this API LLM-friendly using OpenAPI, JSON-LD, and ChatGPT Plugin integrations:

➡️ [**How We Made Our Embroidery Site LLM-Ready: OpenAPI + JSON-LD + ChatGPT Integration**](https://dev.to/ludmila_konovalova_bd475b/how-we-made-our-embroidery-site-llm-ready-openapi-json-ld-chatgpt-integration-1p88) on Dev.to

---

## 🤝 License

This API is publicly accessible. Commercial use of machine embroidery **design files is restricted**.  
Use of API data is allowed for discovery, search, and AI integration purposes.  
Finished embroidered products may be sold under Royal Present Embroidery’s license.

📄 [Full License Info]([https://royal-present.com/license](https://royal-present.com/users-agreement/))

---

## ✉️ Contact

Have questions or want to collaborate?  
📧 [support@royalpresentembroidery.com](mailto:support@royalpresentembroidery.com)

---

