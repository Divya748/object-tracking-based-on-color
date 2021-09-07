# object-tracking-based-on-color
object tracking based on color using HSV (Hue Saturation Value)



Formulas used here
  - Minimum Enclosing Circle
      - ((x, y), radius) = cv2.minEnclosingCircle( countourArea )
  - Moments to find center of the Area
      - Image moments help you to calculate some features like center of mass of the object, area of the object etc.
      - M = cv2.moments(c)
      - center = (int(M["m10"] / M["m00"]), int(M["m01"] / M["m00"]))

















