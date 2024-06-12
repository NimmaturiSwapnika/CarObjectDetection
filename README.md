# CarObjectDetection
Initially used VGG-16, replaced fully connected layers with custom bounding box head using sigmoid activation for colored, grayscale, &amp; green channel images. Green channel performed better, but accuracy was still at 20%. Switching to Random Forest with 30 feature spaces improved accuracy to 50%, highlighting the critical role of feature selection.
