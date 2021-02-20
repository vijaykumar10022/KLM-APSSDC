# KLM-Python


# Taks(Day-1)

 ## Task -1
 
 Test case -1:
  
 input:3 4 1
 
 hint:3x+(x+z)*(x+y+z)
      
      9+(4)*(8)
      
      9+32
      
      41
      
 output:41


## Task -2

TestCase -1

input:8 3

hint :a*pi +(2+b)+10

output:40.132741228718345

TestCase -2

input:2 3.12

hint :a*pi +(2+b)+10

output:21.403185307179587

## Task -3

Testcase -1
 input:8 2 3
 
  hint:a**b**c
  
 output:16777216
 
TestCase -2

input:2 9 2

hint:a**b**c

output:2417851639229258349412352

======================================================================================================
# Task on IF ..IF Else.. IF ELIF
# ROY AND PROFILE PICTURE
Roy wants to change his profile picture on Facebook. Now Facebook has some restriction over the dimension of picture that we can upload.
Minimum dimension of the picture can be L x L, where L is the length of the side of square.

Now Roy has N photos of various dimensions.
Dimension of a photo is denoted as W x H 
where W - width of the photo and H - Height of the photo

When any photo is uploaded following events may occur:

[1] If any of the width or height is less than L, user is prompted to upload another one. Print "UPLOAD ANOTHER" in this case.
[2] If width and height, both are large enough and 
(a) if the photo is already square then it is accepted. Print "ACCEPTED" in this case.
(b) else user is prompted to crop it. Print "CROP IT" in this case.

(quotes are only for clarification)

Given L, N, W and H as input, print appropriate text as output.

**Input:**
First line contains L.
Second line contains N, number of photos.
Following N lines each contains two space separated integers W and H.

**Output:**
Print appropriate text for each photo in a new line.

**Constraints:**
1 <= L,W,H <= 10000
1 <= N <= 1000

 

**SAMPLE INPUT**

180

3

640 480

120 300

180 180

 

SAMPLE OUTPUT

CROP IT

UPLOAD ANOTHER

ACCEPTED

Time Limit:	
