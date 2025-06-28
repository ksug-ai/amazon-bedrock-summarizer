# AWS Bedrock PDF Summarizer Demo

This project showcases how to use **Amazon Bedrock** with **LangChain** to summarize a PDF using foundation models like Claude v2.

> Built for the [KSUG.AI](https://ksug.ai) community — github.com/ksug-ai/amazon-bedrock-summarizer

---

## 🔧 What You'll Need

- AWS account with **Bedrock access** (Claude model enabled)
- IAM role with permissions: `bedrock:InvokeModel`, `s3:GetObject`, etc.
- Python 3.8+
- Basic familiarity with Jupyter Notebooks

---

## 🧪 Demo Features

- Extracts text from a PDF
- Sends text to Claude via Amazon Bedrock
- Uses LangChain to format and manage prompts
- Displays summary in notebook

---

## 📦 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/ksug-ai/amazon-bedrock-summarizer.git
cd amazon-bedrock-summarizer

# Install dependencies
pip install -r requirements.txt
```

Add your **AWS credentials** as environment variables or via `~/.aws/credentials`.

---

## ▶️ Run the Notebook

Use Jupyter or VSCode to open `bedrock_pdf_summarizer.ipynb`

Upload a PDF file (e.g. `sample.pdf`) to the project root.

Run all cells to see the summary generated live using Claude.

---

## 📚 Resources

- [Amazon Bedrock Docs](https://docs.aws.amazon.com/bedrock/)
- [LangChain Docs](https://docs.langchain.com/docs/integrations/providers/bedrock)
- [KSUG.AI Community](https://linktr.ee/ksug.ai)

---

## 💬 Community

This project is built and maintained by the [KSUG.AI](https://ksug.ai) community.
Join our global network of 30,000+ cloud-native learners!

---

## 🛡 Disclaimer

[KSUG.AI](https://ksug.ai) is an independent open-source initiative and is not affiliated with or endorsed by Amazon Web Services (AWS).
