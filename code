sys=tf([1 0 1.7*10^14 ],[7*10^-12 0  4.6*10^14 0 ]);
bodeplot(sys)
step(sys)
impulse(sys)
clf
t = 0:0.01:10;
u = sin(10*t);
lsim(sys,u,t) 
