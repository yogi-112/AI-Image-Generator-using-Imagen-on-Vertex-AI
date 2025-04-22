# 🖼️ AI Image Generator using Imagen on Vertex AI

This project showcases how to use **Google Cloud Vertex AI** with the **Imagen 3.0 model** to generate high-quality images from natural language prompts.

Whether you're creating prototypes for creative projects or exploring the power of Generative AI, this script gets you started fast.

---

## ✨ What It Does

✅ Connects to **Vertex AI** on Google Cloud  
✅ Uses **Imagen 3.0** to generate a realistic image from a text prompt  
✅ Saves the generated image locally (e.g., `image.jpeg`)

---

## 🛠️ Technologies Used

- [Google Cloud Vertex AI](https://cloud.google.com/vertex-ai)
- [Imagen 3.0 Model](https://cloud.google.com/vertex-ai/docs/generative-ai/overview)
- Python 3
- `vertexai` SDK

---


---

## 🚀 Getting Started
1. Set up Google Cloud:
- Enable the **Vertex AI API**
- Set up authentication with: gcloud auth application-default login

2. Install Required Packages:
 - pip install google-cloud-aiplatform

3. Run the Script:
Update the following in image_generator.py:
project_id = "your-gcp-project-id"
location = "your-region"  # e.g., us-east4

Then run: python image_generator.py

