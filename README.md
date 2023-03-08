• • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • 
# pix2pix_on_colab_and_gdrive
train custom pix2pix model on google colab using dataset from google drive.



• • • • • • • • • • • • • • • • • • •  Condictions for training as as below • • • • • • • • • • • • • • • • 

1 - Plase all your training data in given below folders in your google drive.

2 - have all the files with similar resolution, images with different resolution will cause in getting error.

3 - Then follow the steps given below.


• • • • • • • • • • • • •  You have to follow these steps to reproduce the results • • • • • • • • • • • • •

STEP 1 : goto your google drive and make a folder `database_v1`

STEP 2 : inside the `database_v1` folder make these five other folders : inputs, outputs, train, test, val

STEP 3 : run `pix2pix_submission_file.ipynb` jupyter notebook in your google colab and when asked to give permission to your google drive accept the permission.

STEP 4 : Run rest of the jupyter notebook and wait for the model to finish the training.

STEP 5 : Give input images at the final block of the jupyter notebook to generate from your given input image.

• • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • • 
