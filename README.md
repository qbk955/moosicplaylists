# moosicplaylists
# Playlist Clustering Project

## Summary
This project explores the potential of using machine learning to automate the creation of music playlists, a task traditionally handled by human curators. The primary goal was to determine if machine learning could create cohesive and personalized playlists by clustering songs based on their audio features. The project utilized K-Means clustering (After learning about other possibilieties too) to group songs into distinct clusters, which were then used to generate playlists.

## Dataset
The dataset used in this project was intentionally challenging in two ways: (Which we had to find and explore ourselves)

1. **Genre Bias:** The dataset was heavily skewed towards a specific music genre. This was done to test the robustness of the clustering algorithm and to see if it could still identify meaningful clusters despite the lack of genre diversity. The genre bias aimed to push the limits of the model's ability to differentiate songs based on nuanced audio features, rather than relying solely on broad genre distinctions.

2. **Lack of Genre Labels:** The songs in the dataset were not labeled with their genre. This means that the clustering model had to rely entirely on the provided audio features without any genre information. This increased the complexity of the task, as the model had to identify similarities and differences between songs without the guidance of genre classification.

   
## Languages and Libraries Used
- **Languages:**
  - Python

- **Libraries:**
  - **Data Manipulation:** 
    - Pandas
    - NumPy
  - **Machine Learning:**
    - Scikit-learn (K-Means, StandardScaler)
  - **Spotify API:**
    - Spotipy (for playlist creation and management)
  - **Visualization:**
    - Matplotlib
    - Seaborn
  - **Notebook Environment:**
    - Jupyter Notebook

## Key Learnings
- **Machine Learning Techniques:**
  - Gained practical experience with clustering algorithms, particularly K-Means.
  - Learned how to preprocess and scale data effectively to improve clustering results.

- **Feature Selection:**
  - Gained insights into selecting and engineering features for machine learning models, such as identifying and dropping features with minimal impact (e.g., `time_signature`, `mode`, `duration_ms`).

- **API Integration:**
  - Developed skills in integrating machine learning models with external APIs, particularly Spotify, to automate playlist creation.

- **Communication:**
  - Practiced explaining technical concepts and the outcomes of machine learning models to a non-technical audience, focusing on the practical implications of the project.

## Challenges Overcome
- **Feature Selection:** 
  - Initially, the inclusion of certain features like `time_signature` and `mode` led to less cohesive clusters. By iteratively testing and refining the feature set, the final model achieved better clustering performance.
  
- **Scalability:** 
  - Handling the large volume of songs and ensuring that the Spotify API was used efficiently to create and update playlists without hitting rate limits or other restrictions required careful batch processing.
  
- **Playlist Naming:** 
  - Creating meaningful and user-friendly playlist names based on the characteristics of each cluster posed a challenge. A systematic approach was developed to identify key features that best described each cluster for more intuitive playlist names.

## Additional Reflections
- **Ethical Considerations:**
  - This project highlighted the importance of being mindful of biases in machine learning models, particularly when dealing with cultural or genre diversity in music.
  
- **Future Work:**
  - The project could be extended by incorporating user feedback loops to continually refine and personalize the playlists. Additionally, exploring other clustering techniques and incorporating more diverse datasets could further enhance the quality of the generated playlists.
    
- **Presentation Context**: The accompanying presentation was designed specifically for a Data Science Lead, who is well-versed in the technical aspects of machine learning. As such, the presentation is intentionally descriptive and uses domain-specific terminology to provide a deep dive into the methodologies and decisions made during the project.

## Some playlists 
- https://open.spotify.com/playlist/0HCXVmWEMEliOG7laJq142?si=5aac3c3049d7436a
- https://open.spotify.com/playlist/22zzCz19wth4RQA4PYiDjI?si=992c16c8c2c34e9f
- https://open.spotify.com/playlist/35y3tkkQ1hiZLzbofOGSXU?si=3230d69bd5344c6c
- https://open.spotify.com/playlist/6CzxrYvZGOkWBEOJr2vUCU?si=bfafcdb60afd44a3


