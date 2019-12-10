# Tree search parameters  
c1:.5  
c2:.01  
discount factor: 0.9  

# Neural network parameters

Frontend: Keras
Backend: PlaidML
Type: Convolutional neural network
## Layers: 
'''
conv(32, kernel_size(7,7),activation='relu')
dense(32,activation='relu')
dense(32,activation='relu')
dense(32,activation='relu')
dense(3,activation='softmax')
'''
Optimizer=SGD
Loss=categorical_crossentropy

# Hardware

CPU: Ryzen 1600x, 6 core, 12 thread
GPU: AMD RX 480
RAM: 16gb

