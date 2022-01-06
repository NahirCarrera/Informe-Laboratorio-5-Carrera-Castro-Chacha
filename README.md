![image](https://user-images.githubusercontent.com/93786746/140656495-1e9017c5-1622-4145-a547-0ebbe5014f3d.png)
# <p align=center> UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE 
## <p align=center> FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS
# <p align=center>  INFORME LABORATORIO 5
# Integrantes: <p align=right> NRC: 10151
* Carrera Vela Nahir Danae
* Castro Chugchilan Paúl Enrique
* Chacha Chacha Kevin Alejandro
## 1. Objetivos
  ### General: 
  * Comprobar experimentalmente el teorema Thevenin en un circuito resistivo.
  ### Específicos
  * Desarrollar el circuito equivalente de Thevenin del ejercicio planteado a través del simulador Tinkercad para obtener el voltaje y la corriente de la resistencia propuesta.
  * Explicar el método de Thevenin mediante organizadores gráficos para la fundamentación teórica de la presente práctica.
  * Justificar el desarrollo de la práctica a través de un archivo audiovisual para respaldar los datos calculados analíticamente y los datos simulados. 
## 2. Marco Teórico
  ## <p align=center> Materiales
  ![Materiales LAB 5](https://user-images.githubusercontent.com/93829976/148461204-d8f510dc-1ea7-47a3-89f7-57532b4d379c.jpeg)
  ## <p align=center> Teorema de Thevenin
 ![Teorema de Thévenin](https://user-images.githubusercontent.com/93829976/148461212-ed0eda6e-6be0-4d80-aca1-8e2790e729cd.jpeg)
## 3. Explicación del Procedimiento
   ## Materiales
 * 2 Fuente de voltaje CD
 * 2 Multímetros Digitales
 * 1 Resistor (560 Ohm)
 * 2 Resistores (4.7 k Ohm)
 * 1 Resistor (330 Ohm)
 * 1 Resistor (100 Ohm)
 * 1 Resistor (1 k Ohm)
 * 1 Potenciómetro de precisión de 1k ohm
 * 1 Protoboard
  ## Procedimiento
1) Armar el circuito que se muestra en la Figura 5.1.
 ![image](https://user-images.githubusercontent.com/93786746/148314776-5942268f-0199-40c0-be8f-7fa3c47e1eef.png)
 ![image](https://user-images.githubusercontent.com/93786746/148315018-aba44c74-a9c6-4c5f-a8ea-2131a8ad231c.png)

 _Ilustración 1. Circuito armado en Laboratotior virtual Tinkercad_
    
2) Medir el voltaje y la corriente del resistor R5, anotar los resultados en la tabla 5.1. 
![image](https://user-images.githubusercontent.com/93786746/148315132-c2fe5775-6afa-40af-b3d4-3cfd054c027c.png)
 
_Ilustración 2. Medición de voltaje en resistor R5_
![image](https://user-images.githubusercontent.com/93786746/148315246-3c751dcb-3e83-428a-b41d-b9b8f0ff15a8.png)
 
_Ilustración 3. Medición de corriente en resistor R5_
    
3) Desconectar el resistor R5 y medir el voltaje en el circuito abierto. Anotar el valor medido en la tabla 5.1
![image](https://user-images.githubusercontent.com/93786746/148315648-64221442-ef12-4f0f-91f0-da51d8305046.png)
 
_Ilustración 4. Medición de voltaje de Thevenin en circuito abierto sin resistor R5_
 
4) Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valore medido en la table 5.1.
![image](https://user-images.githubusercontent.com/93786746/148315944-ea4a61d3-e31c-48e7-ae8c-252ba0a33602.png)
 
 _Ilustración 5. Medición de resistencia equivalente de Thevenin con fuentes V1 y V2 reemplazadas por su resistencia interna y R5 desconectado_
 
 5) Implemente el circuito equivalente de Thevenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la table 5.2.

![image](https://user-images.githubusercontent.com/93786746/148317700-e1535d22-5f92-449d-8dfc-4ef09141e7af.png)

_Ilustración 6.Implementación del circuito equivalente de Thevenin_
 
![image](https://user-images.githubusercontent.com/93786746/148317845-5c69b843-f882-4750-ab23-d987d0e93dd1.png)

 _Ilustración 7. Medición de voltaje en el circuito equivalente de Thevenin_
 
![image](https://user-images.githubusercontent.com/93786746/148317980-895947cc-cdc2-4e17-a243-6f8dd8092da3.png)

 _Ilustración 8.Medición de corriente en el circuito equivalente de Thevenin_
   
    ## Cálculos de Respaldo
  ### 1. Cálculo del voltaje de Thévenin
  ![image](https://user-images.githubusercontent.com/93829962/148465102-2e26f01e-5a42-45b1-9b6d-fe0ceb08c222.png)
  
  ### 2. Cálculo de la Resistencia equivalente de Thévenin
  ![image](https://user-images.githubusercontent.com/93829962/148465053-5dec9dc9-5ade-40fc-8dc6-4eff70756c45.png)
    
  ### 3. Cálculo del voltaje y corriente de R5 en el circuito original
  ![image](https://user-images.githubusercontent.com/93829962/148465289-4619e408-5161-4fda-b743-06b08dcd669d.png)
  ![image](https://user-images.githubusercontent.com/93829962/148465334-e79de58e-05dc-4419-a4a6-bae6122213ff.png)
  
  ### 4. Cálculo del voltaje y corriente de R5 en el circuito equivalente 
  ![image](https://user-images.githubusercontent.com/93829962/148465379-b72b8715-7d40-469a-bf6f-3c63dd8b24b0.png)

## 4. Respuesta a Interrogantes y cálculo de error
_Tabla 5.1 Valores del circuito equivalente de Thevenin_
    


_Tabla 5.2 Comprobación del teorema de Thevenin_
    


_Tabla 4.3 Cálculo de error resistencia de Thevenin resultados Analíticos - Simulados_
    


_Tabla 4.4 Cálculo de error voltaje de Thevenin resultados Analíticos - Simulados_
    


## 5. Video
  * 
## 6. Conclusiones
  * Para concluir, la aplicación del método de Thevenin es muy importante y eficiente, ya que permite reducir circuitos resistivos que pueden llegar a ser muy complejos en circuitos mucho más simples que solo constan de una resistencia, de una fuente de voltaje y del componente a analizar; al ser un circuito más sencillo, el análisis del elemento que se extrajo del circuito original se vuelve más eficiente ya que los cálculos a realizarse son más cortos. Además, pasando a la parte práctica, resulta más sencillo y económico elaborar circuitos resistivos equivalentes que cumplan con las mismas funciones del circuito original.
  * 
## 7. Bibliografía
 * Floyd, T. (2007). _Principios De Circuitos Eléctricos_. Octava edición. México. Pearson Education.
