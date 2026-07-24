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

* ---

## 8. Cajas de Empotrar para Cuadros Eléctricos

Las cajas se eligen según **tres factores clave**:

* **Nº de Módulos (Ancho DIN):** Cada módulo mide 17,5 mm. Tamaños habituales: **4, 6, 8, 12, 18, 24, 36 módulos**.
  * *Recomendación:* Aconsejar siempre dejar un **20-30% de módulos libres** para futuras ampliaciones (aire acondicionado, paneles solares, cargador de coche).
* **Tipo de Pared:**
  * **Obra / Ladrillo:** Caja de plástico rígido liso para fijar con yeso/mortero.
  * **Pladur / Pared Hueca:** Lleva **garras metálicas/plásticas con tornillos** laterales para presionar la placa de cartón yeso.
* **Uso y Entorno:**
  * **IP40:** Uso estándar en interior de viviendas.
  * **IP65:** Estanqueidad alta contra agua y polvo (para exterior, garajes o trasteros).

---

## 9. Peines de Conexión (Puentes de Unión)

Pletinas de cobre aisladas que conectan varios magnetotérmicos en paralelo en la misma fila sin acumular cables:

* **Monofásicos (L+N):** Para cuadros de vivienda estándar (pasa Fase y Neutro en patillas alternadas).
* **Trifásicos (3P o 3P+N):** Para instalaciones comerciales o industriales trifásicas.
* Se eligen por número de módulos (ej: 12, 24 módulos) o en tiras recortables.

---

## 10. Magnetotérmicos: Simple (1P+N) vs. Doble (2P)

<table style="width: 100%; border-collapse: collapse; margin-top: 10px;">
  <thead>
    <tr style="background-color: #f2f2f2; text-align: left;">
      <th style="padding: 8px; border: 1px solid #ddd;">Tipo</th>
      <th style="padding: 8px; border: 1px solid #ddd;">¿Qué corta?</th>
      <th style="padding: 8px; border: 1px solid #ddd;">¿Qué detecta/protege?</th>
      <th style="padding: 8px; border: 1px solid #ddd;">Ancho</th>
      <th style="padding: 8px; border: 1px solid #ddd;">Uso Principal</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 8px; border: 1px solid #ddd;"><strong>1P + N</strong><br>(Estándar Vivienda)</td>
      <td style="padding: 8px; border: 1px solid #ddd;">Corta <strong>Fase y Neutro</strong></td>
      <td style="padding: 8px; border: 1px solid #ddd;">Protege solo en la <strong>Fase</strong></td>
      <td style="padding: 8px; border: 1px solid #ddd;"><strong>1 Módulo</strong><br>(17,5 mm)</td>
      <td style="padding: 8px; border: 1px solid #ddd;">Cuadros de vivienda habituales (ahorra espacio).</td>
    </tr>
    <tr>
      <td style="padding: 8px; border: 1px solid #ddd;"><strong>2P</strong><br>(Doble Completo)</td>
      <td style="padding: 8px; border: 1px solid #ddd;">Corta <strong>Fase y Neutro</strong></td>
      <td style="padding: 8px; border: 1px solid #ddd;">Protege en <strong>Fase y Neutro</strong></td>
      <td style="padding: 8px; border: 1px solid #ddd;"><strong>2 Módulos</strong><br>(35 mm)</td>
      <td style="padding: 8px; border: 1px solid #ddd;">Uso industrial, comercios o redes con interferencias.</td>
    </tr>
  </tbody>
</table>

---

## 11. Esquema Unifilar Básico de un Cuadro de Vivienda

Así se distribuye la corriente desde la entrada principal hasta cada circuito de la casa:

<pre style="white-space: pre; font-family: monospace; overflow-x: auto;">
[ Entrada de Red / Contador ]
              │
              ▼
    [ ICP ] (Control de Potencia)
              │
              ▼
    [ IGA ] (General - p.ej. 25A) ───► [ Protector Sobretensiones ]
              │
              ▼
    [ ID ] (Diferencial 30mA / Clase AC o Superinmunizado)
              │
     ┌────────┴────────┬───────────────┬───────────────┐
     ▼                 ▼               ▼               ▼
 [PIA C1]          [PIA C2]        [PIA C3]        [PIA C4]
  (10A)             (16A)           (20A)           (25A)
   │                 │               │               │
 Iluminación       Enchufes         Lavadora /       Cocina /
 (1,5 mm²)        (2,5 mm²)       Termo (4 mm²)   Horno (6 mm²)
</pre>

---

### Orden de Instalación en el Carril DIN:
1. **Entrada:** Llegada de Fase y Neutro al **IGA**.
2. **Protección de picos:** Del IGA deriva o se conecta el **Protector de Sobretensiones**.
3. **Seguridad personal:** Del IGA / Sobretensiones pasa al **Diferencial (ID)**.
4. **Reparto por zonas:** Salida del Diferencial hacia el **Peine de conexión** que alimenta por arriba a todos los **PIAs** (C1, C2, C3, C4, C5...).

