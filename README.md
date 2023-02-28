# Proyecto-Parcial-3

![image](https://user-images.githubusercontent.com/116772752/208487145-d0353032-6309-4f57-a2a8-ec74218dba3d.png)

UNIVERSIDAD DE LAS FUERZAS ARMADAS ESPE

ASIGNATURA: FUNDAMENTOS DE CIRCUITOS ELÉCTRICOS

DOCENTE: ING. DARWIN ALULEMA

ESTUDIANTES:

* Caiza Alejandro
* Llerena Santiago 
* Lema Kevin

TEMA DEL PROYECTO: Mini amplificador de audio 

FECHA: 29-02-2023

# 1. OBJETIVOS
## Objetivo General
* Implemnetar el uso de circuitos integrados y capacitores para poder diseñar un mini amplificador de audio, controlando la salida de audio mediante un potenciometro ubicado el circuito para posteriormente diseñarlo en la placa de pruebas verificando sus correctas conexiones 

## Objetivos Especificos 
* Analizar los usos que posee un circuito integrado tal como el LM 386 utilizado en el desarollo del circuito, y de igual manera sus caracteristicas y aplicaciones 
* Implementar el uso de capacitores adecuados para el respectivo funcionamiento del circuito electrico 
* Desarollar un correcto diagrama esquematico el cual pueda describir en su totalidad cada conexion que se realiza en el circuito 

# 2. MARCO TEORICO


# 3. MATERIALES
* Protoboard o placa de pruebas
* ![image](https://user-images.githubusercontent.com/116832991/221930329-10d7748c-268e-4ccd-9b7a-e24ad8e840fd.png)


* 1 integrado LM 386
* ![image](https://user-images.githubusercontent.com/116832991/221929895-e5f7b327-133c-42f8-beb1-e1c5d9e76563.png)


* 1 Condensador de 220 uF a 16V
* ![image](https://user-images.githubusercontent.com/116832991/221929753-c3df8e06-e79f-4233-9e87-d6c638cff4b8.png)

 
* 1 Potenciomentro de 10K
* ![image](https://user-images.githubusercontent.com/116832991/221930674-3d9f3d7d-2002-4296-9481-3213b82cc7bc.png)


* fuente de alimentacion entre 5V a 12V
* ![image](https://user-images.githubusercontent.com/116832991/221928808-046b4b40-cfb6-4827-a5e6-97b66cc225b4.png)


* 1 bocina de 8 ohms 2 watts
* ![image](https://user-images.githubusercontent.com/116832991/221928541-9bc45823-f087-4288-be4e-3faac7fe8c60.png)


* 1 cable plug o adaptador de audio
* ![image](https://user-images.githubusercontent.com/116832991/221928137-be4eb543-8fc2-4c45-8b22-8132204db581.png)


* jumpers o cables macho macho
* ![image](https://user-images.githubusercontent.com/116832991/221927961-2bde1e3c-6990-4fa4-b1aa-bfb1261dedd2.png)


# 4. PROCEDIMIENTO 
## Diagrama del circuito 

Para comenzar con el circuito, primero detallamos el diagrama circuital  del proyecto :
![mini amplificador de audio](https://user-images.githubusercontent.com/116832991/221779921-9b704283-0617-4d97-bc50-fc8b4fd44334.png)

## Armado de proyecto 
1. ![image](https://user-images.githubusercontent.com/116832991/221780360-91807e16-03f8-4d13-9206-0cdd94d4d3db.png)
2. ![image](https://user-images.githubusercontent.com/116832991/221780387-ff5e116a-b592-480f-8521-e932c9a00cdc.png)
3. ![image](https://user-images.githubusercontent.com/116832991/221780415-a3974d0e-fdb0-4d0f-90d1-c2167a07881b.png)
4. ![image](https://user-images.githubusercontent.com/116832991/221780447-1776ef19-0b01-4515-ab6d-accfaf343ffd.png)
5. ![image](https://user-images.githubusercontent.com/116832991/221780465-5be005a8-61dc-449c-b6c4-b83b964243f7.png)
6. ![image](https://user-images.githubusercontent.com/116832991/221780486-e9a17960-3e7c-4483-a0ac-92bae6eb8d62.png)
7. ![image](https://user-images.githubusercontent.com/116832991/221780508-0577db1e-fcec-4245-97dd-f1f54d94c78b.png)
8. ![image](https://user-images.githubusercontent.com/116832991/221780548-2e5f76ca-dd9b-4096-8987-fc10d37033da.png)
9. ![image](https://user-images.githubusercontent.com/116832991/221780568-f74f873a-97a9-4985-9cb9-5777542bd46e.png)
10. ![image](https://user-images.githubusercontent.com/116832991/221780592-0c1e1dc1-7112-4c22-a435-421f34649d29.png)


## FUNCIONAMIENTO DEL CIRCUITO

El circuito funciona mediante un circuito integrado el cual es el LM 386 este es un amplificador de audio el cual tiene 8 pines, los cuales se detallan a continuacion en la imagen:
* ![image](https://user-images.githubusercontent.com/116832991/221934243-f8acb08c-16a4-4c9c-bff7-03f550102c5f.png)

* Para comenzar realizamos un puente entre los pines 2 y 4 del integrado posteriormente realizamos una conexion desde el pin 2 del integrado este el pin no inversor el cual se utiliza para proporcionar la señal de audio, lo conectamos mediante un jumper al pin medio del potenciometro, como sabemos el potenciometro tiene 3 pines el pin izquierdo conectado a la fuente de alimentacion, el pin medio se encarga de controlar la intensidad de corriente que fluye por el circuito y el pin derecho conectado a tierra, con esta conexion controlamos la salida de audio, realizamos una conexion desde el pin 6 el cual va conectado a la fuente de alimentacion al pin positivo del condensador, este se encarga de almacenar carga y suministrar la energía que le demanda el amplificador y desde el pin negativo realizamos una conexion a la bocina, el condensador se conecta con el pin positivo en el pin 5 del integrado este es el pin de saida, se encarga de  proporcionar audio de salida amplificado y aliado al altavoz, en el potenciometro realizamos la conecion del cable plug encargado de recibir la señal de audio desde un dispositivo movil este conectado al pin derecho del potenciometro y al pin 4 del integrado ya que este pin se encarga de estar conectado a tierra de tal manera dejando salir de audio 

# VIDEO


# CONCLUSIONES


# REFERENCIAS
* https://www.youtube.com/watch?v=8U0o1pAvK20&t=279s
* https://amplificadores.info/amplificadores-de-audio/lm386

