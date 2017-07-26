# Face++ to identify a person
#download github code
```
$git clone https://github.com/lbaitemple/Summer_2017-.git
$cd Summer_2017-
```


#install opencv & other requierments
```
$ sudo apt-get update
$ sudo apt-get upgrade

$sudo apt-get install python2.7-dev python3-dev
$sudo pip install requests
```
#check to see if opencv has installed correctly
```
$python
>>> import cv2
>>> print(cv2.__version__)
```
#create two folders named /test/pictures_faces inside /Summer_2017- , and put all of your pictures in it 
```
$ mkdir test
$ cd test
$ mkdir pictures_faces
$ cd ..
```

# how to run the code
```
$ python picture_comparsion4.py
```
