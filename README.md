# House / Apart / Indoor Classification

## Presentation

Tool to recognize real estate images : distinguish houses, aparts and indoor/trash images

## Usage

Call "classifHouseApart" function :
* Input : list of images urls
* Output : 2 lists of images urls : apart ones and house ones

Several cases :
* No outdoor images : print "no outdoor images" and gives you 2 empty lists

Displays also the predictions results and their pictures

## Command

```python
apart,house = classifHouseApart(listImagesUrls)
```

## Example

<img src="https://github.com/Ainara2828/House-Apart--CNN/blob/master/example.png" alt="drawing" width="600"/>
