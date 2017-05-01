# lionfish
Lionfish Identifier 


Harr Cascade classifier trained with about 70 positive images


Install opencv:

` brew tap homebrew/science
 brew install opencv`

run:

`python detect_lionfish.py -i ./images/image_01.jpg`

Parameters for the multi scale detector:
  min size: Minimum possible object size. Objects smaller than that are ignored.
  neighbors: Parameter specifying how many neighbors each candidate rectangle should have to retain it.
  scale factor: Parameter specifying how much the image size is reduced at each image scale.
