# Code for LCDD Generation

## 0. Prerequisites
1. Matlab
2. Our all GT images are from [Google Drive Here](https://drive.google.com/file/d/1tfeBnjZX1wIhIFPl6HOzzOKOyo0GdGHl/view) 
3. Use monodepth2 to generate depth maps from GT images to render "haze".
3. put the two folders at `$project_root/Depth` and `$project_root/Groundtruth`

## 1. Generate Datasets

1. run the following command in Matlab console: 
```
>> generate_dataset
```

2. It may takes a while to render rain streaks and rain veils on these datasets. After this process is done, you will see three new folders
in this directory


  + filelists
  + train
  + val
 

3. If you put the snow degradation image into the GT image path, you will get snow-rain and snow-haze composite degradation images.
 


