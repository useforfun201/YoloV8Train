# how to filter class
    detections = detections[(detections.class_id == 0) & (detections.confidence > 0.5) & mask]

