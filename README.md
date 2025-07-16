# 🧠📄 **Bibliography Extraction Tool**

### 🗃️ Extract Text from Images & PDFs using AWS Textract, OCR, and NLP

<div align="center">
  <img src="https://raw.githubusercontent.com/Akki-333/TEXT_EXTRACTION/380065bed721aeaee4d2bde4f971c6fae91ebf6c/UI.png" alt="UI Screenshot" width="80%" />
</div>

---

## 🚀 Features

- 📷 Extract text from images (`.jpeg`, `.png`, `.jpg`)
- 📄 Extract text from PDFs & Word documents
- 🤖 Extract **bibliographic metadata**: `Title`, `Author`, `Year`
- 🧠 Smart NLP fallback for missing fields using SpaCy
- 📑 Summarize extracted text
- 💾 Download results as `Word`, `PDF`, or `Excel`
- 🌗 Light/Dark themes available
- 🛠 Powered by AWS Textract, Tesseract OCR, and GPT-2

---

## 🛠️ Getting Started (Run Locally)

### 1. 🔁 Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. 📦 Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 3. 🔐 Configure AWS Access

Create an `.env` file in the project root with your AWS credentials:

```env
AWS_ACCESS_KEY_ID=xxxxxxxxxxxxxxxxxxxxxxxxxxxx
AWS_SECRET_ACCESS_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxx
AWS_REGION=ap-south-1
```

Make sure the IAM user has **S3** and **Textract** access.

### 4. 🚀 Run the App Locally

```bash
streamlit run app.py
```

---

## 📁 File Structure

```
├── app.py                # Streamlit main app
├── config.toml           # Streamlit theme config
├── README.md             # Project documentation
├── requirements.txt      # Dependencies
├── requirements.in       # Base dependencies
├── UI.png                # App UI screenshot
├── example.jpeg          # Sample input image
```

---

## 📸 Example Input

![example](https://raw.githubusercontent.com/Akki-333/TEXT_EXTRACTION/380065bed721aeaee4d2bde4f971c6fae91ebf6c/example.jpeg)

---

## ✨ Author

- **Akki-333**  
  [GitHub Profile](https://github.com/Akki-333)

---

## 📝 License

This project is licensed under the MIT License - feel free to use it!
