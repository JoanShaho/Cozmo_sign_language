# Cozmo_sign_language

This is a program that uses Anki's Cozmo robot to store hand sign images, train a Convolutional Neural Network to predict the correct sign, and actuall guess given the image he sees.

- Current issues:
    1. The image that cozmo uses is unprocessed which results in cozmo not being able to associate the hand gesture with a sign but the            entire image. This results in incorrect guesses if the background is not exactly the same.
    2. The loading process is slow and not very efficient

- Possible solutions:
    1. Take a new set of pictures while wearing a black glove. This can help find the hand gesture within the image since the pixels that          correspond to the hand gesture will have a low grayscale value.
    2. Find more efficient ways to load the data
