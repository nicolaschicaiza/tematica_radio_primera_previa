# Ecuaciones Primer Previa Radiocomunicaciones

[TOC]

## Capítulo 1 -- Fundamentos de Radiopropagación

#### Velocidad de la Luz:

$$
    c = f·\lambda \left[\frac{m}{s}\right], c=3·10^8 \left[\frac{m}{s}\right]
$$

### Ondas electromagnéticas conocidas y estudiadas 

| Tipo de Onda | Rango de Frecuencias Hz |
|--------------|-------------------------|
| Radiocomunicaciones | $3 \times 10^3 - 3 \times 10^{11}$ |
| Ondas calóricas | $3 \times 10^{11} - 3 \times 10^{13}$ |
| Rayos infrarrojos | $3 \times 10^{13} - 3 \times 10^{14,2}$ |
| Luz visible | $3 \times 10^{14,2} - 3 \times 10^{14,8}$ |
| Rayos ultravioleta | $3 \times 10^{14,8} - 3 \times 10^{17}$ |
| Rayos X | $3 \times 10^{16} - 3 \times 10^{19}$ |
| Rayos Gama | $3 \times 10^{19,2} - 3 \times 10^{22}$ |
| Rayos Cósmicos | $3 \times 10^{22} - 3 \times 10^{28}$ |

### Bandas de Frecuencia
---

| Banda No. | Rango de Frecuencias | Subdivisión Métrica | Abreviatura | Designación | Servicios Típicos |
|-----------|----------------------|---------------------|-------------|-------------|-------------------|
| 4 | 3 -- 30 KHz | Mm | VLF | Muy baja frecuencia | Navegación, sonar. |
| 5 | 30 -- 300 KHz | Km | LF | Baja frecuencia | Radio Guia, ayudas a la navegación. |
| 6 | 0.3 -- 3 MHz | Hm | MF | Media frecuencia | Radiodifusión AM, Servicios Marítimos. |
| 7 | 3 -- 30 MHz | Dm | HF | Alta frecuencia | Telefonía, telégrafo, banda ciudadana, comunicaciones mar -- tierra y mar -- aire. |
| 8 | 30 -- 300 MHz | m | VHF | Muy alta frecuencia | Televisión, Radiodifusión FM, control tráfico aéreo, ayudas a la navegación. |
| 9 | 0.3 -- 3 GHz | dm | UHF | Ultra alta frecuencia | Televisión, hornos domésticos, comunicaciones satélite, radares de vigilancia. |
| 10 | 3 -- 30 GHz | cm | SHF | Súper alta frecuencia | Radares embarcados, de policía de aeropuertos, comunicaciones vía satélite, radio enlaces, televisión por cable. |
| 11 | 30 -- 300 GHz | mm | EHF | Extremadamente alta frecuencia | Radar, localización de misiles |
| 12 | 300 -- 3000 GHz | dmm | -- | -- | -- | -- |

#### Bandas de Microondas

| Designación Microonda | Frecuencia |
|-----------------------|------------|
| L  | 1 -- 2 GHz |
| S  | 2 -- 4 GHz |
| C  | 4 -- 8 GHz |
| X  | 8 -- 12 GHz |
| Ku | 12 -- 18 GHz |
| K  | 18 -- 27 GHz |
| Ka | 27 -- 40 GHz |

#### Región de bandas de frecuencia

| Región | Zonas Incluidas |
|--------|-----------------|
| Región I | Europa, África, Siberia, Oriente Medio |
| Región II | América del Sur y del Norte |
| Región III | Austalia, Sureste Asiático, Pacífico Sur |

### Mecanismos de Propagación
------


#### Radiador Isotrópico

Es una antena **Teórica** o hipotética de tipo ideal la cual radia la misma energía en todas las direcciones. 

* Ganancia 0dB
* Potencia Isotrópica Radiada Equivalente (PIRE)

#### Dipolo Elemental

De manera general consiste en un hilo conductor cuya longitud dependerá de la frecuencia de trabajo.  

* Longitud típica de $\lambda$.
* Habitual en frecuencias < 1MHz
* poco Ancho de Banda
* Baja eficiencia

#### Antena Yagi

Corresponde a un arreglo de dipolos que me permiten controlar el patrón de radiación, la ganancia y la directividad del elemento radiante.

* Controlar la ganancia
* Controlar la directividad
* Controlar la Polarización

#### Antenas Parabólicas

El principio se base en la reflexión de las ondas electromagnéticas que inciden paralelamente al eje principal y se concentran en el eje focal.

* Alta directividad
* Poca eficiencia (60%)

#### Onda Terrestre -- Onda Superficial

Aquella que se propaga sobre la superficie de la tierra y su alcance está determinado por la potencia con la cual es transmitida y las características del terreno que atraviesa.

| Propiedad | Valor | 
|-----------|-------|
| Antena | Verticales, muy grandes |
| Bandas | VLF (3-30KHz), LF (30-300KHz), MF (300KHz--3MHz) y parte baja de HF (3-10MHz) |
| Potencia | Orden de Kilovatio [Kw] |
| Perdidas | Muy altas, señal absorbida por la tierra |
| Polarización | Vertical, le permite caminar sobre la tierra |
| Uso | Comunicaciones de radio difusión |


#### Onda Terrestre -- Línea de Vista

Aquella que viaja desde el emisor al receptor sin tocar la superficie terrestre, ni llegar a la ionosfera.

| Propiedad | Valor | 
|-----------|-------|
| Atenuación | valores bajos |
| Perdidas | Características climáticas |
| Potencia | Orden de Vatios [W]
| Alcance  | 100 Km máx. |
| Bandas   | VHF, UHF y SHF (30MHz -- 30GHz) |

#### Onda espacial -- Vía Ionósfera

Aquella que llega hasta ionosfera y la atraviesa, parte de ella es reflejada y/o refractada por dicha capa, siendo devuelta a la tierra.

| Propiedad | Valor | 
|-----------|-------|
| Transmisión | Inestable y depende del grado de ionización de la ionosfera |
| Bandas | HF (3--30MHz), comunicaciones de onda corta|
| Potencia | Orden de Vatios [W] cubre grandes distancias durante cortos periodos de tiempo |
| Otras  | Mayor cantidad de electrones, mayor capacidad de reflejar las altas frecuencias, se pueden dar múltiples reflexiones ionosfera/tierra |

### Fenómenos Físicos de Propagación
---

#### Refracción

Consecuencia de la distinta velocidad de la radiación en dos medios. Se observa un brusco cambio de la dirección del haz de radiación al pasar de un medio a otro con distinto índice de refracción (refracción de la luz).

* La frecuencia es la misma en los dos medios.
* La velocidad cambia al pasar de un medio a otro.
* Existe una relación entre el ángulo de incidencia y el ángulo de refracción.

#### Reflexión

Cuando la radiación cruza una superficie de separación entre dos medios de diferente índice de refracción, parte de la radiación se refracta, pero otra parte vuelve por el mismo camino.

* Reflexión en superficies rugosas: reflexión difusa.
* Reflexión en superficies pulidas: reflexión especular.

#### Multitrayecto

Es un fenómeno que ocurre cuando a la antena de recepción llega la señal de trayectoria directa y otras señales resultantes de la reflexión de la señal en diferentes superficies.

La señal de trayectoria directa puede reflejarse, provocando la recepción de varias copias. Las copias múltiples pueden reforzar o cancelar la señal directa.

#### Difracción

Ocurre cuando se distorsiona una onda por un obstáculo cuyas dimensiones son comparables a la longitud de onda de la radicación.

### Unidades Logarítmicas
---

#### El Decibelio (dB)

Es una unidad relativa que se utiliza, sobre todo, en acústica y comunicaciones para expresar la relación entre potencia o energías.
$$
    A = 10 \log{\frac{P_2}{P_1}} [dB]; \text{ Amplificación, sí } P_1<P_2,\text{ Atenuación, sí } P_2<P_1
$$
Indica solamente la relación entre dos magnitudes. Dependiendo de la magnitud, se habla de unidades absolutas: dBw, dBm.
$$
    1 mW \rightarrow dBmW\text{ ó }dBm \rightarrow P(dBm) = 10 \log{\frac{P}{1mW}}
$$
$$
    1 W \rightarrow dBW \rightarrow P(dBW) = 10 \log{\frac{P}{1W}}
$$

#### dBm

Se define como el nivel de potencia de dB con relación a 1mW, es decir:

$$
    P(dBm)=10\log{\frac{P_1(mW)}{P_2(=1mW)}} [dB]
$$
$$
    P(mW)=10^{\frac{P(dBm)}{10}}
$$

#### dBv

Indica el valor de tensión en dB con relación a 1V, es decir:

$$
    V(dBv)=20\log{\frac{V_2(V)}{V_1(=1V)}} [dB]
$$
$$
    P(mW)=10^{\frac{V(dBv)}{20}}
$$

#### Resto de unidades

| Magnitud | Referencia | Nivel absoluto | Expresión |
|----------|------------|----------------|-----------|
| **Potencia eléctrica $(p)$** | 1mW <br> 1W <br> 1kW | L(dBm) <br> L(dBw) <br> L(dBk)| $L(dBm) = 10\log{p(mW)}$ <br> $L(dBw) = 10\log{p(W)}$ <br> $L(dBk) = 10\log{p(kW)}$ | 
| **Tensión eléctrica $(v)$** | 0,775V <br> 1mV <br> 1$\mu$V | L(dBv) <br> L(dBj) <br> L(dBu)| $L(dBv) = 20\log{\frac{v(V)}{0,775}}$ <br> $L(dBj) = 20\log{v(mV)}$ <br> $L(dB\mu) = 20\log{v(\mu V)}$ | 
| **Campo eléctrica $(E)$** | 1$\frac{\mu V}{m}$ | L(dBu)| $L(dB\mu) = 20\log{E(\frac{\mu V}{m} )}$ | 

#### Operaciones

##### Conversión
$$
    dBk \stackrel{-30dB}{\longleftarrow} dBw \stackrel{+30dB}{\longrightarrow} dBm
$$

##### Unidades adimensionales (dB)
* $$
    dB + dB = dB, \text{ ampificación}
$$
* $$
    dB - dB = dB, \text{ atenuación}
$$

##### Unidades dimensionales (dBm, dBw, dBk)

* $$
    dBm + dB = dBm
$$
* $$
    dBm + dBm = N/A\\ \text{ No existe operación en Sx de comunicaciones que represente: } \\10 \log{P_2·P_1}= 10 (\log{P_2} + \log{P_1})
$$
* $$
    dBm - dB = dBm
$$
* $$
    dBm - dBm = dB\\
    10 \log{\frac{P_2(mW)}{P_1(mW)}}=10 (\log{P_2} - \log{P_1}) [dB]
$$

### Parámetros del Sistema
---

##### Parámetros Transmisor

* $Ltt$: Pérdida en los circuitos terminales.
* $Gt$: Ganancia directiva para el transmisor.
* $Pt$: Potencia transmitida. 
* $PIRE$: Potencia Isotrópica Efectivamente Radiada.
* $PRA$: Potencia Radiada Aparente.
* $L_c$: Atenuación del medio de transmisor.
* $G_a$: Ganancia de la antena de transmisión.

##### Parámetros Receptor

* $Ltr$: Pérdidas en los circuitos terminales.
* $Gr$: Ganancia directiva para el receptor.
* $Pr$: Potencia receptor.

##### Parámetros Espacio Libre

* $Lb$: Pérdidas básicas de propagación.
* Función de la frecuencia.
* $d$: Distancia.
* Medio.
* Altura de antena.
* Modo de propagación.

#### Potencia Isotrópica Radiada Equivalente (P.I.R.E)

$$
    PIRE_{dBm} = P_t[dBm] - L_c[dB] + G_a[dBi]
$$

$$
    PIRE_{dBm} = PRA_{dBm} + 2,15[dB]
$$

#### Potencia Radiada Aparente (P.R.A.)

$$
    PRA_{dBm} = P_t[dBm] - L_c[dB] + G_a[dBd]
$$

$$
    PRA_{dBm} = PIRE_{dBm} - 2,15[dB]
$$

### Ganancia

Medida de la direccionalidad de la antena. Es la potencia emitida en una dirección concreta comparada con otra antena.

##### Ganancia Isotrópica (Gi)

Si se emplea como referencia una antena isotrópica en espacio libre, su unidad de medida es $dBi$ que significa decibelios respecto a una antena isotrópica.

$$
    dBi = dBd + 2,15[dB]
$$

##### Ganancia de dipolo de media longitud de onda (Gd)

Si la antena de referencia es un dipolo $\frac{\lambda}{2}$ en espacio libre, su unidad de medida es $dBd$ que significa decibelios respecto a una antena de dipolo.

$$
    dBd = dBi - 2,15[dB]
$$

##### Ganancias de antenas respecto a una isotrópica como referencia

| Antena | Gi(dB) |
|--------|--------|
| Isotrópa en espacio libre | 0 |
| Dipolo de Hertz en espacio libre | 1,76 |
| Dipolo $\lambda$/2 en espacio libre | 2,15 |
| Antena vertical corta | 4,77 |
| Dipolo de Hertz sobre plano conductor | 4,77 |
| Mono polo $\lambda$/4 sobre plano conductor | 5,18 |

#### Polarización de la onda radiada

Propiedad de OEM radiada que describe las variaciones temporales del vector del campo eléctrico para un punto del espacio, observadas en la dirección de propagación.

* Polarización lineal
* Polarización circular
* Polarización elíptica

#### Intensidad del campo eléctrico

$$
    e = \sqrt{\frac{30P_t[W]}{d^2}} = \frac{\sqrt{30P_t[W]}}{d} \left[\frac{V}{m}\right], \text{ Potencia de transmisión PIRE ó PRA. }
$$

$$
    e \left[\frac{dBv}{m}\right] = 20 \log{\frac{e(\frac{v}{m})}{1(\frac{v}{m})}} [dB]
$$

#### Pérdidas en el espacio libre

En la medida que la distancia aumenta, la señal se dispersa por una zona (esfera) más grande, lo cual disminuye la señal recibida. Las perdidas son mayores para frecuencias más altas (longitudes de onda menores).

#### Absorción atmosférica

El vapor de agua y el oxígeno de la atmósfera absorben las señales de radio y producen pérdidas

* La lluvia y la niebla dispersan las ondas de radio

#### Potencia recibida

$$
    P_r = P_t G_r \left(\frac{\lambda}{4\pi d}\right)^2
$$

#### Pérdidas de espacio libre

$$
    \frac{P_t}{P_r} = \left(\frac{4\pi d}{\lambda}\right)^2
$$

$$
    L_{fs}(dB)=32,45 + 20 \log (D_{km}) + 20 \log (F_{MHz})
$$

#### Desvanecimiento

Es la variación en el nivel de la señal que llega al extremo receptor, es un efecto indeseado porque el sistema deja de operar correctamente.

* Desvanecimientos
$$
    F_1 = P_o - P_1, t=t_1 \\
    F_2 = P_o - P_2, t=m_m
$$

* Duración del desvanecimiento 1
$$
    \tau_1 = t_2 - t_1 
$$

### Ruido
---

**Ruido predominante**, ruido térmico, limita la sensibilidad del receptor.

#### Ruido Térmico

* Figura de ruido típica
$$
    3 dB - 4 dB
$$
* Tolos los cuerpos con una temperatura diferente de $0^\circ K$ desprenden radiación incoherente (ruido). 
* Potencia de ruido disponible ne ruido térmico.
$$
    N = k T B \left[\frac{W}{Hz}\right]\\
    k: \text{Cte. de Boltzman=}1,32\times 10^{-23} \left[\frac{J}{K}\right]\\
    B: \text{Ancho de Banda de Ruido} \left[Hz\right]\\
    T: \text{Temperatura de Ruido de antena} [K]
$$

#### Densidad espectral de potencia

$$
    N_0 = kT
$$

#### Temperatura ambiente (290°K)
$$
    N_{dBw}=-204 + 10 \log(B_{Hz})
$$

#### Umbral de ruido térmico en un receptor a temperatura ambiente
$$
    P_n(dBw)=-204 + 10 log(B_{Hz}) + NF_{dB})
$$

#### Otros tipo de ruido
* Ruido Impulsivo
* Ruido Atmosférico
* Ruido de Intermodulación
* Ruido de Cósmico
* Ruido de la tierra

### Parámetros de Desempeño
---

#### Relación Señal a Ruido S/N

#### Relación $E_b/N_o$ 

#### Disponibilidad

Porcentaje de tiempo que el sistema puede brindar un servicio cumpliendo con una calidad determinada. La disponibilidad se mide en %, considerando como referencia un año (360 días). Ningún sistema de radiocomunicaciones tiene una disponibilidad del 100%, el canal radio tiene gran variación, por lo cual este valor siempre estará por debajo de 100%. Sistemas de gran calidad tiene D > 99,99%, sistemas de radio difusión pueden tener D > 90%.

**Ejemplo**:

Un enlace de comunicaciones entre la sede principal de un bando y una sucursal tiene una disponibilidad del 99%. ¿Cuantas horas esta fuera de servicio?
$$
    I = (100\% - 99\%)=1\%
$$

El sistema no esta disponible el 1% del tiempo.
$$
    360 \times 1\% = 3,6 \text{ días } \rightarrow 3,6 \text{ días }  \times 24 \text{ horas} = 86,4 \text{ horas} 
$$

#### Indisponibilidad
$$
    \text{Indisponibilidad} = (100\% - \text{disponibilidad})\\
    I = (100\% - D)
$$

## Capítulo 2 -- Propagación por Onda de Superficie

* Presente en las bandas de LF (30KHz -- 300KHz), MF (300KHz -- 3000KHz) y parte baja de HF (hasta 10MHz)
* Se propaga en la discontinuidad tierra -- aire debido a las corrientes inducidas en la tierra.
* Propaga la polarización vertical, porque la polarización horizontal se atenúa muy rápidamente debido al carácter conductor de la superficie de la tierra en estas frecuencias.
* El alcance varía con la frecuencia, la potencia transmitida y el tipo de suelo (tierra seca, húmeda, mar).
* En LF se puede conseguir alcances de 2000 Km, en MF de hasta 300 Km, en frecuencias más altas como HF, apenas se llega a los 50 Km.
* Las aplicaciones más importantes son los sistemas de comunicaciones navales y los sistemas de radiodifusión (LF y onda media en AM).
* Las antenas que se utilizan habitualmente son monopolos verticales con alturas entre 50 y 200 m que radian polarización vertical.
* Estable ante perturbaciones.
* Ancho de banda reducido.
* Potencias altas del orden de Kw a Mw.

### Características eléctricas de la tierra.
---

* La propagación depende de la frecuencia y del tipo de suelo.
* La caracterización correcta del suelo es fundamental para una correcta predicción de la propagación.
* El suelo se caracteriza como un dieléctrico con pérdidas definido por los parámetros de permitividad relativa y conductividad.
* Las características de absorción de la tierra dependen del tipo de terreno.

| Tipo de Superficie | $\epsilon$ | $\sigma \frac{\Omega}{m}$ |
|--------------------|------------|---------------------------|
| Agua de Mar   | 80    | $4 - 5$ |
| Agua Dulce    | 84    | $1\times 10^{-3} - 1 \times 10^{-2}$ |
| Terreno muy Húmedo    | 30    | $5\times 10^{-3} - 1 \times 10^{-2}$ |
| Terreno Ártico    | 15    | $5\times 10^{-4}$ |
| Terreno muy Seco    | 3    | $5\times 10^{-5} - 1 \times 10^{-4}$ |
| Hielo Polar    | 3    | $2.5\times 10^{-5}$ |

### Intensidad de Campo Eléctrico.
---

#### Densidad de flujo de potencia en antena isotrópica
$$
    \varphi = \frac{pire[W]}{4\pi d^2 [m]} = \frac{|e|^2}{120 \pi}
$$

#### Intensidad de campo eléctrico: Ecuación Teórica.
$$
    e_{\frac{v}{m}} = \sqrt{30} \times \sqrt{\frac{pire[W]}{d^2[m]}} \left[* \sqrt{\frac{\frac{1}{1000^2}}{\frac{1}{1000^2}}} \right] \\
    e_{\frac{mv}{m}} = \sqrt{30000} \times \sqrt{\frac{pire[Kw]}{d^2[Km]}} = 173,2 \times \sqrt{\frac{pire[Kw]}{d^2[Km]}}
$$

*Recordar que:* $pire[Kw] = P_t[Kw] * g_i$
$$
    e_{\frac{mv}{m}} = 173,2 \times \sqrt{\frac{P_t[Kw]*g_i}{d^2[Km]}} = 173,2 \sqrt{g_i}\times \sqrt{\frac{P_t[Kw]}{d^2[Km]}}
$$

*Antena Monopolo Corto:*
* Antena vertical de altura inferior a la décima parte de la longitud de onda alimentada entre su extremo y el plano conductor.
* Para un Monopolo: Antena estándar (g=3), Figura de Mérito M (300 $\frac{mv}{m}$)
$$
    e_{\frac{mv}{m}} = 300 \times \sqrt{\frac{P_t[Kw]}{d^2[Km]}} \hspace{2cm} e_{\frac{\mu v}{m}} = 3\times 10^5 \times \sqrt{\frac{P_t[Kw]}{d^2[Km]}}
$$
*Figura de Mérito:* Intensidad de campo generado a 1Km con una potencia de 1Kw y una ganancia g.

Estas ecuaciones son el caso de propagación ideal, dado que no se considera el tipo de terreno ni la frecuencia, no se pueden emplear para el análisis de la propagación de una onda real.

Para la estimación del campo eléctrico se recurre a las curvas de intensidad de campo definidas por la ITU, que han sido obtenidas empíricamente.

#### Intensidad de campo eléctrico: Modelo de Tierra Esférica.

* La UIT-R proporciona gráficas que modelan la intensidad de campo producida por una antena transmisora, de tipo Monopolo corto con potencia radiada de 1Kw, en función de la frecuencia, la distancia y el tipo de terreno.

* Estas curvas consideran la difracción que produce la curvatura de la Tierra.

* $$
    e_{dB\frac{\mu v}{m}} = 3 \times 10 ^5 \sqrt{\frac{P_t[Kw]}{d^2[Km]}} \\ 
    \text{El campo eléctrico } e \text{ relativo a una distancia } d(Km) \text{ de un radiador estándar (g=3), está} \\ \text{cuantificado en curvas de nivel de campo relativo.}
$$
* $$
    E_{dB\frac{\mu v}{m}} = 20 \log \left( 3 \times 10^5 \sqrt{\frac{P_t[Kw]}{d^2[Km]}}\right) \\
    \text{Las curvas toman como referencia una antena vertical cuyo campo radiado a 1 kilómetro es }\\ 300 \frac{mV}{m} \text{ o de manera equivalente 109,54} dB\frac{\mu v}{m}.
$$

##### Campo Eléctrico Real $E_R$

*El Campo Eléctrico E para cualquier tipo de antena, cualquier distancia y cualquier potencia de transmisión, se determina por:*
$$
    E_{R_{dB\frac{\mu v}{m}}} = E_{r_{dB\frac{\mu v}{m}}} + 20 \log{\left(\frac{M}{300} \sqrt{P_t[Kw]}\right)}
$$
* $E_r$ es el campo de referencia encontrado en las curvas dadas por la recomendación P.368-9.
* $E_R$ es el campo real generado por la potencia de transmisión configurada.
* $M$ es la figura de meritó, $M = 173,2 \sqrt{g}$.
* Ganancia de antena $g$ en veces.

| Tipo de antena | Figura de mérito M |
|----------------|--------------------|
| Estándar  | 300   |
| Isotrópica    | 173,2   |
| $\frac{\lambda}{4}$   | 314   |
| $\frac{\lambda}{2}$   | 222   |


#### Pérdidas Totales de Propagación.
$$
    L_{tot} = L_{abs} + L_{disp}
$$

* **Pérdidas por dispersión:** Independientes de la frecuencia y tipo de terreno, se obtienen empleando el campo generado debido a la dispersión de la onda en el espacio libre. Este campo corresponde a la línea punteada que se encuentra sobre toda las curvas de intensidad de campo definidas en la recomendación.  
*Nota:* En todas estas curvas la línea punteada es igual.  
Se considera como referencia el inicio de las curvas (109,54 dBu), al cual se le resta el valor de campo obtenido de la curva para una cierta distancia.
$$
    L_{disp} = 109,54 - E_r
$$

* **Pérdidas totales de propagación:** 
Dependen de la frecuencia y características eléctricas de la tierra. Resultan de la diferencia del valor de referencia de las curvas (109,54) y el campo obtenido a una cierta distancia.
$$
    L_{tot} = 109,57 - E_r 
$$
Sí la potencia de transmisión es diferente de 1Kw o sí no se trata de una antena estándar, en vez de tomar el campo eléctrico de referencia, se toma el campo eléctrico real según esas condiciones.
$$
    L_{tot} = 109,57 - E_R 
$$
* **Pérdidas por absorción:** Dependen de la frecuencia y características eléctricas de la tierra. Resultan de la diferencia de pérdidas totales y las de dispersión.
$$
    L_{abs} = L_{tot} - L_{disp}
$$
### Zona de Servicio
---

* **Zona de servicio:** Región de cobertura donde la OEM, tiene un nivel aceptable y no está sometida a niveles interferentes intersistema.
* **Condición de no interferencia CNI:** Es el nivel de campo eléctrico máximo permitido de la señal interferente, que otros sistemas que operan en la misma frecuencia pueden producir, sobre la frontera de la ZS de un sistema. 
* **Distancia mínima:** Separación Mínima entre estaciones vecinas que operan en la misma frecuencia que garantice la ZS y la CNI para cada estación.

* $E_{SZA}\_$ : Usuarios que tengan un nivel de señal superior o igual a este umbral forman parte de la zona de servicio.  
* $CNI_A$: Ninguna emisión proveniente de otra estación debe superar esta intensidad de campo.


#### Sistema de difusión AM -- Plan Técnico Nacional de AM

Para sistemas AM se debe analizar la posible interferencia con estaciones que se encuentren en la misma frecuencia o dentro del margen de separación requerido. Los parámetros de las estaciones se encuentran definidos en el Plan Técnico Nacional de AM.

*Sistemas de difusión AM (535 a 1705KHz)*
* Las antenas de transmisión deben estar fuera de las zonas Urbanas.
* BW canal: 10KHz o 20KHz, si no, causa interferencias.
* Separación mínima de frecuencias 40KHz.
* Offset de 10Hz.
* Enlace estudio -- estación: UHF.
* Cumplir con las normas internaciones de exposición a radiación.

| Tipo de estación | Potencia de operación | Zona de Servicio día | Zona de Servicio noche | Condición no interferencia día | Condición no interferencia noche |
|------------------|-----------------------|----------------------|------------------------|--------------------------------|----------------------------------|
| A | 10 a 250 Kw | 500 $\frac{\mu V}{m}$ | 1250 $\frac{\mu V}{m}$ | 250 $\frac{\mu V}{m}$ | 650 $\frac{\mu V}{m}$ |
| B | 5 a 10 Kw | 1250 $\frac{\mu V}{m}$ | 6500 $\frac{\mu V}{m}$ | 625 $\frac{\mu V}{m}$ | 3250 $\frac{\mu V}{m}$ |
| C | 1 a 5 Kw | 1250 $\frac{\mu V}{m}$ | 10000 $\frac{\mu V}{m}$ | 625 $\frac{\mu V}{m}$ | 5000 $\frac{\mu V}{m}$ |
| D | Max. 250 W | 3500 $\frac{\mu V}{m}$ | 10000 $\frac{\mu V}{m}$ | 1750 $\frac{\mu V}{m}$ | 5000 $\frac{\mu V}{m}$ |

#### Distancia Mínima

Para instalar estaciones operando en la misma frecuencia o dentro del rango no permitido, la distancia entre dichas estaciones debe ser tal, que no permita la interferencia mutua entre estaciones.

Si dos estaciones transmisoras están operando en la misma frecuencia, es necesario mantener una distancia de separación entre ellas para evitar se interfieran mutuamente. Esta distancia mínima se determina según las zonas de servicio y las condiciones de no interferencia establecías según su clasificación en cuanto a tipo de estación con se aprecia anteriormente.

La zona que es sometida a interferencia proveniente de ambas estaciones en el sistema se conoce como **zona de nadie**.

La mayor entre estas dos distancias mínimas, será la distancia que debe existir entre las dos estaciones para no generar interferencia entre sistemas.

#### Interpolación

Se considera la herramienta matemática necesaria para encontrar de manera aproximada el valor de un parámetro en función de otro, a partir de parejas de valores correspondientes que están bien definidos y son evaluables. En general conociendo un par de valores ($x_1, y_1$) y ($x_2, y_2$) se pueden interpolar para determinar el valor de y correspondiente a un valor $x$ así:
$$
    y = y_2 - (y_2 - y_1)\frac{(x_2 - x)}{x_2-x_1} \hspace{1cm} ó \hspace{1cm} y = y_1 + (y_2 - y_1)\frac{(x-x_1)}{x_2-x_1} \\
    \hspace{5.5cm}\text{siempre que } x_1<x<x_2\text{, }y_1<y<y_2
$$

##### Ejemplo
Hallar el valor del campo $E$ a una distancia de 100 Km, para un enlace que trabaja con los datos: frecuencia = $750 \text{KHz}$, conductividad $\sigma = 10^{-13}$ u.e.m.  
**Solución**
Como las curvas de campo disponibles no contienen exactamente la frecuencia de 750 KHz, entonces interpolamos con dos valores disponibles de frecuencia una mayor y la otra menor, por ejemplo f1 = 700 KHz y f2 = 1000 KHz. Luego de la gráfica para $\sigma = 10^{-13}$ u.e.m, sacamos:
$$
   E1(f1,d) = 58 dB\mu \hspace{2cm} E2(f2,d)=52dB\mu 
$$
Ahora analizamos los parámetros así. Sí $f1<f<f2$ entonces $E1>E>E2$ porque a medida que aumenta la frecuencia, aumentan las pérdidas y por lo tanto disminuye el valor del campo. Entonces la relación de interpolación será:
$$
\text{forma uno: } E = E1 - (E1 - E2)\frac{(f - f1)}{f2-f1} = 58 - (58 - 52)\frac{(750 - 700)}{1000 - 700} = 57dB\mu \\
    \\
    \text{forma dos: } E = E2 + (E1 - E2)\frac{(f2 - f)}{f2-f1} = 52 + (58 - 52)\frac{(1000 - 750)}{1000 - 700} = 57dB\mu
$$
