# Lab 1 — Checkpoint Answers

## Checkpoint Questions

### 1. Why is image classification insufficient when an image contains multiple objects?
Image classification assigns a label to the entire image. It does not identify the location of each object independently.

### 2. What does object detection add to image classification?
Object detection identifies objects and locates them using bounding boxes.

### 3. Can semantic segmentation distinguish between individual objects of the same class?
Semantic segmentation assigns a class to each pixel but does not distinguish separate instances of the same class. Instance segmentation is used to separate individual instances.

### 4. Why are keypoints useful for human pose estimation?
Keypoints represent important body landmarks. Their positions help estimate body posture and movement.

## Final Comparison

| Task | Main Purpose | Output |
|---|---|---|
| Image Classification | Classify an image | Image label |
| Object Detection | Locate and classify objects | Bounding boxes and labels |
| Semantic Segmentation | Classify image pixels | Pixel-level class masks |
| Keypoint Detection | Locate important landmarks | Keypoint coordinates |

## Additional Questions

### 1. Which task assigns one label to an entire image?
Image Classification.

### 2. Which task identifies object locations using bounding boxes?
Object Detection.

### 3. Which task assigns labels at the pixel level?
Semantic Segmentation.

### 4. Which task identifies body landmarks?
Keypoint Detection.

### 5. Do keypoints change when a person changes pose?
Yes. The positions and configurations of keypoints change with the person's pose.

### 6. Why is annotation consistency important?
Consistency improves dataset quality, reduces labeling errors, and helps make annotations more reliable.
