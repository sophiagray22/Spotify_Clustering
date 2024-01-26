## Spotify Playlist Clustering Analysis

I performed k-means clustering on my most listened to Spotify playlist. I ended up with 3 clusters, which can be visualized [here](https://public.tableau.com/views/spotify_clustering/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) in a Tableau dashboard. The most important features that determined a song's cluster were modality (major/minor key), time signature, valence and duration.

Clusters 1 was the largest cluster with 311 songs. It was characterized by popular artists such as Taylor Swift, Doja Cat, and Noah Kahan. Notably, every song in this cluster was in major key and had a time signature of 4.

Cluster 2 was the smallest, with only 39 songs. The most common artists in this cluster were WILLOW, Lana Del Rey, and Harry Styles. Songs in cluster 2, were 10 seconds shorter than the median song length for the entire playlist and had lower valence. The variable that sets cluster 2 apart is time signature. Clusters 1 and 3 are predomiantly made of songs with a time signature 4, whereas songs in cluster 2 are almost entirely in time signature 3.

Cluster 3 is second largest cluster with 189 songs, and the most common artists were Lana Del Rey, Tyler the Creator, and SZA. Cluster 3 is remarkably similar to cluster 1. Both clusters had similar durations and valence and were predominantly made of time signature 4 songs. The variable that differentiates these two clusters is modality. Every song in cluster 1 was in major key and every song in cluster 2 was in minor key.
