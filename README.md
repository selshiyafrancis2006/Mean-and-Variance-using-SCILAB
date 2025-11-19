<h1>MEAN-AND-VARIANCE-USING-SCILAB</h1>

AIM: To write a program for mean, variance and cross correlation in SCILAB and verify the output.

EQUIPMENTS Needed

· Computer with i3 Processor · SCI LAB

Algorithm

Define the Function: Specify the function you want to simulate. For example, f(x)=sin⁡(x)f(x) = \sin(x)f(x)=sin(x) or any other function.

Generate Sample Points: Decide on the range and the number of sample points. Generate these sample points within the desired range.

Evaluate the Function: Compute the function values at each of these sample points.

Compute Mean, Variance and Cross Correlation: Use Scilab's functions to calculate the mean and variance of the computed function values.

Display Results: Output the computed mean variance and Cross Correlation

PROCEDURE

· Refer Algorithms and write code for the experiment.

· Open SCILAB in System

· Type your code in New Editor

· Save the file

· Execute the code

· If any Error, correct it in code and execute again

· Verify the generated results

PROGRAM

clear; clc; clear;

//Mean Value function X=f(x),

z=13*(1-x)^2,//Marginal Probability Density Function X=x*z

endfunction a=0;

b=1;

EX=intg(a,b,f);//Mean value of X function Y=c(y)

z=13*(1-y)^2,//Marginal Probability Density Function Y=y*z

endfunction EY=intg(a,b,c);//Mean value of Y disp(EX,"i)Mean of X =") disp(EY," Mean of Y =")



Variance

function X=g(x),

z=13*(1-x)^2,//Marginal Probability Density Function X=x^2*z

endfunction a=0;

b=1;

EX2=intg(a,b,g); function Y=h(y)

z=13*(1-y)^2,//Marginal Probability Density Function Y=y^2*z

endfunction EY2=intg(a,b,h);

vX2=EX2-(EX)^2;//Variance of X vY2=EY2-(EY)^2;//Variance of Y disp(vX2,"ii)Variance of X"); disp(vY2," Variance of Y");

Cross Correlation


x= input("type in the reference sequence="); y= input("type in the second sequence="); n1=max(size(y))-1;

n2=max(size(x))-1;

r=corr(x,y,n1);

plot2d3('gnn',r);
OUTPUT:

i) Mean of X = 1.0833333 Mean of Y = 1.0833333

ii) Variance of X -0.7402778 Variance of Y -0.7402778

Cross Correlation

Type in the reference sequence = [1 2 3 4 5 6 7 8]

Type in the second sequence = [2 1 3 5 6 3 5 9]

<img width="901" height="494" alt="image" src="https://github.com/user-attachments/assets/d6d82924-9110-4d8f-9b35-5e0e338519c8" />

calculation:

<img width="578" height="925" alt="image" src="https://github.com/user-attachments/assets/06fb0039-7313-4141-8431-172da421ab16" />
<img width="1029" height="915" alt="image" src="https://github.com/user-attachments/assets/9776b82a-3de2-4e6b-aff5-03a5d333f3f9" />
<img width="771" height="894" alt="image" src="https://github.com/user-attachments/assets/b361e06e-7a33-4a33-b316-77a5462edf65" />

RESULT:

Thus the mean , variance and cross correlation are executed in Scilab and output is verified.
