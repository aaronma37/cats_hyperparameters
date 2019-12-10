# Tree search parameters  
c1:.5  
c2:.01  
discount factor: 0.9  
max_depth = 10
# Neural network parameters  
Frontend: Keras  
Backend: PlaidML  
Type: Convolutional neural network  

Optimizer=SGD  
Loss=categorical_crossentropy  

## Layers:   
- conv(32, kernel_size(7,7),activation='relu')  
- dense(32,activation='relu')  
- dense(32,activation='relu')  
- dense(32,activation='relu')  
- dense(3,activation='softmax')  
  

# Hardware
CPU: Ryzen 1600x, 6 core, 12 thread  
GPU: AMD RX 480  
RAM: 16gb  

