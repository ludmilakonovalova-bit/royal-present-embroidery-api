# 🧵 Royal Present Embroidery API

![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)
![OpenAPI](https://img.shields.io/badge/OpenAPI-3.1.0-brightgreen)
![Status](https://img.shields.io/badge/status-active-success)
![Platform](https://img.shields.io/badge/platform-Royal%20Present%20Embroidery-orange)

Public **OpenAPI specification** and **AI Plugin manifest** for  
[Royal Present Embroidery](https://royal-present.com) —  
the marketplace of **machine embroidery designs** and **digital patterns**.

---

## 📘 Overview

This API provides structured access to embroidery **designs**, **categories**, and **hoop sizes**.  
It powers AI systems, search engines, and integrations with ChatGPT Plugins.

- **Base URL:** `https://royal-present.com`
- **Version:** `v1.0.0`
- **Formats:** JSON
- **Schema:** OpenAPI 3.1.0
- **Manifest:** `.well-known/ai-plugin.json`

---

## 📂 Endpoints

| Endpoint | Method | Description |
|-----------|---------|-------------|
| `/api/gpt/categories/` | `GET` | Returns available embroidery categories |
| `/api/gpt/hoops/` | `GET` | Lists supported hoop sizes |
| `/api/gpt/designs/` | `GET` | Search embroidery designs by name, category, or hoop size |

### Example request
```bash
curl "https://royal-present.com/api/gpt/designs/?query=rose"
