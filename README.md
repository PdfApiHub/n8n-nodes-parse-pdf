# n8n-nodes-parse-pdf

[![NPM Version](https://img.shields.io/npm/v/n8n-nodes-parse-pdf.svg)](https://www.npmjs.com/package/n8n-nodes-parse-pdf)
[![License](https://img.shields.io/npm/l/n8n-nodes-parse-pdf.svg)](LICENSE.md)

> Extract text, tables, and structured layout data from any PDF file.

This is an [n8n](https://n8n.io/) community node powered by **[PDF API Hub](https://pdfapihub.com)**.

---

## 🚀 Install

1. Go to **Settings → Community Nodes** in n8n
2. Enter `n8n-nodes-parse-pdf`
3. Click **Install**

## 🔑 Setup

Sign up at [pdfapihub.com](https://pdfapihub.com) → copy your API key → add to n8n credentials.

---

## ✨ Features

| Parameter | Description |
|-----------|-------------|
| **Input Type** | URL or Binary file |
| **Parse Mode** | **Text** (plain text), **Layout** (position-aware), **Tables** (structured rows/columns), **Full** (everything) |
| **Pages** | `all` or specific ranges like `1-3` |

---

## 💡 Use Cases

- **Invoice processing** — extract line items and totals from PDF invoices
- **Data entry automation** — pull structured data from forms
- **Search indexing** — extract text for full-text search
- **Report analysis** — parse tables from financial reports into spreadsheets

## License

[MIT](LICENSE.md)
