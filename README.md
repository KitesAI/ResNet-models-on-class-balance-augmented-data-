# ResNet-models-on-class-balance-augmented-data-

- ResNet50 has a accuracy of **46.31%** on completely un-seen data.
- ResNet18 has a accuracy of **52.63%** on completely un-seen data.
- ResNet18_Reg includes the regularization techniques (L2, Dropout, Batch norm) and scheduler learning rate. In the model training, the dataset used: Training - balanced augmented data, Validation - 150 out of remaining 190 non-augmented data, Test - 40 remaining.
- ResNet18_croped_Simple_Augmentation: **Dataset**- normal Augmentation on Croped images, 3 class (4Z, 5K, 6D), Number of images: (train-600, val-180, test-27). **Results**: 88%.
                                       

**Remarks**: The model will perform well on un-seen data, if we will provide a good amount of train dataset to the model. 
         The augmentation method is incressing the size of data set, but they generated images are similar, resulting "Overfitting". 

**Results for ResNet18**:

![R18_p](https://github.com/KitesAI/ResNet-models-on-class-balance-augmented-data-/assets/147130999/b0beade8-e312-4082-a6c4-6fb289d870cf)

![R18_c](https://github.com/KitesAI/ResNet-models-on-class-balance-augmented-data-/assets/147130999/47a50632-33f7-436d-9031-68fcc33520ae)


**ResNet18_croped_Simple_Augmentation**

![Conf_1](https://github.com/KitesAI/ResNet-models-on-class-balance-augmented-data-/assets/147130999/e2533d7d-84ad-43a1-b31e-076da9f00e5d)
