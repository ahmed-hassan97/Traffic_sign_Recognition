# Traffic_sign_Recognition
using cnn in classify between 43 kind from traffic sign



i used data from kaggle 

i linked it to google colab 
using api from dataset 

build convolution neural network to classify between images 
output is softmax to  43 kind from traffic sign

link data on kaggle
https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

#deep learning
#CNN
#open cv

how to link data from kaggle to colab 
steps:>>>>

1- install kaggle on colab
        using this  command  !pip install kaggle
  
2- go to your account on kaggle 
       and download expire api token (this file is .json)

3-download this file(.json) on local machine 

4-upload this file to your google colab
       
3- execute this command
      !mkdir -p ~/.kaggle
      !cp kaggle.json ~/.kaggle/
      

4-change permission 

        execute this command 
       !chmod 600 ~/.kaggle/name_file_.json
       
5-from dataset copy api to dataset

 for example 
        !kaggle datasets download -d meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

finally:
     
     unzip file::>>>>>
     
     from zipfile import ZipFile
     file_name = "file_link_from_kaggle.zip"

    with ZipFile(file_name, 'r') as zip:
    zip.extractall()
    print('done')


i hope this document  will be useful

thanks 
ahmed hassan
