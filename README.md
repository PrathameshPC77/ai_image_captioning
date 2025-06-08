# 🖼️ AI Image Caption Generator

This project is a **Streamlit-based web app** that generates captions for images using a pre-trained **Vision Transformer (ViT) + GPT-2** model. The model takes an uploaded image as input and generates a meaningful caption that describes the image's content.

---

## 🚀 Demo

![Demo Output](https://github.com/PrathameshPC77/ai_image_captioning/blob/main/output.png)

---

## 📌 Problem Statement

Manually describing images is time-consuming and not scalable, especially for large collections. This project aims to automate image captioning using deep learning models.

---

## ✅ Features

- Upload any image and get a smart caption.
- Uses **ViT (Vision Transformer)** as encoder and **GPT-2** as decoder.
- Easy-to-use **Streamlit** interface.
- Deployed model hosted on Hugging Face 🤗.

---

## 🧠 How It Works (Workflow)

1. User uploads an image via the Streamlit web interface.
2. The image is preprocessed and passed to a ViT encoder.
3. Extracted features are passed to a GPT-2 decoder.
4. GPT-2 generates a caption using beam search.
5. The caption is shown on the screen.

---

## 🧰 Tech Stack

| Technology      | Purpose                            |
|----------------|------------------------------------|
| Python          | Programming language               |
| Streamlit       | Web app framework                  |
| Hugging Face 🤗 | Pre-trained model + hosting        |
| PyTorch         | Deep learning framework            |
| Transformers    | Model loading & inference utility  |

---

## 📦 Installation & Run Locally

```bash
git clone https://github.com/PrathameshPC77/ai_image_captioning.git
cd ai_image_captioning
pip install -r requirements.txt
streamlit run app.py
```

---

## 📄 Project Structure

```
├── app.py                # Main Streamlit app
├── requirements.txt      # Python dependencies
├── .streamlit/config.toml
├── README.md             # Project documentation
└── output.png            # Demo output image
```

---

## 📚 References

- [ViT-GPT2 Image Captioning Model](https://huggingface.co/nlpconnect/vit-gpt2-image-captioning)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [Streamlit Docs](https://docs.streamlit.io/)

---

## 📈 Future Scope

- Add support for multilingual captioning.
- Fine-tune the model on custom datasets.
- Deploy on cloud using Streamlit Cloud, AWS, or GCP.

---

## 🤝 Contribution

Pull requests and suggestions are welcome! For major changes, please open an issue first.

---

## 📬 Contact

Made by [Prathamesh C.](mailto:prathu3322@gmail.com)  
Project for [AI NSI Internship Program May 2025]
