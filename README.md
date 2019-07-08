# House / Apart / Indoor Classification

## Presentation

Tool to recognize real estate images : distinguish houses, aparts and indoor/trash images

## Usage

Call "classifHouseApart" function :
* Input : list of images urls
* Output : 2 lists of images urls : apart ones and house ones

Other case :
* No outdoor images : print "no outdoor images" and gives you 2 empty lists

Displays also the predictions results and their pictures

## Command

```python
apart,house = classifHouseApart(listImagesUrls)
```

## Requirements

* Libraries :
  * Numpy
  * Panda
  * Keras
  * PIL
  * Matplotlib.pyplot
  * Tensorflow

* Download the two CNN models :
  * "indoor_outdoor_model.h5"
  * "house_apart_model.h5"
  
 [GoogleDrive/Models.zip](https://drive.google.com/file/d/1YHBSIFpdHSPYUZYK4SQjV1rOZRnm2YUl/view?usp=sharing) 

## Result example

<img src="https://github.com/Ainara2828/House-Apart--CNN/blob/master/example.png" alt="drawing" width="400"/>
