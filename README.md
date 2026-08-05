EXP2: Introduction to salt pepper noise (used for grayscale image)
[numpy, cv2 and matlplotlib] 

1. source of salt pepper noise
2. nature of noise - its an additive noise, easy to remove (multiplicative noise is difficult)
3. experiment with moving window - to filter the noise

eg: prob= 0.2
	0.1 - salt
	0.1 - pepper
	0-255

np.random.rand((603,1200)) - 2D bcz image is 2D
random < prob/2 = 0
random > 1 - prob/2 = 255

EXP3: Mean and median filter for image noise removal with different size and kernal size
