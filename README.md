# CycleGAN-based-Image-Transformation-for-Severe-Weather-Self-Driving

## Result demo
![image](https://user-images.githubusercontent.com/36163586/207711648-54be07f0-b56e-41ef-8a70-ae67c267b196.png)
![image](https://user-images.githubusercontent.com/36163586/207711662-6dde2eef-f828-4269-baa1-730abafe7185.png)

## Install requirements
- jupyter notebook
- tensorflow
- numpy
- matplotlib
- IPython.display
- glob
- sys

## How to run it?
- Replace file_* to your own file path. File_foggy = Dom A, file_city = Dom B
- Run each block in jupyter notebook

## Load your model
- Replace or rewrite 'g_model_AtoB.hdf5', 'g_model_BtoA.hdf5','c_model_AtoB.hdf5','c_model_BtoA.hdf5' as your checkpoints file.
