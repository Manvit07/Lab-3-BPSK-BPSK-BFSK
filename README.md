# Lab-3-BPSK-BPSK-BFSK
clc;
clear all;
fm = 5;
am = 5;
t = 0:0.001:1;
a = 5;
m = a*square(2*pi*fm*t);
subplot(3,1,1);
plot(t,m);
grid on;
%sinosidal wave
c = a*sin(2*pi*10*t);
subplot(3,1,2);
plot(t,c,'k-');
title('carrier signal');
%BPSK
x = m.*c;
subplot(3,1,3);
plot(t,x,'k-');
title('BPSK');
Clc;
Clear all;
Close all;
Am=1;
Ac=4;
T=00:0.001:2;
Fc=15;
Fm=2
Kf=1;
M=am*square(2*pi*fm*t)
Subplot(3,1,3)
Plot(t,m)
M=am*square(2*pi*fc*t)
Subplot(3,1,2)
Plot(t,c)
