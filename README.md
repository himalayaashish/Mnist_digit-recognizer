# Mnist_digit-recognizer

### A simple CNN model with 98% accuracy





Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param    
=================================================================
conv2d (Conv2D)              (None, 24, 24, 8)         208       
max_pooling2d (MaxPooling2D) (None, 12, 12, 8)         0         
dropout (Dropout)            (None, 12, 12, 8)         0         
conv2d_1 (Conv2D)            (None, 12, 12, 16)        1168      
max_pooling2d_1 (MaxPooling2 (None, 6, 6, 16)          0         
dropout_1 (Dropout)          (None, 6, 6, 16)          0         
flatten (Flatten)            (None, 576)               0         
dense (Dense)                (None, 256)               147712    
dropout_2 (Dropout)          (None, 256)               0         
dense_1 (Dense)              (None, 10)                2570      
=================================================================
Total params: 151,658
Trainable params: 151,658
Non-trainable params: 0
