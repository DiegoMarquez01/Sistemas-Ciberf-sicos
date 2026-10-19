---
layout: default
title: Ejercicio introductorio — Presupuestos
nav_order: 2
---

# Ejercicio introductorio: Presupuesto limitado ($20,000 MXN) vs. presupuesto ilimitado

**Autor:** Diego Márquez Esqueda

---

## Importancia de los costos y la selección de componentes en un proyecto

En cualquier proyecto de ingeniería, y en particular en un sistema ciberfísico, el diseño no termina cuando "funciona". Cada componente elegido (un procesador, un sensor, un microcontrolador, una fuente de alimentación) tiene un **costo**, una **disponibilidad** y unas **restricciones técnicas** que afectan al resto del sistema. Por eso, la selección de componentes y la elaboración del presupuesto son parte del diseño, no un trámite al final.

Algunas razones por las que esta etapa es tan importante:

- **El presupuesto define el alcance.** Con recursos limitados hay que priorizar qué es indispensable y qué es deseable; con recursos amplios, el reto es no sobredimensionar ni gastar en algo que el usuario no va a aprovechar.
- **Los componentes no son independientes.** Un procesador condiciona la tarjeta madre (socket y chipset), la tarjeta madre condiciona el tipo de memoria, y el consumo de todo el conjunto condiciona la fuente de poder. Un error de compatibilidad puede dejar el sistema sin funcionar aunque cada pieza por separado sea buena.
- **El costo total no es solo el precio de las piezas.** También cuentan el envío, los impuestos, las licencias de software, la protección eléctrica, la garantía y un margen para imprevistos o cambios de precio.
- **La fuente de compra importa.** El mismo componente puede variar en precio, tiempo de entrega y garantía según el proveedor, y un proveedor poco confiable puede salir más caro a largo plazo.
- **Las decisiones deben poder justificarse.** Un presupuesto bien documentado (qué se eligió, por qué, cuánto cuesta y dónde se compra) permite que el cliente o el equipo tomen decisiones informadas y que el proyecto sea reproducible.

Este ejercicio, realizado al inicio del curso, aplica estas ideas a un caso cotidiano: armar una computadora de escritorio para un cliente, con dos escenarios de presupuesto muy distintos.

---

## Planteamiento del ejercicio

Un cliente desea construir una computadora de escritorio. El caso no especifica el uso que le dará (juegos, trabajo de oficina, edición, entretenimiento, etc.). Se plantean dos escenarios:

- **Caso A:** presupuesto limitado de **$20,000 MXN**.
- **Caso B:** presupuesto **ilimitado**.

Para cada caso se propone una configuración completa (unidad central y periféricos), con el precio aproximado de cada componente y la tienda donde puede comprarse.

---

## 1. Componentes base

Antes de cotizar, se definieron los componentes que debe tener un equipo completo y la función de cada uno:

| Categoría | Función |
|---|---|
| CPU | Procesamiento |
| Tarjeta madre | Compatibilidad y conexiones |
| RAM | Multitarea |
| Almacenamiento (SSD) | Velocidad de arranque y carga |
| Fuente de poder | Alimentación estable |
| Gabinete | Protección y flujo de aire |
| Sistema operativo | Software base |
| Monitor | Salida visual |
| Teclado y mouse | Entrada |
| Bocinas o audífonos | Audio |
| Webcam | Videollamadas |
| Regulador / No-break | Protección eléctrica |

*Tabla 1. Componentes base de un equipo de escritorio completo.*

---

## 2. Caso A — Presupuesto de $20,000 MXN

La estrategia fue cubrir un uso general (ofimática, navegación, videollamadas, multimedia y juegos ligeros) con el menor costo posible. Para ello se eligió un procesador con **gráficos integrados**, lo que elimina el gasto de una tarjeta de video dedicada, que suele ser el componente más caro.

### Unidad central (torre)

| Componente | Especificación sugerida | Precio aprox. (MXN) | Dónde comprarlo |
|---|---|---|---|
| Procesador | AMD Ryzen 5 5600G (gráficos integrados Radeon Vega 7, sin necesidad de tarjeta de video aparte) | $2,179 | Cyberpuerta |
| Tarjeta madre | ASUS PRIME A520M-K, socket AM4 | $849 | Cyberpuerta |
| Memoria RAM | Zunate, módulo DDR4 2666 MHz de 16 GB | $1,319 | Amazon México |
| Almacenamiento | Cusu SSD 512 GB | $1,191 | AliExpress |
| Fuente de poder | XPG PROBE 500 W 80+ Bronce | $689 | Cyberpuerta |
| Gabinete | XPG Starker Air, con 2 ventiladores instalados | $1,279 | Cyberpuerta |
| Sistema operativo | Windows 11 Home OEM | $2,309 | Cyberpuerta |
| **Subtotal torre** | | **$9,815** | |

*Tabla 2. Componentes de la torre, caso A.*

### Periféricos

| Componente | Especificación sugerida | Precio aprox. (MXN) | Dónde comprarlo |
|---|---|---|---|
| Monitor | Monitor 19'' Stylos Tech | $659 | Amazon México |
| Teclado y mouse | PERFECTCHOICE Kit | $299 | Amazon México |
| Bocinas | YOMYM Bocinas para PC de escritorio | $199 | Amazon México |
| Webcam | Autbye Cámara Web | $199 | Amazon México |
| Regulador | Koblenz Regulador RS-1410 | $378 | Amazon México |
| Audífonos | Naceb Audífonos con micrófono | $323 | Cyberpuerta |
| **Subtotal periféricos** | | **$2,057** | |

*Tabla 3. Periféricos, caso A.*

### Total caso A

| Concepto | Monto aprox. (MXN) |
|---|---|
| Torre completa | $9,815 |
| Periféricos | $2,057 |
| **Total estimado** | **$11,872** |
| Colchón de presupuesto (imprevistos, envío, ajuste de precios) | $8,128 |
| **Presupuesto disponible** | **$20,000** |

*Tabla 4. Resumen del caso A.*

> **Nota:** en la versión original del ejercicio, el subtotal de la torre aparecía como $7,636. Al sumar de nuevo los siete componentes de la Tabla 2 el resultado correcto es $9,815, por lo que el total y el colchón se corrigieron en este documento.

---

## 3. Caso B — Presupuesto ilimitado

Sin restricción económica, se buscó una configuración de gama más alta del mercado, capaz de cubrir cualquier uso: juegos en alta resolución, edición de video, modelado 3D o cargas de inteligencia artificial.

### Unidad central (torre)

| Componente | Especificación sugerida | Precio aprox. (MXN) | Dónde comprarlo |
|---|---|---|---|
| Procesador | AMD Ryzen 9 9950X3D, 16 núcleos, 5.7 GHz (socket AM5) | $12,889 | Cyberpuerta |
| Tarjeta gráfica | NVIDIA RTX 5090, 32 GB GDDR7 (ASUS ROG Astral) | $79,119 | Cyberpuerta |
| Memoria RAM | Kit Corsair Vengeance DDR5, 64 GB (2 × 32 GB), 6000 MHz | $19,308 | Amazon México |
| Almacenamiento | SSD NVMe Gen5 2 TB | $12,369 | Cyberpuerta |
| Tarjeta madre | X870E con Wi-Fi 7 y USB4 (socket AM5) | $7,389 | Mercado Libre |
| Fuente de poder | 1000 W 80+ Platinum | $2,139 | Cyberpuerta |
| Enfriamiento | AIO líquido 360 mm | $1,397 | Amazon México |
| Gabinete | Corsair 5000D AIRFLOW | $3,519 | Amazon México |
| Sistema operativo | Windows 11 Home OEM | $2,309 | Cyberpuerta |
| **Subtotal torre** | | **$140,438** | |

*Tabla 5. Componentes de la torre, caso B.*

> **Corrección de compatibilidad:** en la versión original la tarjeta madre aparecía como "X870E / Z890". El chipset **Z890 es para procesadores Intel** (socket LGA1851) y **no es compatible** con el Ryzen 9 9950X3D, que usa socket AM5. La opción correcta es únicamente una tarjeta **X870E** (o X870) para AM5.

### Periféricos

| Componente | Especificación sugerida | Precio aprox. (MXN) | Dónde comprarlo |
|---|---|---|---|
| Monitor | KTC Monitor curvo de 32 pulgadas | $3,389 | Amazon México |
| Teclado y mouse | Acteck 2 en 1, teclado ergonómico y mouse | $1,115 | Mercado Libre |
| Bocinas | Acteck Bocina para computadora | $1,579 | Cyberpuerta |
| Webcam | Logitech Webcam HD | $1,049 | Cyberpuerta |
| No-break | CyberPower PR1500LCD, línea interactiva, 1500 W | $12,619 | Cyberpuerta |
| Audífonos | JBL Audífonos con micrófono | $2,359 | Cyberpuerta |
| **Subtotal periféricos** | | **$22,110** | |

*Tabla 6. Periféricos, caso B.*

### Total caso B

| Concepto | Monto aprox. (MXN) |
|---|---|
| Torre completa | $140,438 |
| Periféricos | $22,110 |
| **Total estimado** | **$162,548** |
| **Presupuesto disponible** | **Ilimitado** |

*Tabla 7. Resumen del caso B.*

---

## 4. Comparación entre ambos casos

| Concepto | Caso A | Caso B | Relación B / A |
|---|---|---|---|
| Torre | $9,815 | $140,438 | ≈ 14.3 × |
| Periféricos | $2,057 | $22,110 | ≈ 10.7 × |
| **Total** | **$11,872** | **$162,548** | **≈ 13.7 ×** |
| Componente más caro | Windows 11 ($2,309, 24 % de la torre) | RTX 5090 ($79,119, 56 % de la torre) | — |

*Tabla 8. Comparación de costos entre los dos escenarios.*

Algunas observaciones de la comparación:

- En el caso A, el componente más caro de la torre es la **licencia del sistema operativo**, por encima del procesador. En presupuestos ajustados, el software y las licencias pesan mucho y no deben olvidarse.
- En el caso B, la **tarjeta gráfica sola representa más de la mitad del costo de la torre**. Esto es típico de los equipos de gama alta: la GPU es la que define el precio, y solo se justifica si el uso del cliente realmente la aprovecha (juegos en 4K, renderizado, IA).
- La licencia de Windows cuesta lo mismo en ambos casos, por lo que en proporción pesa casi 24 % de la torre en el caso A y menos de 2 % en el caso B.
- Mientras la torre subió ≈14 veces, los periféricos del caso B (salvo el no-break) siguen siendo de gama media, por lo que el equipo no quedó equilibrado (ver la revisión técnica).

---

## 5. Revisión técnica de las configuraciones

Al revisar el ejercicio con más detalle, vale la pena analizar si las piezas son compatibles entre sí y si la fuente de poder está bien dimensionada.

### 5.1 Compatibilidad

| Verificación | Caso A | Caso B |
|---|---|---|
| CPU ↔ tarjeta madre (socket y chipset) | Ryzen 5 5600G y A520M-K: ambos AM4 ✔. Conviene confirmar que el BIOS de la tarjeta soporte la serie Ryzen 5000G (algunas requieren actualización). | 9950X3D (AM5) con X870E ✔. **Z890 ✘** (es para Intel). |
| RAM ↔ tarjeta madre | DDR4 ✔. La A520M-K tiene 2 ranuras. | DDR5 ✔ (AM5 solo acepta DDR5). |
| Configuración de memoria | Un solo módulo de 16 GB trabaja en **un solo canal**. Como los gráficos integrados del 5600G usan la RAM como memoria de video, **2 × 8 GB en doble canal** darían bastante más rendimiento gráfico por un precio similar. Además, el 5600G soporta DDR4-3200, y el módulo de 2666 MHz lo limita. | 2 × 32 GB en doble canal ✔. Para Ryzen 9000, 6000 MHz es la velocidad recomendada. |
| GPU ↔ gabinete | No aplica (gráficos integrados). | La RTX 5090 ROG Astral mide ≈ 36 cm; el Corsair 5000D admite tarjetas de hasta ≈ 40 cm ✔. |
| Enfriamiento ↔ gabinete | Disipador incluido con el 5600G ✔. | El 5000D admite radiadores de 360 mm ✔. |
| Conector de alimentación de la GPU | No aplica. | La RTX 5090 usa el conector **12V-2x6** (16 pines); la fuente debe ser ATX 3.0/3.1 o incluir el adaptador correcto. |
| Almacenamiento | SSD de 512 GB: verificar si es SATA o M.2 NVMe y que la tarjeta tenga la ranura correspondiente. | NVMe Gen5: necesita una ranura M.2 PCIe 5.0 (las X870E la tienen) y buena disipación. |

*Tabla 9. Verificación de compatibilidad entre componentes.*

### 5.2 Consumo estimado y selección de la fuente

Una forma práctica de elegir la fuente es sumar el consumo máximo aproximado de cada componente y agregar un margen de seguridad de 20 a 30 %. Además, una fuente trabaja con mejor eficiencia cuando opera entre el 50 y el 80 % de su capacidad.

| Componente | Caso A (W) | Caso B (W) |
|---|---|---|
| Procesador | 65 (TDP del 5600G, ≈ 88 W pico) | 170 (TDP del 9950X3D, ≈ 230 W pico) |
| Tarjeta gráfica | — (integrada en el CPU) | 575 (TGP de la RTX 5090) |
| Tarjeta madre | ≈ 25 | ≈ 50 |
| Memoria RAM | ≈ 5 | ≈ 10 |
| Almacenamiento | ≈ 5 | ≈ 10 |
| Ventiladores / bomba AIO | ≈ 5 | ≈ 20 |
| **Consumo pico estimado** | **≈ 130 W** | **≈ 895 W** |
| Con margen de 25 % | ≈ 165 W | ≈ 1 120 W |
| **Fuente elegida** | **500 W 80+ Bronce** | **1000 W 80+ Platinum** |
| Evaluación | Sobrada: trabaja a ≈ 26 % de su capacidad. Una de 400–450 W sería suficiente, aunque la de 500 W deja espacio para agregar una tarjeta de video en el futuro. | Justa, a plena carga trabaja a ≈ 90 %. NVIDIA recomienda 1000 W como mínimo para la RTX 5090; por sus picos transitorios de consumo. |

*Tabla 10. Estimación de consumo y dimensionamiento de la fuente de poder. Valores aproximados con base en las especificaciones de los fabricantes.*

El mismo cálculo sirve para validar la protección eléctrica. En el caso A, el regulador de 1400 VA cubre de sobra el consumo del equipo. En el caso B, el no-break de 1500 W queda cerca del límite si se suma el monitor a un consumo pico de ≈900 W, aunque en uso normal está bien. Algo a considerar, un regulador solo estabiliza el voltaje, mientras que un no-break además da respaldo de batería ante apagones.

---

## Conclusiones

1. **Primero hay que preguntar, aunque el cliente no lo diga.** El caso no especificaba para qué se usaría la computadora, y esa es la pregunta más importante. Una PC de oficina, una para juegos y una para edición de video o IA llevan componentes completamente distintos. Antes de cotizar conviene preguntar el uso principal, el software que va a correr, la resolución de pantalla deseada, qué periféricos ya tiene el cliente, si necesita Wi-Fi, y cuánto espera que dure el equipo o si planea ampliarlo. Un presupuesto ilimitado no significa gastar todo, sino gastar en lo que el cliente va a aprovechar.

2. **Hay que verificar que los componentes embonen entre sí.** Cada pieza depende de otra: el procesador define el socket y el chipset de la tarjeta madre, la tarjeta madre define el tipo de RAM (DDR4 o DDR5), el número de ranuras y los puertos M.2, y la tarjeta de video debe caber en el gabinete y tener el conector de alimentación correcto. En este ejercicio, la opción "Z890" del caso B es un ejemplo claro: es una tarjeta de gama alta, pero no funciona con un procesador AMD. También importa *cómo* se instala cada pieza: un solo módulo de RAM contra dos en doble canal cambia notablemente el rendimiento de los gráficos integrados del caso A.

3. **La fuente de poder se elige con un cálculo, no por costumbre.** Se debe estimar el consumo de cada componente, sumar un margen de 20 a 30 % y elegir una fuente que opere cerca de la mitad de su capacidad en uso normal. En el caso A la fuente quedó sobrada; en el caso B quedó justa para una RTX 5090. Lo mismo aplica a la protección eléctrica: el regulador o no-break debe cubrir el consumo pico de todo el equipo, incluyendo el monitor.

4. **El presupuesto debe incluir lo que no se ve.** La licencia del sistema operativo fue el componente más caro de la torre en el caso A. Además, el envío, los impuestos, la garantía y la variación de precios entre tiendas justifican dejar un colchón, como se hizo en el caso A.

5. **El precio más bajo no siempre es el más barato.** Marcas poco conocidas o vendedores sin garantía pueden ahorrar dinero al inicio pero costar más si una pieza falla. En componentes críticos (fuente, almacenamiento, tarjeta madre) conviene priorizar la confiabilidad.

6. **Un buen presupuesto es un documento verificable.** Revisar el ejercicio permitió encontrar un error de suma ($7,636 en lugar de $9,815) y uno de compatibilidad (Z890). Es una buena razón para revisar siempre las cuentas y las especificaciones antes de entregar una cotización, y de preferencia hacer los cálculos en una hoja de cálculo y no a mano.
