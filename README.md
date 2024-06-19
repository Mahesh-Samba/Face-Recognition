# Face-Recognition
Face Recognition Model using CNN
In my face recognition project, I developed a model using Convolutional Neural Networks (CNNs) with a dataset stored in a .npz file format. The project began by loading and visualizing the images to understand the data distribution and characteristics. Afterward, I split the dataset into training and testing sets to ensure the model's performance could be properly evaluated.

For the CNN architecture, I utilized the Keras Sequential API, which allowed for the straightforward construction of a layered model. The CNN included several convolutional layers for feature extraction, followed by pooling layers to reduce dimensionality, and dense layers for classification. The final layer used a softmax activation function to output the probabilities for each class.

To train the model, I employed categorical cross-entropy as the loss function, suitable for multi-class classification tasks. The Adam optimizer was chosen for its efficiency and adaptive learning rate capabilities, which helped in achieving faster convergence.

During the training phase, I monitored the model's accuracy and loss on both training and validation sets to avoid overfitting. Data augmentation techniques, such as rotation, flipping, and zooming, were applied to artificially expand the dataset and improve the model's generalization ability.

The model's performance was evaluated using metrics like accuracy, precision, recall, and F1-score, ensuring a comprehensive understanding of its effectiveness. The resulting face recognition model demonstrated high accuracy in identifying faces, making it a valuable tool for applications in security and authentication systems.

Overall, this project highlighted the power of CNNs in image classification tasks, and the importance of proper data handling, architecture design, and training techniques in building an effective face recognition system.
