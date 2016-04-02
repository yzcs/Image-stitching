# Image-stitching
1. Load both images, convert to double and to grayscale. 
% 2. Detect feature points in both images. 
% 3. Extract fixed-size patches around every keypoint in both images, and 
% form descriptors simply by "flattening" the pixel values in each patch to 
% one-dimensional vectors. 
% 4. Compute distances between every descriptor in one image and every descriptor in the other image. 
% 5. Select putative matches based on the matrix of pairwise descriptor 
% distances obtained above. 
% 6. Run RANSAC to estimate (1) an affine transformation and (2) a 
% homography mapping one image onto the other. 
% 7. Warp one image onto the other using the estimated transformation. 
% 8. Create a new image big enough to hold the panorama and composite the 
% two images into it. 
Final project for Industrial vision course at MUN
