# Traffic Sign classification for Autonomous Vehicles    

The project designed and implemented a Sequential model leveraging cascading convolutional layers with varying filter sizes. The architecture comprised 16 filters of size 3x3, followed by 32 filters of 3x3, then 64 filters of 3x3, and finally, 128 filters of 3x3. 

Interspersed with the convolutional layers were max-pooling layers of size 2x2, which served to downsample the feature maps, reducing computational complexity while preserving essential information. Additionally, batch normalization was incorporated into the model to improve stability during training by normalizing the activations of each layer.

The model was trained on the German Traffic Sign Recognition Benchmark (GTSRB) dataset. This dataset consists of thousands of images spanning various classes of traffic signs commonly encountered on roads.

Throughout the training process, optimization techniques were employed, including fine-tuning hyperparameters, adjusting learning rates, and employing data augmentation strategies to enhance the model's generalization capabilities.

Upon completion of training, the model achieved an impressive accuracy of 98.48% on the GTSRB dataset.

In the context of traffic sign recognition, the described approach can be deployed in autonomous vehicles to enable real-time detection and classification of traffic signs from onboard cameras. By analyzing the input video stream, the model can identify various types of traffic signs such as speed limits, stop signs, yield signs, and directional arrows. This information is then used by the vehicle's decision-making system to adjust its speed, change lanes, yield to other vehicles, and navigate intersections safely. Overall, the integration of computer vision techniques for traffic sign recognition plays a crucial role in enhancing the perception capabilities of autonomous vehicles and ensuring safe and efficient operation on the roads.
