
# Sea Turtle Image Segmentation Project Description

This is a document for understanding the project structure directory and how to run. The detail about this project is shown in: https://drive.google.com/file/d/1uP_XtqNk2Ip5lUMlCB5W4eFzXVqY_Jcd/view?usp=drive_link


## Authors

- [Yuchen Xie](mailto:z5515211@ad.unsw.edu.au)
- [Wenbo Chen](mailto:z5517402@ad.unsw.edu.au)
- [Haomiao Xia](mailto:z5541528@ad.unsw.edu.au)
- [Siyao Liu](mailto:z5464957@ad.unsw.edu.au)
- [Tianning Dong](mailto:z5559246@ad.unsw.edu.au)


## File structure
C:.  
│  json2png.ipynb  
│  file-structure.txt  
│  
├─Tianning Dong  
│ &emsp;     requirements.txt  
│ &emsp;     segnet.ipynb  
│      
├─Haomiao Xia  
│ &emsp;     DeepLabV3.ipynb  
│ &emsp;     requirements.txt  
│      
├─Siyao Liu  
│ &emsp;     pspnet.ipynb  
│ &emsp;     requirements.txt  
│      
├─Wenbo Chen-z5517402  
│ &emsp;     DANet.ipynb  
│ &emsp;     ECA-Unet.ipynb  
│ &emsp;     requirements.txt  
│ &emsp;     trainmetrics.txt  
│ &emsp;     trainmetrics2.txt  
│ &emsp;     trainmetrics3.txt  
│ &emsp;     UNet.ipynb  
│ &emsp;     validmetrics.txt  
│ &emsp;     validmetrics2.txt  
│ &emsp;     validmetrics3.txt  
│      
└─Yuchun Xie  
&emsp;&emsp; FCN.ipynb  
  
  The json2png.ipynb is a python function that convert coco format mask to png. In each folder, the model code and running environment are stored.
  As for FCN, the environment is Google CoLab. The trainmetrics and validmetrics store the loss during training process. As for the weight models, we uploaded them on GitHub:<https://github.com/Python2200/CV-Master-comp9517>


## Contribution

- Yuchun Xie: Literature Review, FCN model
- Wenbo Chen: Evaluation, Result, U-Net, ECA-UNet, DANet model
- Haomiao Xia: Conclusion, DeepLabV3 model
- Siyao Liu: Introduction, PSPNet model
- Tianning Dong: Discussion, SegNet model
