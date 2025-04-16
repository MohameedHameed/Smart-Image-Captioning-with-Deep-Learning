
# 🧠 Smart Image Captioning with Deep Learning

## <div dir="rtl">🇸🇦 الوصف</div>

<div dir="rtl">

هذا المشروع يستخدم نموذج ذكاء اصطناعي لتوليد وصف تلقائي للصور.  
يقوم النموذج بأخذ صورة (مثل صورة كلب أو شخص في مكان ما) ثم يولّد جملة تصف محتوى الصورة بدقة.  
تم استخدام تقنيات مثل الشبكات العصبية CNN، وLSTM، ومجموعة بيانات مدربة مسبقًا لتوليد النتائج.

</div>

---

## 🇺🇸 Description

This project uses an AI model to generate automatic captions for images.  
Given an input image (e.g., a dog in a park), the model generates a descriptive sentence.  
It leverages deep learning techniques like CNNs, LSTMs, and a pretrained dataset.

---

## 🛠️ Features

- 📸 Upload an image and get a textual description.
- 🤖 Deep learning-based caption generation.
- 🧰 Uses pretrained models and image embeddings.

---

## 🚀 Usage
jupyter notebook ImageCaption.ipynb
1- Upload an image in the appropriate cell.
2 -Run the caption generation cell to see the result.
---
## 🖼️ Example
Input image:
Generated caption:
A dog sitting on green grass.
---
## 📦 Dataset
The dataset is downloaded using gdown from Google Drive, as defined in the notebook.
---
### 🧠 Model Architecture
Feature extractor: Pretrained CNN (e.g., InceptionV3)

Language model: LSTM-based decoder

Integration: Combines image features and text sequences to generate descriptions.
---
## ✍️ Author
Developed by Mohammed Hameed
Feel free to contribute or report issues via GitHub.
