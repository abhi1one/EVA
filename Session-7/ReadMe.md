# Session7-Task 1

Check this paper out: 

https://arxiv.org/pdf/1409.4842.pdf (Links to an external site.)Links to an external site.



1. They mention on page 6, that the RF is 224x224. 

2. Use the formulas and show the calculations

   ![3](C:\Users\home\Desktop\Abhishek-Code\EVA\Session-7\32.png)

   Receptive Field Calculation

   ![1](C:\Users\home\Desktop\Abhishek-Code\EVA\Session-7\13.png)

3. Submit Calculations in the readme file



## Calculations

#### Layer 1:

Base 

in=224

out=224

r=1

j=1



#### Layer 2:

Convolution k=3, s=2, p=1

out = (224+2*1-3)/2 +1 = 112

j = 1*2 = 2 

r = 1+(3-1)*1 = 3



#### Layer 3

Maxpooling: k=2, s=2 p=0

out = (112+2*0-3)/2+1 = 56

j = 2*2 = 4

r = 3+(2-1)*2 = 5



#### Layer 4

Convolution k=3, s=1, p=1

out = (56+2*1-3)/1+1 = 56

j = 4*1 = 4

r = 5+(3-1)4 = 13