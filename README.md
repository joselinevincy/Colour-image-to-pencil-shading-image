COLOR IMAGE TO PENCIL SHADING IMAGE

# STEP BY STEP PROCEDURE..

# 1. cv2.cvtColor:
converts the image to gray scale
# 2. 255-gray_image:
inverts the grayscale image to create a negative
# 3. cv2.GuassianBLlur:
blurs the inverted image to soften the lines
# 4. 255-blurred_image:
inverts the blurred image
# 5. cv2.divide:
blends the grayscale with the inverted blurred image to produce a pencil sketch effect
