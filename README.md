# 🎶 Personalized Song Recommender

A visually engaging and intelligent **Streamlit web app** that recommends songs based on user selection using **autoencoder-based deep learning** and **cosine similarity**. Discover musically similar tracks using audio features like BPM, Danceability, Energy, and more!

---

## 🚀 Live Demo

Link-  https://song-recommendation-app-43slcq4uzjyumbxyzrdole.streamlit.app/


---

## 📂 Project Structure

📁 Song-Recommender/

├── app.py # Main Streamlit application

├── Spotify-2000.csv # Dataset containing songs and their features

├── README.md # You're here!

├── requirements.txt # Python dependencies


---

## 📌 Features

- 🎵 Recommend similar songs using deep learning (autoencoder)
- 💡 Custom styling for a modern dark-themed UI
-  🎛 Adjustable number of recommendations
- 📈 Embeddings visualized using cosine similarity
- ⚡ Real-time interaction powered by Streamlit

---

## 🧠 How It Works

1. **Dataset**: Contains 2000 songs with metadata and audio features.
2. **Preprocessing**:
   - Missing values are filled
   - Features are normalized using `MinMaxScaler`
3. **Autoencoder**:
   - Learns compressed feature representations (embeddings)
   - Uses 2 dense encoding layers and a decoder
4. **Similarity**:
   - Cosine similarity is calculated between song embeddings
   - Top similar songs are recommended based on user-selected track

---

## 📊 Dataset

- 📁 `Spotify-2000.csv`
- Features used:
  - `Beats Per Minute (BPM)`
  - `Energy`, `Danceability`
  - `Loudness`, `Valence`, `Popularity`, etc.

---

## 📦 Install required packages

pip install -r requirements.txt

## 3. Run the Streamlit app

streamlit run app.py

```
