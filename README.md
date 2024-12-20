This project aims to develop a machine learning system for autonomous rock classification on Mars, enhancing rover efficiency by minimizing Earth-Mars communication delays and enabling independent exploration. The classification of Martian rocks holds significance in understanding planetary geology, past environments, and potential signs of life.

The dataset comprises three main categories of rocks—metamorphic (marble, quartzite), sedimentary (coal, limestone, sandstone), and igneous (basalt, granite). Preprocessing included aspect ratio calculation, duplicate removal, image resizing, and normalization. To improve model performance and address class imbalance, data augmentation was applied to all three categories, preserving their distinct characteristics.

The modeling approach followed a step-by-step process:

A simple CNN model was initially used as a baseline to test classification feasibility.
Transfer learning was implemented using pre-trained architectures such as MobileNetV2 and VGG16 to leverage existing feature extraction capabilities.
A custom handmade model was designed specifically for the dataset's characteristics.
By maintaining the three primary rock categories throughout, the project ensures robust classification tailored to Martian exploration needs. This innovative approach demonstrates the potential of machine learning in planetary science and autonomous rover operations.
