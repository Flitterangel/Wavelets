# Representation Of Variance
Given an auxiliary function v=v(x): R->R;k>=0

with v(x)= 0 for x<=0,  v(x)= 1 for x>=0

For example,v(x)= 0 for x<=0

v(x)= 10x^3-15x^4+6x^5, for 0<=x<=1

v(x)= 1, for x>=1

v(1 − x)=1-v(x)

#Fourier Transform of the Haar Wavelets
w = 0:0.01:12*pi;

haar = ((4*(sin(w/4)).^2))./((sqrt(2*pi)).*abs(w));

