# Applying-PCA-and-t-SNE-on-images-and-visualizing.
Applying PCA and t-SNE on images and visualizing Using Python 3. 
In this we will first take 2 images and Normalize the data
We will put them in a pandas dataframe with 5 features x,y,r,g,b.
The x and y features are the position of the pixel relative to the top left most pixel of the image.
The r,g and b stand for the rgb values of the pixel.
the data is normalised.
We run a PCA and find the most significant components.
The 3 most significant components are then plotted.
Then we run t-SNE on the same normalized data with n = 2 components for 3 different perplexities(5,30,50).
