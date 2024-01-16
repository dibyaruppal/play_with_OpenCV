## TASK 1.   Bounding Box around Foreground Object:

  To draw a bounding box around the foreground object using OpenCV, I employed the following steps:
  
      • Image Preprocessing: Load the image and apply necessary preprocessing steps such as 
          1. Transformation of the original image to grayscale image.
          2. Addition of blur using Gaussian Blur method.
          
      • Foreground Extraction: Use a suitable method to extract the foreground from the image. This could be achieved through techniques like thresholding or background subtraction.
          1. Conversion of grayscale image into binary image
          
      • Contour Detection: Utilize OpenCV's contour detection functions to find contours in the foreground image.
      
      • Bounding Box Calculation: Calculate the bounding box coordinates based on the detected contours.
      
      • Drawing the Bounding Box: Draw the calculated bounding box on the original image.
      
  **Result**: The final output is an image with a bounding box delineating the foreground object, providing a clear visual representation of its spatial extent.
  


## TASK 2.   Grayscale Conversion and Canny Edge Detection:
  
  For converting the image to grayscale and detecting edges using the Canny edge detection method:
  
      • Grayscale Conversion: Transform the original image to grayscale using OpenCV's cvtColor function.
      
      • Canny Edge Detection: Apply the Canny edge detection algorithm to highlight edges in the grayscale image. Adjust parameters such as the low and high thresholds to control the sensitivity of edge detection.
      
      • Visualization: Display the grayscale image and the corresponding edges to observe the effect of the Canny edge detection.
      
  **Result**: The output consists of two images - one in grayscale and another highlighting the detected edges, offering insights into the image's structural features.
  


## TASK 3.   K-means for Segmentation on RGB Image:

  To perform segmentation using K-means clustering on the RGB image:
  
      • Flatten Image: Flatten the RGB image to a 2D array, making it compatible with the K-means algorithm.
      
      • K-means Clustering: Apply the K-means algorithm to segment the flattened image into a specified number of clusters. In this case, the clusters represent different segments in the image.
      
      • Reshape and Display Segmented Image: Reshape the clustered image back to its original dimensions and display the segmented regions, each represented by a distinct colour.
      
  **Result**: The segmented image highlights different regions based on colour clusters, effectively separating distinct objects or areas within the original RGB image.
  

  
## Conclusion:
The application of these OpenCV-based image processing techniques allows for a comprehensive analysis of images, including the identification of foreground objects, detection of edges, and segmentation based on colour clusters. These methods provide valuable insights for tasks such as object recognition, feature extraction, and image understanding.
