![tablero](game_manual_assets/midgarhex_web_logo.png)
#### Un juego de mesa competitivo inspirado en la cultura Vikinga y la mitología Nórdica
###### Por: Joan Lopez (jslopezr00@gmail.com)

###### Repositorio: https://github.com/joanhalo2/Midgard

###### Jugadores: 2 - 4 | Tiempo: 60 min
###### Licencia: Creative Commons  
______________________________________________________________________________
## 0. ÍNDICE  

**1.** Resumen del juego  
**2.** Tablero  
**3.** Reglas y Glosario  
**4.** Piezas   
  * **4.1** Piezas Básicas  
  * **4.2** Piezas Especiales  
  * **4.3** Piezas Míticas   
  * **4.4** Jarls

**5.** Cartas de Fuerza de Batalla  
**6.** Configuración inicial del tablero   
**7.** Fases del turno    
**8.** Créditos adicionales   
______________________________________________________________________________
### 1. RESUMEN DEL JUEGO   
El principal objetivo en MidgardHex es derrotar al Jarl(Regente) que comanda el ejercito de tu contrincante. Se podría definir la esencia del juego con las siguientes preguntas:

- **¿Que tipo de juego es MidgardHex?**  
  MidgardHex es un juego de tipo competitivo cuyo principal objetivo es derrotar al Jarl enemigo derrotando a su vez al ejercito enemigo.  
- **¿Qué historia cuenta el juego?**  
  Midgar se inspira en el ajedrez para la base de enfrentamiento entre dos ejércitos Vikingos, pero utiliza elementos de la mitología Nórdica y de aspectos militares historicos de la época Vikinga (siglos IX,X,XII).
- **¿Para cuantas personas está diseñado?**  
  Inicialmente está diseñado para dos (2) personas, pero si se extiende el tamaño del tablero pueden jugar hasta cuatro(4) personas.  
- **Cuales son sus principales mecánicas?**  
  Usa principalmente elementos de azar por medio del lanzamiento de **dados de 4, 6, y 20 lados** respectivamente. Adicionalmente el tablero basado en piezas hexagonales permite simular un campo de batalla y la utilización de elementos propios de juegos de cartas coleccionables, así como elementos de
  juegos de rol.  

______________________________________________________________________________
### 2. TABLERO   

#### 2.1 Disposición (para 3 jugadores)  
![tablero](game_manual_assets/tablero.png)  

#### 2.2 Tipos de losas
  - ***Charcos***: Aplica ***desventaja*** a todas las tiradas realizadas por cualquier pieza mientras permanezca en esta loza.  

  - ***Praderas***: No aplica ninguna regla.

  - ***Tierras***: Aplica ***ventaja*** a todas las tiradas realizadas por cualquier pieza mientras permanezca en esta loza.  

#### 2.3 Distribución de losas
| 2 Jugadores  | 3 Jugadores  | 4 Jugadores  |
|---|---|---|
| 20 Charcos  | 28 Charcos  | 38 Charcos   |
| 60 Praderas  | 85 Praderas  | 112 Praderas  |
| 11 Tierras  | 14 Tierras  | 19 Tierras  |
| **Total: 91**  | **Total: 127**  | **Total: 169**  |

______________________________________________________________________________
### 3. REGLAS y GLOSARIO
#### 3.1 Definiciones
- ***Pieza:***  
  Ficha que representa a una (1) unidad de batalla (Jarl, Guerrero, etc)  
- ***Loza:***  
  Pieza **hexagonal** que representa un (1) espacio en el terreno de juego (tablero)  
- ***Tirada:***  
  También conocida como ***lanzamiento***, se refiere al acto de lanzar un dado.
- ***Modificadores:***  
  Son los valores unitarios (ej: +2,+3,+5) que se le adicionan al resultado de una **tirada o lanzamiento**.
- ***Clase de dificultad (CD):***   
  Se refiere al número objetivo que se debe **igualar o superar** en una **tirada**.  
  Por ejemplo, una expresión del tipo ```CD16``` indica que en el resultado de una **tirada (sumando los modificadores correspondientes)** debe ser igual o superior a **16**.  

- ***1d20:***  
  Abreviatura para referirse a un dado de **20 caras**.  

- ***1d4:***  
  Abreviatura para referirse a un dado de **4 caras**.  

- ***1d6:***  
  Abreviatura para referirse a un dado de **6 caras**. (***los de toda la vida***)
- ***Ventaja:***  
  Consiste en lanzar **2d20** y tomar como resultado el ***mayor*** valor entre ambos

- ***Desventaja:***  
  Consiste en lanzar **2d20** y tomar como resultado el ***menor*** valor entre ambos

#### 3.2 Características

| Característica  |   Símbolo   | Descripción  | Ejemplo  |
|:---:|:---:|:---:|:---:|
| Armadura  | ![armadura](game_manual_assets/armor_icon.png)  | Valor de la **CD** a superar con una tirada de un dado **1d20**  | ![armadura](game_manual_assets/armor_example.png) |
|  Bonificador de Ataque | ![ataque](game_manual_assets/attack_icon.png)  |  **Bonificador** que se debe sumar al resultado de la tirada de **1d20** |![ataque](game_manual_assets/attack_example.png) |
| Movimiento  | ![movimiento](game_manual_assets/mov_icon.png)  | Cantidad de lozas que se puede mover la pieza por turno | ![movimiento](game_manual_assets/mov_example.png)|
| Alcance  | ![alcance](game_manual_assets/alcance_icon.png)  | Cantidad **máxima** de lozas que puede alcanzar un ataque de dicha pieza  |![alcance](game_manual_assets/alc_example.png) |
| Puntos de sacrificio  | ![sacrificio](game_manual_assets/sacrifice_icon.png)  | Valor unitario que sirve para conseguir **Cartas** de ***Fuerza de Batalla*** o ***Favores de los Dioses***  | ![alcance](game_manual_assets/sacr_example.png)|

#### 3.3 ACCIONES  

  - **Atacar:**    
    1. Determinar si en la loza actual se aplica **ventaja** o **desventaja**, caso en el cual se deben lanzar **2d20** y escoger el valor mayor o menor según sea el caso.
    2. **Lanzar 1d20**
    3. Al valor del lanzamiento del paso anterior sumar los bonificadores de ataque correspondientes.

  - **Ataques combinados:(Solo contra unidades Míticas)**   
    Si 2 o más piezas están adyacentes a una misma pieza Mítica se pueden sumar los resultados de las tiradas de ataque con sus bonificadores correspondientes.

  - **Realizar sacrificios:**  
    Canjear las piezas enemigas capturadas por su valor total de **Puntos de Sacrificio** con el objetivo de obtener **Cartas** de ***Fuerza de Batalla*** o ***Favores de los Dioses***.   

______________________________________________________________________________
### 4. PIEZAS  
##### **4.1 Piezas Básicas**  
<!-------------------------------- GUERRERO-------------------------------------->
  <table>
  <tr><th> GUERRERO </th><th> VALORES</th></tr>
  <tr><td>

  ![token](/game_manual_assets/pawns/guerrero.png)

  </td><td>

  |   Característica| Valor                                        |
  |:-----------------:|:------------------------------------------:|
  | ![armadura](game_manual_assets/armor_icon.png)  | **12**       |
  | ![ataque](game_manual_assets/attack_icon.png)   | **+3**       |
  | ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
  | ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
  | ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **1**  |
  </td></tr> </table>
<!-------------------------------- ARQUERO -------------------------------------->
  <table>
  <tr><th> ARQUERO </th><th> VALORES</th></tr>
  <tr><td>

  ![token](/game_manual_assets/pawns/arquero.png)

  </td><td>

  |   Característica| Valor                                        |
  |:-----------------:|:------------------------------------------:|
  | ![armadura](game_manual_assets/armor_icon.png)  | **10**       |
  | ![ataque](game_manual_assets/attack_icon.png)   | **+2**       |
  | ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
  | ![alcance](game_manual_assets/alcance_icon.png) | **6**        |
  | ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **1**  |
  </td></tr> </table>

<!-------------------------------- lANCERO -------------------------------------->
  <table>
  <tr><th> LANCERO </th><th> VALORES</th></tr>
  <tr><td>

  ![token](/game_manual_assets/pawns/lancero.png)

  </td><td>

  |   Característica| Valor                                        |
  |:-----------------:|:------------------------------------------:|
  | ![armadura](game_manual_assets/armor_icon.png)  | **9**        |
  | ![ataque](game_manual_assets/attack_icon.png)   | **+4**       |
  | ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
  | ![alcance](game_manual_assets/alcance_icon.png) | **2**        |
  | ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **1**  |
  </td></tr> </table>

##### **4.2 Piezas Especiales**   
<!-------------------------------- BERSERKER -------------------------------------->
<table>
<tr><th> BERSERKER </th><th> VALORES</th></tr>
<tr><td>

![token](/game_manual_assets/pawns/berseker.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **15**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+5**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **2**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **2**  |
</td></tr> </table>
<!-------------------------------- VALKIRIAS -------------------------------------->
<table>
<tr><th> VALKIRIA </th><th> VALORES</th></tr>
<tr><td>

![token](/game_manual_assets/pawns/valkiria.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **16**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+5**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **2**  |
</td></tr> </table>
<!-------------------------------- JINETES DE PONY -------------------------------------->
<table>
<tr><th> JINETE </th><th> VALORES</th></tr>
<tr><td>

![token](/game_manual_assets/pawns/jinete.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **14**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+4**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **5**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **2**  |
</td></tr> </table>

##### **4.3 Piezas Míticas**  
<!-- | Nombre  | Descripción  | Efecto |
|:-:|---|---|
| Fenrir  | Lobo Gigante |Daño x +área|
| Jörmundgander   | Serpiente Gigante|Veneno X área|
| Ymir  | Gigante de hielo |Daño x +área|
| Fafnir | Dragón de fuego  |Daño x +área|
| Nidhogg  | Dragón devorador de cuerpos |Multiplica puntos de sacrificio|
| Auðumbla  | Vaca Gigante  |Bonificadores de armadura X +área|
| Gullinbursti  |Cerdo Gigante   |Montura para el Jarl|
| Sigurd  | Héroe Mitológico  | Bonificadores de ataque X area| -->

###### Tamaño de lozas y Área de Efecto
Las piezas míticas a diferencias de las piezas normales **ocupan 7 lozas** y su área de efecto es de **9 lozas:**  

![areas](game_manual_assets/effect_areas.png)   


###### Movimiento de piezas míticas   
Todas las piezas míticas se mueven a razón de **1 loza** por movimiento, usando como ejemplo el siguiente diagrama:

![Mitic_mov](game_manual_assets/mitic_movement.png)

###### Fenrir:   
<!-------------------------------- Fenrir -------------------------------------->
<table>
<tr><th> Fenrir </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/Fenrir.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **21**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+5**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Lobo Gigante </th><th>El resultado de la tirada de ataque se aplica a 3 losas en el área de efecto</th></tr>
</table>

###### Jörmundgander:
<!-------------------------------- Jörmundgander -------------------------------------->
<table>
<tr><th> Jörmundgander </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/serpiente.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **20**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+5**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Serpiente Gigante </th><th>El resultado de la tirada de ataque se aplica a 2 lozas en el área de efecto</th></tr>
</table>

###### Ymir:
<!-------------------------------- Ymir -------------------------------------->
<table>
<tr><th> Ymir </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/gigante.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **23**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+4**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Gigante de hielo </th><th>El resultado de la tirada de ataque se aplica a 3 losas en el área de efecto. Las piezas que sobreviven al ataque no se pueden mover en el siguiente turno</th></tr>
</table>

###### Fafnir:
<!-------------------------------- Fafnir -------------------------------------->
<table>
<tr><th> Fafnir </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/fafnir.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **25**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+4**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Dragón de fuego </th><th>El resultado de la tirada de ataque se aplica a 3 losas en el área de efecto. Las piezas que sobreviven al ataque no se pueden mover en el siguiente turno</th></tr>
</table>

###### Nidhogg:   
<!-------------------------------- NidHogg -------------------------------------->
<table>
<tr><th> Nidhogg </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/Nidhogg.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **22**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+3**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Dragón devorador de cuerpos </th>
<th>Los puntos de sacrificio ganados con cada ataque exitoso de Nidhogg se duplican </th></tr>
</table>

###### Auðumbla:
<!-------------------------------- Auðumbla -------------------------------------->
<table>
<tr><th> Auðumbla </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/vaca.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **21**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+4**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Vaca Gigante </th><th>Todas las piezas aliadas dentro del área de efecto ganan +3 a su valor de Armadura</th></tr>
</table>

###### Gullinbursti:
<!-------------------------------- Gullinbursti -------------------------------------->
<table>
<tr><th> Gullinbursti </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/jabali.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **20**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+3**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Cerdo Gigante </th><th>Cuando se utiliza como montura para un Jarl, otorga +3 al movimiento y +2 al ataque del Jarl. No se podrá atacar al Jarl directamente hasta que Gullinbursti muera o deje de ser usado como montura </th></tr>
</table>

###### Sigurd:
<!-------------------------------- Sigurd -------------------------------------->
<table>
<tr><th> Sigurd </th><th> VALORES</th></tr>
<tr><td>

![token](game_manual_assets/miticas/sigurd.png)

</td><td>

|   Característica| Valor                                        |
|:-----------------:|:------------------------------------------:|
| ![armadura](game_manual_assets/armor_icon.png)  | **21**       |
| ![ataque](game_manual_assets/attack_icon.png)   | **+4**       |
| ![movimiento](game_manual_assets/mov_icon.png)  | **1**        |
| ![alcance](game_manual_assets/alcance_icon.png) | **1**        |
| ![sacrificio](game_manual_assets/sacrifice_icon.png)  | **5**  |
</td></tr>
<tr><th> Héroe Mitológico </th><th>Ocupa el espacio de una pieza Normal. Todas las piezas aliadas dentro del área de efecto tienen +3 en tiradas de ataque </th></tr>
</table>


##### **4.4 JARLS**  

###### Principales Características:
Un o una Jarl, son las piezas más importantes en MidgardHex, puesto que:
  - **Posee un contador de vidas:**![jarl_life](game_manual_assets/life_icon.png)**. Cuando este llega a cero (0),   el/ la Jarl muere.**   
  - **Al morir un Jarl, se pierde el juego**.   
  - **Es la única pieza capaz de invocar criaturas Míticas**.   
  - **Se pueden usar las habilidades de Jarl cada turno**.

###### Atacar a un/una Jarl:
Para atacar a un/una Jarl, las piezas atacantes deben superar en una tirada de ataque la defensa del Jarl ```(CD15)```, si se supera dicha tirada, se procede a lanzar el **dado de daño (1d4)** y el resultado de dicho lanzamiento **se debe restar al contador de vidas correspondiente.**  
##  
***Descripción de uso de una carta de Jarl***  
![jarl_desc](game_manual_assets/jarl_desc.png)  
##  

**A continuación se describen la anatomía de una carta de Jarl y como se usan:**  

**1.** ***Dado de daño***: Indica el dado (1d4 en este ejemplo) que se debe lanzar una vez superada una tirada de ataque que afecta al Jarl que está siendo atacado/a.  

**2.** ***Armadura:*** Valor de la **CD**(15 en este ejemplo) a superar con una tirada de **1d20**.  

**3.** Indicadores de ***movimiento,bonificador de ataque y alcance*** que aplican para dicho/a Jarl.  

**4.** ***+2*** Significa "Incrementa el contador de vidas en 2 unidades, si **una vez por turno** se supera una tirada de 1d20 con ```CD15```".  

**5.** ***-2*** Significa "Decrementa el contador de vidas en 2 unidades, y todas las unidades adyacentes al/la Jarl recibirán un **bonificador de +2** en sus tiradas de ataque **durante este turno**".  

**6.** ***-8*** Significa "Decrementa el contador de vidas en 8 unidades, y podrás invocar al campo de batalla (desde la loza de arranque) una criatura Mítica escogida al azar de la baraja correspondiente".   

**7.** Valor inicial del contador de vidas del/la Jarl.  

______________________________________________________________________________
### 5. CARTAS DE APOYO
Dichas cartas se obtienen intercambiando puntos de sacrificio ![sacrificio](game_manual_assets/sacrifice_icon2.png) por carta según la siguiente regla:

  **[![sacrificio](game_manual_assets/sacrifice_icon2.png) X 3]** : Obtienes una Carta de Fuerza de Batalla del mazo correspondiente.

  **[![sacrificio](game_manual_assets/sacrifice_icon2.png) X 8]** : Obtienes un lanzamiento de **2d6** en la tabla de ***Favores de los dioses***.

#### 5.1 Fuerzas de Batalla  

| Cantidad por Mazo | Nombre  | Efecto  |
|:-:|---|---|
|  2 | Valkiria  | Pieza especial  |
|  2 | Jinete de Pony  | Pieza especial  |
|  2 | Berserker  | Pieza especial  |
|  2 | Impulso de batalla  | Puedes atacar con 1 pieza adicional x 1 turno  |
|  2 | Grito de terror  | Un/a oponente solo puede atacar con 2 piezas x 1 turno  |
|  2 | Vigor  | Tu Jarl gana [ ![jarl_life](game_manual_assets/life_icon2.png) + 3 ] |
|  1 | Maldición de las runas  | Un Jarl enemigo pierde [ ![jarl_life](game_manual_assets/life_icon2.png) - 3 ]  |
|  2 | Ayuda de los aldeanos locales | Ganas  [ ![sacrificio](game_manual_assets/sacrifice_icon2.png) X 3 ] |
|  2 | Ayuda del sepulturero  | Un oponente pierde [ ![sacrificio](game_manual_assets/sacrifice_icon2.png) X 3 ]  |
|  2 | Escudo Nuevo  | Tu Jarl gana [ ![armadura](game_manual_assets/armor_icon2.png) + 3 ] permanentemente |
|  2 | Arma Nueva  | Tu Jarl gana [ ![armadura](game_manual_assets/attack_icon2.png) + 2 ] permanentemente |  

#### 5.1 Favores de los Dioses    
| **Resultado de lanzar 2d6** | **Favor obtenido**  |
|   :-:   |     ---             |
|2|Tu Jarl obtiene [ ![armadura](game_manual_assets/life_icon2.png) + 5 ] únicamente por este turno|
|3|Tus oponentes obtienen [ ![armadura](game_manual_assets/armor_icon2.png) - 3 ] en todas sus piezas por este turno |
|4|Recuperas tus **Guerreros** abatidos por tus oponentes|
|5|Ganas **3 nuevos Lanceros**|
|6|Ganas **3 nuevos Guerreros**|
|7|Tu petición a los dioses es ignorada (no ganas ningún beneficio)|
|8|Ganas **3 nuevos Arqueros**|
|9|Recuperas tus **Lanceros o Arqueros** abatidos por tus oponentes|
|10|Obtienes **un bonificador de +5** en todas tus tiradas este turno|
|11|Tus oponentes **tienen desventaja** en todas sus tiradas el siguiente turno (la desventaja no es acumulable)|
|12|Ganas **2 unidades especiales a tu elección**|  

______________________________________________________________________________
### 6. CONFIGURACIÓN INICIAL DE LA PARTIDA
- Se barajan los mazos de **Fuerzas de Batalla Piezas Míticas**

- Distribución inicial de piezas por cada jugador/ra:  

  | **Pieza** | **Cantidad inicial**  |
  |   :-:     |     ---               |
  |Jarl |1|  
  |Guerrero |10|  
  |Arquero |5|  
  |Lancero |5|

- Disposición de las piezas iniciales en el tablero:  
![tablero](game_manual_assets/tablero_disposicion.png)

______________________________________________________________________________
### 7. FASES DEL TURNO  

  **1. Fase de Sacrificios**  
  Al inicio de cada turno se pueden gastar los puntos de sacrificio conseguidos hasta el momento ( ![sacrificio](game_manual_assets/sacrifice_icon2.png) ) para obtener ***Cartas de Apoyo*** bien sean ***Fuerzas de Batalla o Favores de los Dioses***. Los puntos de sacrificio usados no pueden ser recuperados.

  **Si se obtuvieron nuevas piezas, estas ingresan en la LOZA DE ARRANQUE correspondiente**.

  **2. Fase de Movimiento**  
  Por cada turno se disponen de **hasta un máximo de 3 unidades de movimiento ( ![movimiento](game_manual_assets/mov_icon.png) )**, estas unidades se pueden distribuir libremente entre las piezas deseadas.

  **3. Fase de Jarl**  
  Se activa una de las habilidades del/la Jarl. Si se invocarón piezas míticas, estas podrán
  moverse hasta el próximo turno.

  **4. Fase de Ataque**  
  Por cada turno, luego de haberse llevado a cabo la fase de Movimiento correspondiente, **Se pueden declarar hasta un máximo de 3 piezas atacantes que cumplan los requisitos de alcance.**
  **Cada pieza solo puede atacar 1 única vez.**

  **5. Final del turno**  
  Luego de resolverse los resultados de **las tiradas de ataque** realizadas en la fase anterior, se procede a evaluar qué piezas enemigas se lograron derrotar para hacer un recuento de los **puntos de sacrificio** obtenidos este turno.

### 8. Créditos adicionales
  - Distintos cliparts usados principalmente en el arte de las piezas míticas y las fuerzas de batalla fueron tomadas de https://www.openclipart.org
  - "Warrior dude" Por: Ironthunder bajo la licencia Creative Commons-BY 3.0: https://opengameart.org/content/warrior-dude
  - "Warlord Portrait" Por Justin Nichol bajo la licencia Creative Commons-BY 3.0: https://opengameart.org/content/warlord-portrait
______________________________________________________________________________
### 9. OPEN GAME LICENSE  

##### OPEN GAME LICENSE Version 1.0a

The following text is the property of Wizards of the Coast, Inc. and is Copyright 2000 Wizards of the Coast, Inc ("Wizards"). All Rights Reserved.

1. Definitions: (a)"Contributors" means the copyright and/or trademark owners who have contributed Open Game Content; (b)"Derivative Material" means copyrighted material including derivative works and translations (including into other computer languages), potation, modification, correction, addition, extension, upgrade, improvement, compilation, abridgment or other form in which an existing work may be recast, transformed or adapted; (c) "Distribute" means to reproduce, license, rent, lease, sell, broadcast, publicly display, transmit or otherwise distribute; (d)"Open Game Content" means the game mechanic and includes the methods, procedures, processes and routines to the extent such content does not embody the Product Identity and is an enhancement over the prior art and any additional content clearly identified as Open Game Content by the Contributor, and means any work covered by this License, including translations and derivative works under copyright law, but specifically excludes Product Identity. (e) "Product Identity" means product and product line names, logos and identifying marks including trade dress; artifacts; creatures characters; stories, storylines, plots, thematic elements, dialogue, incidents, language, artwork, symbols, designs, depictions, likenesses, formats, poses, concepts, themes and graphic, photographic and other visual or audio representations; names and descriptions of characters, spells, enchantments, personalities, teams, personas, likenesses and special abilities; places, locations, environments, creatures, equipment, magical or supernatural abilities or effects, logos, symbols, or graphic designs; and any other trademark or registered trademark clearly identified as Product identity by the owner of the Product Identity, and which specifically excludes the Open Game Content; (f) "Trademark" means the logos, names, mark, sign, motto, designs that are used by a Contributor to identify itself or its products or the associated products contributed to the Open Game License by the Contributor (g) "Use", "Used" or "Using" means to use, Distribute, copy, edit, format, modify, translate and otherwise create Derivative Material of Open Game Content. (h) "You" or "Your" means the licensee in terms of this agreement.

2. The License: This License applies to any Open Game Content that contains a notice indicating that the Open Game Content may only be Used under and in terms of this License. You must affix such a notice to any Open Game Content that you Use. No terms may be added to or subtracted from this License except as described by the License itself. No other terms or conditions may be applied to any Open Game Content distributed using this License.

3. Offer and Acceptance: By Using the Open Game Content You indicate Your acceptance of the terms of this License.

4. Grant and Consideration: In consideration for agreeing to use this License, the Contributors grant You a perpetual, worldwide, royalty-free, non-exclusive license with the exact terms of this License to Use, the Open Game Content.

5. Representation of Authority to Contribute: If You are contributing original material as Open Game Content, You represent that Your Contributions are Your original creation and/or You have sufficient rights to grant the rights conveyed by this License.

6. Notice of License Copyright: You must update the COPYRIGHT NOTICE portion of this License to include the exact text of the COPYRIGHT NOTICE of any Open Game Content You are copying, modifying or distributing, and You must add the title, the copyright date, and the copyright holder's name to the COPYRIGHT NOTICE of any original Open Game Content you Distribute.

7. Use of Product Identity: You agree not to Use any Product Identity, including as an indication as to compatibility, except as expressly licensed in another, independent Agreement with the owner of each element of that Product Identity. You agree not to indicate compatibility or co-adaptability with any Trademark or Registered Trademark in conjunction with a work containing Open Game Content except as expressly licensed in another, independent Agreement with the owner of such Trademark or Registered Trademark. The use of any Product Identity in Open Game Content does not constitute a challenge to the ownership of that Product Identity. The owner of any Product Identity used in Open Game Content shall retain all rights, title and interest in and to that Product Identity.

8. Identification: If you distribute Open Game Content You must clearly indicate which portions of the work that you are distributing are Open Game Content.

9. Updating the License: Wizards or its designated Agents may publish updated versions of this License. You may use any authorized version of this License to copy, modify and distribute any Open Game Content originally distributed under any version of this License.

10. Copy of this License: You MUST include a copy of this License with every copy of the Open Game Content You Distribute.

11. Use of Contributor Credits: You may not market or advertise the Open Game Content using the name of any Contributor unless You have written permission from the Contributor to do so.

12. Inability to Comply: If it is impossible for You to comply with any of the terms of this License with respect to some or all of the Open Game Content due to statute, judicial order, or governmental regulation then You may not Use any Open Game Material so affected.

13. Termination: This License will terminate automatically if You fail to comply with all terms herein and fail to cure such breach within 30 days of becoming aware of the breach. All sublicenses shall survive the termination of this License.

14. Reformation: If any provision of this License is held to be unenforceable, such provision shall be reformed only to the extent necessary to make it enforceable.

15. COPYRIGHT NOTICE
Open Game License v 1.0 Copyright 2000, Wizards of the Coast, Inc.
______________________________________________________________________________
