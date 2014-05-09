#!/usr/bin/python
#!encoding: UTF-8

import pylab as dibujo

x= [0.0001,0.00001,0.000001,0.0000001,0.00000001]
y1= [28.57,100,100,100,100]
y2= [0,14.29,71.43,28.57,100]
y3= [0,0,28.57,100,100]
y4= [0,0,0,14.29,85.71]
y5= [0,0,14.29,71.43,14.29]
y6= [0,0,14.29,14.29,71.43]
y7= [0,0,0,0,28.57]

#p1= dibujo.subplot(211) #dos filas, una columna y voy a hacer el primer dibujo
dibujo.title('Porcentajes de fallo')
dibujo.plot (x, y1, marker='*', linestyle=':' , color='r', label='10') 
dibujo.plot (x, y2, marker='o', linestyle='-.' , color='b', label='50') 
dibujo.plot (x, y3, marker='p', linestyle='-' , color='m', label='100') 
dibujo.plot (x, y4, marker='s', linestyle='--' , color='g', label='150') 
dibujo.plot (x, y5, marker='+', linestyle=':' , color='c', label='500')
dibujo.plot (x, y6, marker='.', linestyle='-.' , color='y', label='550') 
dibujo.plot (x, y7, marker='^', linestyle='-' , label='1000') 
#tambien se pueden poner como estilo de linea los siguientes: --, -., -
#y como colores normalmente la inicial del color en ingles:r,m,b,g,c,y
#el marker señala los pares (x,y), también acepta formatos: o,s,p, *,+,.,^
dibujo.legend()
#dibujo.xlim(0,8) #me dibuja de 0 a 7 en el eje x, si quiero que solo salgan los numeros de 1 a 4 que es donde se mueve la x cojo la funcion siguiente:
#dibujo.xticks(x)
#p2= dibujo.subplot(212) #dos filas, una columna y hago el segundo dibujo
#dibujo.plot (x, y, marker='s', linestyle='-' , color='g', label='linea4') 


#dibujo.xlabel('Intervalos')
#dibujo.ylabel('Tiempo en segundos')



dibujo.show()

