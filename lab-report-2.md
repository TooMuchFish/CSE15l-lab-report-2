# Name : Shaodong Shan
# Course: CSE 15L
Date: April 21, 2022
 
This is the second lab report in my course of CSE 15L
![welcome](https://as2.ftcdn.net/v2/jpg/00/74/04/71/1000_F_74047191_MmYUxOjF0TxwND45VyyqFM2kMsr8hzGt.jpg)
Within this lab report, I'll introduce three code changes that in my group in order to introduce bugs fix by following steps.
* A screenshot of the code change 
* Link to the test file for a failure-inducing input
* The symptom of that failure-inducing input
* Relationship between the bug, the symptom, and the failure-inducing input
 

# Code 1. 
 ![code1](https://user-images.githubusercontent.com/103075501/166324169-77505d26-8a9f-486c-9d70-e9c54c063282.jpg)


# [link](https://github.com/eambrosio27/markdown-parser/commit/03aca9bffbf24720050087e71f6bf7b4e0b524c6)  to the Code 1 file for failure inducing input
<img width="854" alt="15lrep2a1" src="https://user-images.githubusercontent.com/103075501/164575869-26fb26bf-9d5b-426f-bf11-feb383cb9aed.png">
 
  Since there is an image link, and its code is ` ![Image](link.png)`, an error will take place and the system will run an infinity loop. The expected output for this inducing input should be `[]`.
 
 
 
 
# Code 2.
<img width="994" alt="15lrep2b2" src="https://user-images.githubusercontent.com/103075501/164576663-9c52ed75-ebb8-4506-b9f9-480473f125b0.png">
 
# [link](https://github.com/nidhidhamnani/markdown-parser/commit/f645d8519f425b1e8720559a3622073f09c615dc)   to the Code 2  file for failure inducing input
<img width="818" alt="15lreo2b1" src="https://user-images.githubusercontent.com/103075501/164576236-216e894b-5092-4ca8-959f-38964bdd8f2b.png">
  
  There exist an error in ` [link1]https://something.com ` becasue since we want to give a hyperlink to transfer to the specifed website, we need to use the format that ` [link1](https://something.com) `, and the error is that we need a pair of parentheses to contain the website address.



# Code 3.
<img width="867" alt="15lrep2c2" src="https://user-images.githubusercontent.com/103075501/164577216-f841d46d-e36c-449b-a5d9-acce239639d6.png">
 
# [link](https://github.com/TooMuchFish/markdown-parser/blob/main/test3.md)   to the Code 3 file for failure inducing input

<img width="730" alt="15lrep2c1" src="https://user-images.githubusercontent.com/103075501/164576597-d9631d6c-f08e-4428-91c5-fb70ef8a2be0.png">
 
 For this code3, since I don't find more cases from [shared document](https://docs.google.com/document/d/1TDcdY4AVA8pRi1ITJ67m6TBaApn40q8BkqqqwC-LpWU/edit#heading=h.s8u88f6kqofr) in my group, then I made one myself. Its original code is
 >
  `[a link]                (youtube.com)`, this is wrong because it has too many spaces between the signal "]" and "(", these spaces will made a infinite loop error in our system. So the correct format should be `[a link](youtube.com)`.
 
 
 
 
# This is end of my lab2 report, thanks for your watching.
![thanks](https://user-images.githubusercontent.com/103075501/162642394-44533b1f-86e6-4dd4-ac23-0c8392cfdbbb.jpg)
 
 
 
