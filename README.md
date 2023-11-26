Step 1. Install dependencies and add virtual environment to the Python Kernel.

Step 2. Install various python libraries that is being used in making deep learning models like np, pd, scipy etc.

Step 3. Now analysis the model and check which YOLO algorithm will be suitable for this whether it will be V4 or V8 algorithm.

Step 4. Begin working on those algorithms systematically.

Step 5. Start by applying filter boxes on the objects seen in the image captured by our model and compute box scores, threshold score accordingly.

Step 6. Apply IOU (intersection over union) on that particular box and find out whether it is greater than the threshold value we set it for.

Step 7. Apply Non-max Suppressionn over the overlapping boxes so that the box with the highest score came into picture and we would continue on that one.

Step 8. Now the important encoding part come into picture which is the most important part of the YOLO algorithm which is used for filtering  boxes up for prediction.

Step 9. We should always compare our model with already pretrained model for better analysis of our model.
