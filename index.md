# Manual de Conceptos Básicos de Electricidad y Protección

## 1. Componentes del Cuadro General de Mando y Protección (CGMP)

El cuadro eléctrico organiza la distribución y protección de las líneas de la vivienda:

* **ICP (Interruptor de Control de Potencia):** Controla que no se supere la potencia contratada con la compañía eléctrica.
* **IGA (Interruptor General Automático):** Protege la instalación contra cortocircuitos y sobrecargas generales. Corta la corriente si se supera la capacidad máxima de la línea.
* **PCS / SURGET (Protector de Sobretensiones):** Protege los equipos electrónicos contra picos de tensión (por ejemplo, impactos de rayos o fallos en la red).
* **ID (Interruptor Diferencial):** Protege a las personas frente a contactos directos e indirectos. Salta cuando detecta una fuga de corriente a tierra.
* **PIA (Pequeños Interruptores Automáticos):** Protegen cada circuito individual de la casa (iluminación, enchufes, electrodomésticos, etc.) frente a sobrecargas y cortocircuitos.

---

## 2. Tipos de Corriente

* **Corriente Alterna (AC):**
  * Es la que llega a las viviendas y comercios.
  * Cambia de sentido y polaridad periódicamente.
  * Permite transportar la energía a grandes distancias con menores pérdidas.
* **Corriente Continua (DC):**
  * Es el tipo de corriente que generan los **paneles solares fotovoltaicos** y las baterías.
  * Fluye siempre en el mismo sentido con polaridad constante.
  * Para consumirse en la vivienda, requiere de un **inversor** que la transforme de DC a AC.

---

## 3. Dimensionamiento de Cableado por Circuito

Sección de conductor de cobre según el uso normalizado:

| Circuito | Uso / Aplicación | Sección Mínima |
| :--- | :--- | :--- |
| **C1** | Iluminación | 1,5 mm² |
| **C2** | Tomas de uso general y frigorífico | 2,5 mm² |
| **C3** | Lavadora, lavavajillas y termo eléctrico | 4 mm² |
| **C4** | Cocina y horno | 6 mm² |
| **C5** | Tomas de corriente de baño y cocina | 2,5 mm² |

---

> **Nota:** La sección adecuada del cable garantiza evitar calentamientos en la línea y pérdidas de tensión innecesarias.
> ---

## 4. Tipos de Magnetotérmicos (PIAs) y Características

Los Pequeños Interruptores Automáticos (PIAs) protegen las líneas individuales frente a sobrecargas y cortocircuitos:

* **Corte Bipolar (1P+N / 2P):** Cortan tanto la **Fase** como el **Neutro**. Es la norma estándar en instalaciones residenciales para garantizar la seguridad total al maniobrar o ante un fallo en el circuito.
* **Curva de Disparo tipo C:** Es el estándar en viviendas. Salta rápido ante cortocircuitos pero tolera pequeños picos de arranque habituales en electrodomésticos comunes.

---

## 5. Tipos de Interruptores Diferenciales (ID)

Protegen a las personas frente a fugas de corriente a tierra. La sensibilidad habitual en viviendas es de **30 mA**:

* **Clase AC (Estándar):** Detecta fugas de corriente alterna puras. Apto para circuitos básicos de iluminación y cargas simples.
* **Clase A / Superinmunizado (SI):**
  * **¿Por qué usarlo?:** Los electrodomésticos modernos con electrónica avanzada, variadores de frecuencia, placas de inducción, aires acondicionados e inversores solares generan armónicos y corrientes continuas pulsantes que pueden hacer saltar un diferencial normal (disparos intempestivos).
  * **Ventaja:** Evita saltos en falso causados por ruido de la red o interferencias electrónicas y garantiza protección real ante fugas con componente continua.

---

## 6. Potencias Contratadas Habituales y Calibre Principal (IGA)

Relación orientativa entre la potencia contratada de la vivienda, la corriente máxima aproximada y el IGA recomendado:

| Potencia Contratada (Monofásica 230V) | Calibre del IGA Recomendado | Uso habitual |
| :--- | :--- | :--- |
| **3,45 kW** | 16 A | Viviendas pequeñas con equipamiento básico / gas |
| **4,6 kW** | 20 A | Vivienda estándar con vitrocerámica y aire acondicionado |
| **5,75 kW** | 25 A | Vivienda equipada / termo eléctrico + climatización |
| **9,2 kW** | 40 A | Vivienda con elevado consumo eléctrico / aerotermia |

---

## 7. Código de Colores Normalizado para Cableado

* **Fase:** Marrón, Negro o Gris.
* **Neutro:** Azul claro.
* **Toma de Tierra:** Franjas Verde y Amarilla.
