Parte 1. Entregar de manera ordenada Diagrama de Flujo + Solución en Python + Prueba de Escritorio

Página del libro 194

Ejercicios. 5.15

![ALGORITMIA MOMENTO 2 drawio](https://github.com/user-attachments/assets/e5850204-5631-4a2c-bca9-93fd04ac5ef5)

![image](https://github.com/user-attachments/assets/54eee4b6-91fe-404c-85e9-7da8d7601fef)

![image](https://github.com/user-attachments/assets/6bb2eba6-b1c8-44ea-ad13-41bcf082fcae)

5.16

![image](https://github.com/user-attachments/assets/793b7dad-0690-4853-8b9a-bc70d52d034b)

![image](https://github.com/user-attachments/assets/7068d233-3fd9-4878-9315-4eb736690ef3)

5.17

![2](https://github.com/user-attachments/assets/43c16ad2-c222-41fc-a852-d742d0c7e820)

![image](https://github.com/user-attachments/assets/785229c6-15de-4d2a-b81b-7e3b471a1654)

![image](https://github.com/user-attachments/assets/e2b2a6da-125f-47b5-8af8-91d4543925f7)

![image](https://github.com/user-attachments/assets/9bc45e6c-b329-47fb-b6da-038c51714c54)

5.19

![3](https://github.com/user-attachments/assets/21c092c1-5eb3-4d65-b451-eb6d4ffff537)

![image](https://github.com/user-attachments/assets/46801f79-37c6-47c2-b1d0-e3effbadd482)

![image](https://github.com/user-attachments/assets/6eda364b-84a1-4fb5-909e-c9920807d2e3)




Parte 2. Entregar de manera ordenada Análisis del problema + Pseudocodigo + Diagrama de Flujo + Solución en Python + Prueba de Escritorio

Ejercicios página Libro 199

5.9
Inicializar total_articulos_A = 0
Inicializar total_articulos_B = 0
Inicializar importe_A = 0
Inicializar importe_B = 0

Mientras el código del artículo no sea 'X':
    Leer código del artículo
    Leer precio unitario
    Leer cantidad de artículos

    Si el código es 'A':
        total_articulos_A = total_articulos_A + cantidad
        importe_A = importe_A + (precio unitario * cantidad)
    Sino si el código es 'B':
        total_articulos_B = total_articulos_B + cantidad
        importe_B = importe_B + (precio unitario * cantidad)

Imprimir total_articulos_A, importe_A
Imprimir total_articulos_B, importe_B

![image](https://github.com/user-attachments/assets/816b75a7-8d8a-4475-9179-e2a022ebae7a)

![image](https://github.com/user-attachments/assets/559b382d-40fb-40d6-aec5-9bc653ee62de)

5.10
Inicializar num_dias = 0
Inicializar suma_maxima = 0
Inicializar suma_minima = 0
Inicializar num_errores = 0

Mientras las temperaturas no sean 0,0:
    Leer temperatura_maxima
    Leer temperatura_minima
  
    Si temperatura_maxima == 9 o temperatura_minima == 9:
        Incrementar num_errores
    Sino:
        Incrementar num_dias
        suma_maxima = suma_maxima + temperatura_maxima
        suma_minima = suma_minima + temperatura_minima
Si num_dias > 0:
    media_maxima = suma_maxima / num_dias
    media_minima = suma_minima / num_dias
    porcentaje_errores = (num_errores / num_dias) * 100
Sino:
    media_maxima = 0
    media_minima = 0
    porcentaje_errores = 0

Imprimir num_dias, media_maxima, media_minima, num_errores, porcentaje_errores

![image](https://github.com/user-attachments/assets/a5e392d2-29ae-487f-a724-8855c1e61dca)

![image](https://github.com/user-attachments/assets/6f63562c-30fd-4632-9bf9-51ced4c2a115)
