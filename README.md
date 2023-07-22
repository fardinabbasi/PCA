# Principal Component Analysis
A common technique for **image compression** is principal component analysis (PCA). Image quality and compression ratio depend on the number of **principal components**.

Performing PCA on the "[emotion_detection](https://github.com/fardinabbasi/PCA/tree/main/emotion_detection_dateset)" dataset contains 213 images with 6 labels: Happy, Fear, Angry, Disgust, Surprise, and Sad.

<img src="/readme_images/random.png">

### How does PCA work?
First, the original data is **normalized** to have a mean of 0 and a variance of 1.
<div style="display: flex;">
    <img src="/readme_images/s1.jpg">
    <img src="/readme_images/s2.jpg">
</div>

## Best n_components
The **eigenvalues** are presented below in descending order.

The **elbow** method is employed to select the optimal n_components, which involves retaining data projections only onto principal components with significant eigenvalues.

<img src="/readme_images/elbow.png">
