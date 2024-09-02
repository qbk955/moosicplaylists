# Welcome to Moosic!

Moosic is a small start-up that creates playlists curated by music experts and specialists in both old and new trends. Users can subscribe to Moosic’s website and listen to these playlists through their preferred Music App, whether it's Spotify, Apple Music, or YouTube Music. The personal touch in their playlists, each encapsulating a certain “mood” or “style,” is what users love the most.

However, as the business scales up rapidly, the process of manually curating playlists has become too slow. To address this challenge, Moosic has hired you with a clear mission: to use Data Science to introduce a level of automation in the playlist creation process.

## The Task

Moosic has provided a dataset collected from the Spotify API, which contains the audio features (such as tempo, energy, danceability, etc.) for a few thousand songs. Your task is to use a basic clustering algorithm, like K-Means, to divide this dataset into several clusters that will form the basis for new playlists.

## The Debate

There is a debate within the team regarding the effectiveness of Spotify’s audio features in capturing the actual “mood” of a song. Some team members are skeptical, believing that identifying the mood of a song is a highly subjective task that only a human can perform. On the other hand, others are optimistic that a Data Science-based approach could surpass human capabilities by creating connections between songs that might initially seem unexpected but ultimately make sense.

## The Prototype

In this first iteration of the project, Moosic expects you to deliver an initial prototype. The playlists created don’t have to be perfect, and the company understands that this is just the beginning of a lengthy process. However, your work will help answer two critical questions:

1. **Can Spotify’s Audio Features Identify “Similar Songs”?**
   - When you listen to two rock ballads, two operas, or two drum & bass tracks, you can easily identify them as similar songs. The question is whether these similarities are detectable using Spotify’s audio features.

2. **Is K-Means a Good Method for Creating Playlists?**
   - Should Moosic stick with K-Means as the primary algorithm for playlist creation, or would it be beneficial to explore other methods in the future?

Through collaboration between you and the music experts, these assessments will guide the future direction of Moosic's playlist creation strategy.
