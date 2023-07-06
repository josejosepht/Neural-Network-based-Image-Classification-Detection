# Neural-Network-based-Image-Classification-Detection
The tasks performed in this Jupyter notebook include implementing the AlexNet architecture in PyTorch, modifying the network to handle smaller images while keeping the model parameters constant, implementing the BasicBlock for ResNet18 and ResNet34 networks, exploring data augmentations to improve generalization, and analyzing the usefulness of downsampling and upsampling within the network. The notebook also examines whether the model is overfitting by analyzing the train and validation losses in TensorBoard. Overall, the tasks revolve around neural network architecture design, image processing, data augmentation, and model evaluation.


*  Tensorboard plots of the train and validation losses: (no. of epochs on x-axis, y axis represents number of epochs completed(for first plot of epochs), the accuracy values(for train_acc and val_acc) and the loss values(for train_loss and val_loss) respectively)

![image](https://github.com/josejosepht/Neural-Network-based-Image-Classification-Detection/assets/97187460/380dea1f-3054-4368-8c0a-05a9d390c9f2)

![image](https://github.com/josejosepht/Neural-Network-based-Image-Classification-Detection/assets/97187460/16e712a1-2454-4f8b-9da9-adb70a805b0d)

![image](https://github.com/josejosepht/Neural-Network-based-Image-Classification-Detection/assets/97187460/82cafc39-5f06-4534-9ab7-b0575db4b21c)

![image](https://github.com/josejosepht/Neural-Network-based-Image-Classification-Detection/assets/97187460/e28eb447-3dc8-48f9-b08c-83bdb6414b09)

![image](https://github.com/josejosepht/Neural-Network-based-Image-Classification-Detection/assets/97187460/ff1dbbe2-b282-4059-a4cd-37fd6117f8df)

## Inference:
Here, the plots show that training loss is steadily decreasing of the order of 10e-3 while the validation accuracy remains at ~70%. Hence, it does not overfit but it requires more training epoch owing to a slow learning network.
