# Moosic - Audio Feature Clustering 

In this project, my team and I set out to explore the following questions:

- **Can Spotify’s audio features identify “similar songs” based on human-perceivable characteristics?**
- **Is K-Means a suitable method for creating playlists?**

## 📊 Dataset

We used a dataset of **5,000 songs**, which is included in this repository.  
The dataset contains various **audio features** provided by Spotify’s data science team, designed to quantify musical characteristics.

---

## 🎼 Audio Features Explained

| Feature            | Description |
|--------------------|-------------|
| **acousticness**   | A confidence score from 0.0 to 1.0 indicating whether the track is acoustic. 1.0 means high confidence the track is acoustic. |
| **danceability**   | Describes how suitable a track is for dancing, based on tempo, rhythm stability, beat strength, and overall regularity. 0.0 = not danceable, 1.0 = very danceable. |
| **duration_ms**    | Duration of the track in milliseconds. |
| **energy**         | Measures the track’s intensity and activity on a scale from 0.0 to 1.0. High energy = fast, loud, and noisy (e.g. metal); low energy = calm, soft (e.g. classical music). |
| **instrumentalness** | Predicts whether a track contains vocals. The closer to 1.0, the more likely the track is instrumental. Values above 0.5 generally indicate instrumental tracks. |
| **key**            | The key of the track using Pitch Class notation (e.g. 0 = C, 1 = C♯/D♭, 2 = D, etc.). |
| **liveness**       | Detects the presence of a live audience. Values above 0.8 suggest the track was likely performed live. |
| **loudness**       | Overall loudness of the track in decibels (dB). Typically ranges between -60 and 0 dB. |
| **mode**           | Indicates modality: 1 = major, 0 = minor. |
| **speechiness**    | Detects the presence of spoken words. Values closer to 1.0 suggest more speech-like content (e.g. podcasts, spoken word). |
| **tempo**          | The estimated tempo of the track in beats per minute (BPM). |
| **time_signature** | The estimated overall time signature (number of beats per measure). |
| **valence**        | Describes the musical positiveness of a track. High valence = happy, cheerful; low valence = sad, depressed. |

---

## 🚀 Goal

Using these features, we aimed to evaluate the performance of **unsupervised learning methods**, particularly **K-Means clustering**, in identifying musically and emotionally coherent song groupings — which could serve as the foundation for **automated playlist generation**.

