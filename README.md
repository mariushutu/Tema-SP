# Tema-SP

exemplu5-c):

F=50;
Q=20;
t=0:0.001:0.2;
s=2*sin(2*pi*F*t);
z=2*cos(2*pi*Q*t);
plot(t,s,t,z,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid


TEMA DE CASA:
-EXERCITIUL 1:

Pentru rezolutie temporara de 2ms:
F=5;
T=1/F;
x=[0.25];
d=dutycycle(x, T);
t=0:0.002:2;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-1 0.5]);

Pentru rezolutie temporara de 20ms:

F=5;
T=1/F;
x=[0.25];
d=dutycycle(x, T);
t=0:0.02:2;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-1 0.5]);

Pentru rezolutie temporara de 200ms:

F=5;
T=1/F;
x=[0.25];
d=dutycycle(x, T);
t=0:0.2:2;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-1 0.5]);


-----------------------------------------------------------------------------------------------------


-EXERCITIUL 2:

Pentru rezolutie temporara de 2ms:

F=2;
t=0:0.002:5;
s=sawtooth(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-2 1]);

Pentru rezolutie temporara de 20ms:

F=2;
t=0:0.02:5;
s=sawtooth(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-2 1]);

Pentru rezolutie temporara de 200ms:

F=2;
t=0:0.2:5;
s=sawtooth(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-2 1]);


------------------------------------------------------------------------------------------------------

-EXERCITIUL 3:

Pentru rezolutie temporara de 2ms:

F=40;
t=0:0.002:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-1 1]);

Pentru rezolutie temporara de 2ms:

a)

F=40;
t=0:0.002:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-3,-1, 1, 3]);

b)

F=40;
t=0:0.002:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-3,-1, 1, 3]);

c)

F=40;
t=0:0.002:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-5,-3,-1,1,3,5]);

d)

F=40;
t=0:0.002:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-7,-5,-3,-1,1,3,5,7]);

Pentru rezolutie temporara de 20ms:

a)

F=40;
t=0:0.02:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-3,-1, 1, 3]);

b)

F=40;
t=0:0.02:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-3,-1, 1, 3]);

c)

F=40;
t=0:0.02:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-5,-3,-1,1,3,5]);

d)

F=40;
t=0:0.02:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-7,-5,-3,-1,1,3,5,7]);

Pentru rezolutie temporara de 200ms:

a)

F=40;
t=0:0.2:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-3,-1, 1, 3]);

b)

F=40;
t=0:0.2:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-3,-1, 1, 3]);

c)

F=40;
t=0:0.2:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-5,-3,-1,1,3,5]);

d)

F=40;
t=0:0.2:0.25;
s=square(F*t);
plot(t,s,'.-'), xlabel('Timp[s]'), xlabel('Tensiune[V]'), grid
xlim([-7,-5,-3,-1,1,3,5,7]);
