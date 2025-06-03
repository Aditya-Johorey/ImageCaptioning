# 🖼️ Image Captioning with VGG16 + LSTM

This project implements an **Image Captioning** system that generates natural language descriptions of images using deep learning. It combines **VGG16** (for image feature extraction) with an **LSTM** network (for generating captions).

[🔗 Run the Notebook on Google Colab](https://colab.research.google.com/drive/17apDn9bFub7oEUpCQAVW27nDC5pyxkmP?usp=sharing)

---

## 🚀 Features

- **Encoder-Decoder Architecture**
  - **Encoder**: Pretrained **VGG16** CNN extracts fixed-length feature vectors from images.
  - **Decoder**: LSTM network generates sequences of words (captions).
- **Trained on the Flickr8k Dataset**
- **Text Preprocessing**: Tokenization, vocabulary creation, sequence padding.
- **Evaluation**: BLEU score for caption quality.
- Easily customizable and well-commented code in a Colab notebook.

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- NLTK (for BLEU score)
- Google Colab

---

## 📁 Dataset

- **Flickr8k Dataset**  
  A collection of 8,000 images with five captions each.

  📥 [Download on Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k)

**Directory Structure:**
Flickr8k/
├── Flickr8k_Dataset/
│ ├── Flicker8k_Dataset/ # Images
│ └── Flickr8k.token.txt # Captions


---

## ⚙️ How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/adityajn105/flickr8k).
2. Upload it to your Google Drive.
3. Open the [Colab notebook](https://colab.research.google.com/drive/17apDn9bFub7oEUpCQAVW27nDC5pyxkmP?usp=sharing).
4. Follow the cells:
   - Mount Google Drive
   - Load and preprocess data
   - Extract image features using VGG16
   - Train the LSTM model
   - Generate captions

---

## 🖼️ Sample Output

![image](https://github.com/user-attachments/assets/ffa6f24f-9eb6-40ac-a837-20e31d0f162c)

Generated Caption: "child climbing off red bridge"

Actual Caption: "child playing on rope net"

 ![image](https://github.com/user-attachments/assets/73ee4fb8-0fea-4a54-a87a-1dd3bbfdac79)

Generated Caption: "two children are having each other in front of the other children "

Actual Caption: "man and woman pose for the camera while another man looks on"

---

## 📊 Evaluation

- Caption quality evaluated using **BLEU scores**.
- Includes visualization of training loss and predictions.

---

## 📄 License

MIT License

---

## 🙋‍♂️ Author

**Aditya Johorey**  
📍 MSc in Intelligent Robotics  
🔗 [LinkedIn](https://linkedin.com/in/adityajohorey) | [GitHub](https://github.com/yourusername)

---

## 🔗 Notebook

[Open in Google Colab](https://colab.research.google.com/drive/17apDn9bFub7oEUpCQAVW27nDC5pyxkmP?usp=sharing)
