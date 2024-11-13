# Segmentation-by-clustering
It consists of Image Segmentation Using K-means Clustering with Different K Values and Determining Optimal K Using the Elbow Method

<h1>Image Segmentation Using K-means Clustering with Different K Values</h1>
<h4>1. Import Libraries and Set Up Display:</h4> Import necessary libraries (NumPy, OpenCV, Matplotlib) and set figure size for plots.
<h4>2. Load and Prepare Image:</h4> Load the image, convert it for RGB display in Matplotlib, and apply bilateral filtering to denoise.
<h4>3. Reshape Image for Clustering:</h4> Reshape the denoised image into a 2D array for clustering.
<h4>4. Define K-means Criteria and Cluster with Different K Values:</h4> Set the termination criteria and use a loop to apply K-means clustering for a range of K values (e.g., 2, 4, 6, 8).
<h4>5. Display Original, Denoised, and Clustered Images:</h4> Show the original, denoised, and segmented images for each K value side by side to observe clustering effects.

<h1>Determining Optimal K Using the Elbow Method</h1>
<h4>1. Import Libraries and Load Image:</h4> Import libraries (including scikit-learn's KMeans for clustering) and load the image.
<h4>2. Denoise and Reshape Image:</h4> Apply bilateral filtering for noise reduction and reshape the image for clustering.
<h4>3. Apply the Elbow Method to Find Optimal K:</h4> 
        -Define a range of K values to test.<br>
        -Fit K-means clustering for each K value and calculate the Within-Cluster Sum of Squares (WCSS).
<h4>4. Plot the Elbow Curve:</h4> Plot WCSS versus the number of clusters to find the "elbow," suggesting the optimal K.
<h4>5. Cluster Image with Optimal K:</h4> Choose the optimal K based on the elbow curve, and use cv.kmeans() with this K to segment the image.
<h4>6. Display Original, Denoised, and Final Clustered Image:</h4> Show the original, denoised, and final segmented images with the optimal K.

