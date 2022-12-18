# Informe-4

Nombre: Donovan Jhosue Salazar Lopez

# 1. OBJETIVOS

## OBJETIVO GENERAL

• Conocer sobre los circuitos en serie-paralelo y los teoremas de circuitos y conversiones mediante la utilización del libro de Floyd "Principios de Circuitos Eléctricos"

## OBJETIVOS ESPECIFICOS

• Resumir los capítulos siete y ocho del libro de Floyd "Principios de Circuitos Eléctricos", para que de esta forma se pueda comprender de una mejor manera los temas descritos.

• Aplicar los conocimientos adquiridos de los temas de circuitos en serie y circuitos en paralelo para la resolución de los ejercicios propuestos por el libro de Floyd.

# 2. MARCO TEÓRICO (RESUMEN)

### • CAPITULO 7: CIRCUITOS EN SERIE-PARALELO


3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

1.Visualice y trace los siguientes circuitos en serie-paralelo:
(a) R1 en serie con la combinación en paralelo de R2 y R3
(b) R1 en paralelo con la combinación en serie de R2 y R3
(c) R1 en paralelo con una rama que contiene R2 en serie con una combinación en paralelo de otros cuatro resistores

![image](https://user-images.githubusercontent.com/116816731/208300737-d645ab5f-e477-46aa-ba39-94ce4200163b.png)
![image](https://user-images.githubusercontent.com/116816731/208300747-da8670d0-c41e-4140-9487-0ff168619854.png)
![image](https://user-images.githubusercontent.com/116816731/208300775-59e6399f-657e-4369-bc21-f470c3ac8393.png)

2.En cada circuito de la figura 7-62, identifique las relaciones en serie-paralelo de los resistores vistas desde la fuente.

![image](https://user-images.githubusercontent.com/116816731/208300821-22ce25ee-7385-41cc-a2e4-a3ee3baf6543.png)

(a)R1 y R4 están en serie con la combinación en paralelo de R2 y R3.

(b)R1 está en serie con la combinación en paralelo de R2, R3 y R4.

(c)La combinación en paralelo de R2 y R3 está en serie con la combinación en paralelo de R4 y R5. Todo esto está en paralelo con R1

5.Trace el diagrama esquemático de la configuración de la tarjeta de circuito impreso mostrada en la figura 7-64 indicando valores de resistor, e identifique las relaciones en serie-paralelo.

![image](https://user-images.githubusercontent.com/116816731/208300862-1cd379df-a507-44d9-8f3d-34c9535b2a33.png)

Respuesta

![image](https://user-images.githubusercontent.com/116816731/208300892-1fdff483-2645-46d2-86c2-db7cb773bbb0.png)

R5, R6, R7, R8, R9, R10 y R11 están en serie con la combinación en paralelo que, a su vez, está en paralela con la combinación en serie R1 y R3, y R2 y R4.

7.Configure una tarjeta de circuito impreso para el circuito de la figura 7-63(c). La batería tiene que conectarse externa a la tarjeta.

![image](https://user-images.githubusercontent.com/116816731/208300944-595b33d7-526e-4d03-93db-ac85c216c913.png)

Respuesta

![image](https://user-images.githubusercontent.com/116816731/208300969-3a9cfd4e-12d2-46d6-9605-aa62fbad825c.png)

SECCIÓN 7–2 Análisis de circuitos resistivos en serie-paralelo

9.Para cada uno de los circuitos mostrados en la figura 7-62, determine la resistencia total presentada a la fuente.

![image](https://user-images.githubusercontent.com/116816731/208300994-35e30f98-4efc-4b41-8b67-7bd35e0ac270.png)

(a)

1/Req=1/R2+1/R3
1/Req=1/100+1/100
Req=50

RT=R1+R4+Req
RT=56+27+50
RT=133 ohm

(b)

1/Req=1/680+1/330+1/180
Req=99.43

RT=99.43+680
RT=779.43 ohm

(c)

1/Req=1/6.2+1/3.3
Req=2.15

1/Req=1/10+1/5.6
Req=3.59

Req=2.15+3.59
Req=5.74

1/RT=1/5.74+1/1.0
RT=0.852
RT=852 ohm

11.Determine la corriente a través de cada resistor del circuito de la figura 7-62; calcule en seguida cada caída de voltaje.

![image](https://user-images.githubusercontent.com/116816731/208301024-550f207e-b2b8-4636-9e4f-2c0ac80b94c9.png)

(a)I1 = I4= 11.3mA, I2 = I3 = 5.64 mA,
V1 = 633 mV, V2 = V3 = 564 mV,
V4 = 305mV

(b)I1 = 3.85 mA, I2 = 563 uA,
I3 = 1.16 mA, I4 = 2.13 mA, V1 = 2.62 V,
V2 = V3 = V4 = 383 mV

(c)I1 = 5 mA, I2 = 303 mA,
I3 = 568 mA, I4 = 313 uA,
I5 = 558 mA, V1 = 5 V,
V2 = V3 = 1.88 V, V4 = V5 = 3.13 V

13.Encuentre RT para todas las combinaciones de los interruptores de la figura 7-66

![image](https://user-images.githubusercontent.com/116816731/208303995-a5a669e6-30ce-4197-89a9-7467734c83ca.png)

Respuesta

SW1 cerrado, SW2 abierto: 220 ohm
SW1 cerrado, SW2 cerrado: 200 ohm
SW1 abierto, SW2 abierto: 320 ohm
SW1 abierto, SW2 cerrado: 300 ohm

15.Determine el voltaje en cada nodo con respecto a tierra en la figura 7-67.

![image](https://user-images.githubusercontent.com/116816731/208304036-bb2890ea-7d5d-44bc-95c4-2baffc25599a.png)

Respuesta

VA =1 00V
VB = 61.5V
Vc = 15.7V
VD = 7.87V

17. En la figura 7-68, ¿cómo determinaría el voltaje entre los extremos de R2 por medición sin conectar directamente un medidor entre los extremos del resistor?

![image](https://user-images.githubusercontent.com/116816731/208304071-6f3f87db-8627-4d1c-abd1-e34e89b43b94.png)

Respuesta

Se debe medir el voltaje en A con respecto a tierra y el voltaje en B con respecto a tierra. La resta de esto es VR2.

19.Determine la resistencia del circuito mostrado en la figura 7-68 como se ve desde la fuente de voltaje.

![image](https://user-images.githubusercontent.com/116816731/208304094-0fb90b81-3550-4d5c-a686-7d2d4e837466.png)

Req1 = 56 + 560 + 100
Req1 = 716

Req2 = 100 + 1000
Req2 = 1100

1/RT = 1/716 + 1/1100 + 1/1000
RT = 303 kohm

21.(a) Determine el valor de R2 en la figura 7-70. (b) Encuentre la potencia en R2.

![image](https://user-images.githubusercontent.com/116816731/208304201-59cac81e-3149-467c-9a17-35918490a069.png)

Respuesta

(a)110 kohm

(b)110 mW

23.Encuentre la resistencia entre cada uno de los siguientes juegos de nodos mostrados en la figura 7-72: AB, BC y CD

![image](https://user-images.githubusercontent.com/116816731/208304250-61611917-c543-46f4-a9aa-290d119889bc.png)

Respuesta

RAB = 1.32 kohm

RBC = 1.32 kohm

RCD = 0 ohm

SECCIÓN 7–3 Divisores de voltaje con cargas resistivas

25.Un divisor de voltaje está compuesto por dos resistores de 56 kÆ y una fuente de 15 V. Calcule el voltaje de salida sin carga. ¿Cuál será el voltaje de salida si se conecta un resistor con carga de 1.0 MÆ a la salida?

Vsalida(sin carga) = (R2/R1+R2)VS
Vsalida(sin carga) = (56/56+56)15
Vsalida(sin carga) = 7.5V

R2||RL = R2RL/R2+RL
R2||RL = (56)(1000)/56+1000
R2||RL = 53.03

Vsalida(con carga) = (R2||RL/R1+R2||RL)Vs
Vsalida(con carga) = (53.03/56+53.03)15
Vsalida(con carga) = 7.29V

27.¿Cuál de dos cargas, una de 10 kohm y otra de 47 kohm, provocará una disminución más pequeña en el voltaje de salida de un divisor de voltaje dado?

Vsalida = (R2/R1+R2)Vs

Vsalida = (10/10+47)Vs
Vsalida = 0.175Vs

Vsalida = (47/10+47)Vs
Vsalida = 0.824Vs

Respuesta

47 kohm

29.En la figura 7-74, determine el voltaje de salida con una carga de 33 kohm conectada entre A y B.

![image](https://user-images.githubusercontent.com/116816731/208304369-53b68a5e-0f03-488a-9232-40723bacd050.png)

Req = R2+R3
Req = 5.6 + 2.7
Req = 8.3

Req||RL = ReqRL/Req+RL
Req||RL = 8.3(33)/8.3+33
Req||RL = 6.63

Vsalida(con carga) = (Req||RL/R1+Req||RL)Vs
Vsalida(con carga) = (6.63/10+6.63)22
Vsalida(con carga) = 8.77V

35.¿En cuál de los siguientes intervalos de voltaje presentará un voltímetro la mínima carga que haya en un circuito? (a) 1 V (b) 10 V (c) 100 V (d) 1000 V

Respuesta: 1000 V

37.El voltímetro descrito en el problema 36 se utiliza para medir voltaje entre los extremos de R4 en la figura 7-62(a).

(a) ¿Qué intervalo se deberá utilizar?

Respuesta: en el intervalo de 0.5

(b) ¿En cuánto se reduce el voltaje medido por el medidor con respecto al voltaje real?

Respuesta: Se reduce en un ≅ 1 mV

39.Para el circuito mostrado en la figura 7-77, calcule:

![image](https://user-images.githubusercontent.com/116816731/208304438-b851d291-ba10-4a37-83be-91a4b0c1ad0a.png)

La resistencia total entre las terminales de la fuente

Calcular primero la resistencia del triángulo inferior del lado derecho.

R=560Ω+560Ω

R=1120 Ω

![image](https://user-images.githubusercontent.com/116816731/208304469-29cc657b-7bd6-4862-844b-7344f37b84b1.png)

![image](https://user-images.githubusercontent.com/116816731/208304481-e49f1cbc-7d52-4cfb-8354-806c4b30265c.png)

![image](https://user-images.githubusercontent.com/116816731/208304494-892cfffa-edbb-4088-b828-aa8bedfff59d.png)

![image](https://user-images.githubusercontent.com/116816731/208304510-09030205-2f1d-4d0b-b0ae-dd37acfb5de4.png)

![image](https://user-images.githubusercontent.com/116816731/208304516-74dc3d1a-0e5f-4012-9a03-5d6975a85f02.png)

41.Determine la resistencia total entre las terminales A y B de la red en escalera de la figura 7-79. Asimismo, calcule la corriente en cada rama con 10 V entre A y B.

![image](https://user-images.githubusercontent.com/116816731/208304558-0fbd5d2f-d3b5-407d-b390-7960023fa403.png)

43.Determine IT y VSALIDA en la figura 7-80.

![image](https://user-images.githubusercontent.com/116816731/208304591-0f361cca-60a8-4af3-a3d6-159e306b9537.png)

45.Repita el problema 44 para as siguientes condiciones

(a) SW3 y SW4 conectados a 12 V, SW1 y SW2 a tierra

Respuesta: El voltaje con respecto al anterior ejercicio y sabiendo que

Vsalida= 2R/4R*V

El voltaje es 9V

(b) SW3 y SW1 conectados a 12 V, SW2 y SW4 a tierra

Respuesta: 3.75 V

(c) Todos los interruptores conectados a 12 V

Respuesta: 11.25 V

47.Una celda de carga tiene cuatro medidores de deformación idénticos con una resistencia ilimitada de 120,000 Ω para cada medidor (un valor estándar). Cuando se agrega una carga, los medidores a tensión incrementan su resistencia en 60 mΩ , a 120,060 Ω , y los medidores a compresión disminuyen su resistencia en 60 Ω m, a 119.940 Ω , como se muestra en la figura 7-82. ¿Cuál es el voltaje de salida con carga?

![image](https://user-images.githubusercontent.com/116816731/208304620-42afec66-1197-4d3a-9802-1946e370efa2.png)

49.¿Es correcta la lectura del voltímetro de la figura 7-84?

![image](https://user-images.githubusercontent.com/116816731/208304636-e134a1f7-e923-4689-9c3d-32fbcb5ccc3c.png)

51.En la figura 7-86 hay una falla. Con base en las indicaciones del medidor, determine cuál es la falla.

![image](https://user-images.githubusercontent.com/116816731/208304662-1fd4b583-a07e-4b0c-9ef9-d2701af14b6a.png)

53.Revise las lecturas de los medidores de la figura 7-88 y localice cualquier falla que pudiera existir.

![image](https://user-images.githubusercontent.com/116816731/208304684-5f8d44a3-dbc8-46a4-b494-4dd8ea1d270e.png)

SECCIÓN 8–3 Conversiones de fuente

Una fuente de voltaje tiene los valores VS 300 V y RS 50 Ω. Conviértala en una fuente de corriente equivalente.

I_s=(300 V)/(50 Ω)

I_(s )=6 A

Una batería tipo D nueva tiene entre sus terminales un voltaje de 1.6 V y puede suministrar hasta 8.0 A a un cortocircuito durante muy poco tiempo. ¿Cuál es la resistencia interna de la batería?

Rs=Vs/Is=1.6V/(8 A)

Rs=0.2 Ω

Una fuente de corriente tiene una IS de 600 mA y una RS de 1.2 k Ω. Conviértala en una fuente de voltaje equivalente.

Vs=0.6 A*1200 Ω=720 V

SECCIÓN 8–4 El teorema de superposición

Con el método de superposición, encuentre la corriente a través de R5 en la figura 8-69.

![image](https://user-images.githubusercontent.com/116816731/208304722-90823658-ccef-4992-bf21-d7e5e29d1aac.png)

![image](https://user-images.githubusercontent.com/116816731/208304730-e9583712-ea0d-4ef5-a059-33850a66fcbd.png)

![image](https://user-images.githubusercontent.com/116816731/208304739-a80675df-c392-4134-b1e2-627f536e2fff.png)

Con el teorema de superposición, determine la corriente a través de R3 en la figura 8-70.

