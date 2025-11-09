# ENTREGA ÚNICA - Reto 01

> Exporta este archivo como **PDF único** con nombre:  
> `apellido1_apellido2_nombre_FHW01_Tarea`  *(sin ñ ni tildes)*

## Índice

- [Portada]# Proyecto RA1 UT2
## Reto 01 - Investigación y desarrollo: Conectores y Slots
### Nombre: Apellido1 Apellido2 Nombre
### Curso: Fundamentos de Hardware

- [1. Introducción](#1-introduccion)
- [2. Conectores internos (energía)](#2-conectores-internos-energia)
- [3. Conectores de datos](#3-conectores-de-datos)
- [4. Slots de expansión](#4-slots-de-expansion)
- [5. Conectores externos](#5-conectores-externos)
- [6. Bibliografía](#6-bibliografia)

<a id="portada"></a>
# Proyecto RA1 UT2
## Reto 01 - Investigación y desarrollo: Conectores y Slots
### Nombre: Apellido1 Apellido2 Nombre
### Curso: Fundamentos de Hardware
### Fecha: 09/11/2025


<a id="1-introduccion"></a>
Este proyecto recopila fichas técnicas de los principales conectores y slots actuales de un PC, con el objetivo de documentar su funcionamiento, compatibilidad y características técnicas según fuentes oficiales.  
Se incluyen conectores internos, de datos, slots de expansión y conectores externos.


<a id="2-conectores-internos-energia"></a>

# ATX 24 Pines

**Descripción breve:** Conector principal de alimentación de la placa base. Suministra energía a todos los circuitos lógicos y componentes base del sistema.
**Pines/Carriles/Voltajes/Velocidad:** 24 pines (20+4 en versiones antiguas), 3.3 V / 5 V / 12 V / -12 V.
**Uso principal:** Alimentación general de la placa base (chipset, ranuras PCIe, memorias, etc.).
**Compatibilidad actual:** Alta

## Identificación física
-Gran conector rectangular de 24 pines (a veces 20+4).
-Codificación por muescas para evitar conexión incorrecta.
-Generalmente con cables de colores desde la fuente de alimentación.
-Ubicado en el borde derecho de la placa base (zona principal de energía).

## Notas técnicas
-Estándar ATX12V 2.x definido por FormFactors.org.
-Compatible hacia atrás con versiones de 20 pines.
-Requiere una fuente ATX que cumpla con el estándar 2.0 o superior.

## Fotos
![Conector ATX 24 pines](../../../assets/img/10-conectores_internos/atx24_01.jpg "Conector ATX 24 pines")

## Fuente
https://es.wikipedia.org/wiki/ATX
https://www.profesionalreview.com/2018/11/10/alimentacion-atx-24-pines-eps
https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
https://www.geeknetic.es/Guia/2251/Conectores-ATX-de-Fuentes-de-Alimentacion-Todos-los-tipos-y-versiones.html

# Conector 12VHPWR / 12V-2x6

**Descripción breve:** Nuevo estándar de conector de alta potencia para tarjetas gráficas modernas (como las NVIDIA RTX 40XX).
**Pines/Carriles/Voltajes/Velocidad:** 12 pines + 4 de señal (sense), 12 V hasta 600 W.
**Uso principal:** Alimentación de GPUs de gama alta.
**Compatibilidad actual:** Alta (solo en GPUs recientes)

## Identificación física
-Conector compacto rectangular de 16 pines totales.
-Cable más grueso y firme que los tradicionales PCIe.
-Se ubica en las GPUs modernas de la serie RTX 40.

## Notas técnicas
-Sustituye a los conectores PCIe de 6/8 pines.
-Diseñado por PCI-SIG para reducir el número de cables y mejorar la eficiencia.
-Incluye sensores “sense” para evitar sobrecorriente.

## Fotos
![Conector 12VHPWR / 12V-2x6](../../../assets/img/10-conectores_internos/12VHPWR_12V-2x6.jpg "Conector 12VHPWR / 12V-2x6")

## Fuente
https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
https://en.wikipedia.org/wiki/12VHPWR

# EPS 8 Pines (4+4)

**Descripción breve:** Conector de alimentación dedicado al procesador (CPU). Proporciona energía directa al VRM (regulador de voltaje) del socket.
**Pines/Carriles/Voltajes/Velocidad:** 8 pines (divisible en 4+4), 12 V DC.
**Uso principal:** Alimentación del procesador, especialmente en placas base de gama media y alta.
**Compatibilidad actual:** Alta

## Identificación física
-Conector cuadrado de 8 pines (a veces separable 4+4).
-Colores amarillos y negros.
-Ubicado cerca del socket del procesador (parte superior de la placa).

## Notas técnicas
-EPS12V forma parte del estándar ATX12V.
-Versiones modernas usan conectores adicionales (8+8 pines) para -CPUs de alto consumo.
-Compatible con conectores de 4 pines antiguos (menor potencia).

## Fotos
![EPS 8 Pines (4+4)](../../../assets/img/10-conectores_internos/eps_8_pines.jpg "EPS 8 Pines (4+4)")

## Fuente
https://www.profesionalreview.com/2018/11/10/alimentacion-atx-24-pines-eps
https://es.wikipedia.org/wiki/ATX
https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
https://www.geeknetic.es/Guia/2251/Conectores-ATX-de-Fuentes-de-Alimentacion-Todos-los-tipos-y-versiones.html

# Conector PCIe 6/8 pines

**Descripción breve:** Conector auxiliar de alimentación para tarjetas gráficas y otros dispositivos PCIe de alto consumo.
**Pines/Carriles/Voltajes/Velocidad:** 6 u 8 pines, 12 V.
**Uso principal:** Suministro de energía adicional a GPUs y tarjetas PCIe.
**Compatibilidad actual:** Alta

## Identificación física
-Conector rectangular de 6 o 8 pines (a veces 6+2).
-Ubicado en el extremo superior de las tarjetas gráficas.
-Cables amarillos y negros procedentes de la PSU.

## Notas técnicas
-PCIe 6 pines: hasta 75 W adicionales.
-PCIe 8 pines: hasta 150 W adicionales.
-Algunos adaptadores combinan varios conectores para gráficas de alta potencia.

## Fotos
![Conector PCIe 6/8 pines](../../../assets/img/10-conectores_internos/PCIe_6_8_pines.jpg "Conector PCIe 6/8 pines")

## Fuente
https://www.ultralibrarian.com/blog/power-supply-pcie-power-pin-layout-best-practices
http://jongerow.com/PCIe/index.html

# Conector SATA Power

**Descripción breve:** Conector plano de energía usado para alimentar discos duros, SSDs y unidades ópticas modernas.
**Pines/Carriles/Voltajes/Velocidad:** 15 pines, 3.3 V / 5 V / 12 V.
**Uso principal:** Suministro de energía a dispositivos de almacenamiento SATA.
**Compatibilidad actual:** Alta

## Identificación física
-Conector plano, delgado, con forma de “L” invertida.
-Cable flexible con 15 contactos metálicos.
-Se encuentra en las salidas de la fuente de alimentación.

## Notas técnicas
-Sustituyó al conector Molex en unidades modernas.
-Admite hot-swap en sistemas que lo soportan.
-No intercambiable con el conector de datos SATA (aunque similar en forma).

## Fotos
![Conector SATA Power](../../../assets/img/10-conectores_internos/sata_power.jpg "Conector SATA Power")

## Fuente
https://en.wikipedia.org/wiki/SATA#SATA_power_connectors
https://tripplite.eaton.com/learn/sata-cables-and-speeds



<a id="3-conectores-de-datos"></a>
# M.2 (NVMe / SATA)

**Descripción breve:** Slot compacto que permite instalar SSDs de alto rendimiento y módulos de red (Wi-Fi/Bluetooth). Sustituye a los conectores mSATA y mini PCIe.  
**Pines/Carriles/Voltajes/Velocidad:** Hasta 67 pines / PCIe x4, SATA o USB / hasta 32 Gb/s (NVMe PCIe 3.0x4).  
**Uso principal:** Almacenamiento SSD y tarjetas de red integradas.  
**Compatibilidad actual:** Alta

## Identificación física

- Conector plano, sin cables, con una muesca (tipo M, B o B+M) según el modo de comunicación.  
- Los módulos M.2 se fijan con un tornillo en el extremo.  
- Situado directamente sobre la placa base, cerca del chipset o ranuras PCIe.

## Notas técnicas

- Modos compatibles: SATA o PCIe (NVMe).  
- M.2 tipo **B** usa hasta PCIe x2 o SATA; tipo **M** usa PCIe x4.  
- Las unidades NVMe son significativamente más rápidas que las SATA.  
- Compatibilidad depende del soporte del chipset/BIOS.  
- Longitudes estándar: 2242, 2260, 2280 y 22110 (22 mm de ancho, largo variable).

## Fotos

![Conector M.2 NVMe/SATA](../../../assets/img/11-conectores_datos/SSD_M.2.jpg "M.2 (NVMe / SATA)")

## Fuentes

-https://www.geeknetic.es/Guia/2251/Conectores-ATX-de-Fuentes-de-Alimentacion-Todos-los-tipos-y-versiones.html
-Manual de la placa base

# SATA (Datos)

**Descripción breve:** Conector estándar para la transmisión de datos entre la placa base y dispositivos de almacenamiento como HDD, SSD o unidades ópticas.  
**Pines/Carriles/Voltajes/Velocidad:** 7 pines / hasta 6 Gb/s (SATA III) / señal diferencial.  
**Uso principal:** Conectar discos duros, SSD y unidades ópticas modernas.  
**Compatibilidad actual:** Alta

## Identificación física

- Conector delgado y en forma de “L”, tanto en el cable como en el puerto.
- Color habitual: negro o rojo.
- Se encuentra agrupado junto a los conectores SATA de alimentación en los dispositivos de almacenamiento.

## Notas técnicas

- Versiones: SATA I (1.5 Gb/s), SATA II (3 Gb/s), SATA III (6 Gb/s).  
- Totalmente retrocompatible entre versiones (funciona a la menor velocidad común).  
- Cable de datos independiente del de alimentación.  
- Distancia máxima recomendada: 1 m.  
- No confundir con SATA Power (15 pines, alimentación).

## Fotos

![SATA (Datos)](../../../assets/img/11-conectores_datos/SATA_Data_Cable.jpg "SATA (Datos)")

## Fuentes

-https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
-Manual técnico del fabricante (placa base o SSD/HDD)

# M.2 (NVMe / SATA)

**Descripción breve:** Slot compacto que permite instalar SSDs de alto rendimiento y módulos de red (Wi-Fi/Bluetooth). Sustituye a los conectores mSATA y mini PCIe.  
**Pines/Carriles/Voltajes/Velocidad:** Hasta 67 pines / PCIe x4, SATA o USB / hasta 32 Gb/s (NVMe PCIe 3.0x4).  
**Uso principal:** Almacenamiento SSD y tarjetas de red integradas.  
**Compatibilidad actual:** Alta

## Identificación física

- Conector plano, sin cables, con una muesca (tipo M, B o B+M) según el modo de comunicación.  
- Los módulos M.2 se fijan con un tornillo en el extremo.  
- Situado directamente sobre la placa base, cerca del chipset o ranuras PCIe.

## Notas técnicas

- Modos compatibles: SATA o PCIe (NVMe).  
- M.2 tipo **B** usa hasta PCIe x2 o SATA; tipo **M** usa PCIe x4.  
- Las unidades NVMe son significativamente más rápidas que las SATA.  
- Compatibilidad depende del soporte del chipset/BIOS.  
- Longitudes estándar: 2242, 2260, 2280 y 22110 (22 mm de ancho, largo variable).

## Fotos

![M.2 (NVMe / SATA)](../../../assets/img/11-conectores_datos/SSDs_with_U.2_interface.jpg "M.2 (NVMe / SATA)")

## Fuentes

-https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
- Manual de la placa base



<a id="4-slots-de-expansion"></a>
# Slot: M.2 (NVMe / SATA / Wi-Fi)

**Descripción breve:** Slot de expansión compacto usado principalmente para unidades SSD y módulos inalámbricos. 
**Pines/Carriles/Voltajes/Velocidad:** 75 pines · PCIe x4 / SATA · hasta 64 Gb/s (Gen4 x4)
**Uso principal:** SSD NVMe/SATA, módulos Wi-Fi y Bluetooth.
**Compatibilidad actual:** Alta

## Identificación física
-Zócalo pequeño horizontal (22 mm ancho).
-Claves o muescas “B”, “M” o “B+M” según tipo de dispositivo.
-Suele ubicarse cerca del chipset o la GPU.

## Notas técnicas
-Compatible con dispositivos NVMe (PCIe) y SATA.
-El rendimiento depende de la generación PCIe soportada por la placa.
-Algunos puertos M.2 comparten líneas con SATA, desactivando puertos al usarse.

## Fotos
![Slot: M.2 (NVMe / SATA / Wi-Fi)](../../../assets/img/12-slots_expansion/PCIe.jpg "Slot: M.2 (NVMe / SATA / Wi-Fi)")

## Fuentes
- https://en.wikipedia.org/wiki/PCI_Express
- https://www.hp.com/us-en/shop/tech-takes/pcie-slots
- https://es.wikipedia.org/wiki/PCI_Express

<a id="5-conectores-externos"></a>
# Conector externo: DisplayPort 1.4 / 2.x

**Descripción breve:** Salida de vídeo digital de alta resolución, alternativa profesional a HDMI.
**Pines/Carriles/Voltajes/Velocidad:** 20 pines · hasta 32.4 Gb/s (1.4) / 80 Gb/s (2.0)
**Uso principal:** Monitores de alta resolución, estaciones de trabajo, portátiles
**Compatibilidad actual:** Alta

## Identificación física
-Conector rectangular con un lado biselado.

-Variante mini disponible en portátiles y tablets.
## Notas técnicas
-Soporta MST (Multi-Stream Transport) para múltiples monitores.

-Compatible con adaptadores HDMI/DVI.

## Fotos
![DisplayPort 1.4 / 2.x](../../../assets/img/20-conectores_externos/displayport.jpg "DisplayPort 1.4 / 2.x")

## Fuentes
- https://www.profesionalreview.com/conectores-y-puertos-de-un-pc-guia-completa

# Conector externo: HDMI 2.1

**Descripción breve:** Salida de vídeo y audio digital hasta 8K, usada en monitores y TVs modernos.
**Pines/Carriles/Voltajes/Velocidad:** 19 pines · hasta 48 Gb/s · HDR / 8K / 60-120 Hz
**Uso principal:** Conexión de monitores, TVs y proyectores
**Compatibilidad actual:** Alta

## Identificación física
-Conector rectangular con forma trapezoidal.

-Panel trasero de placas base, gráficas y televisores.

## Notas técnicas
-Soporta eARC, Dynamic HDR y tasas de refresco altas.

-Retrocompatible con HDMI 1.4 / 2.0.

## Fotos
![HDMI 2.1](../../../assets/img/20-conectores_externos/HDMI.jpg "HDMI 2.1")

## Fuentes
- https://www.profesionalreview.com/conectores-y-puertos-de-un-pc-guia-completa

# Conector externo: RJ-45 (Ethernet 1G / 2.5G / 10G)

**Descripción breve:** Conector de red por cable para conexión LAN.

**Pines/Carriles/Voltajes/Velocidad:** 1 Gbps / 2.5 Gbps / 10 Gbps

**Uso principal:** Conexión a redes cableadas y routers

**Compatibilidad actual:** Alta

## Identificación física
-Conector rectangular con pestillo de cierre.

-Panel trasero de placas base y equipos de red

## Notas técnicas
- Admite PoE (Power over Ethernet) en algunos modelos.

-Compatible con Cat5e / Cat6 / Cat6a / Cat7 según velocidad.

-Distancia máxima recomendada: 100 m por cable.

## Fotos
![RJ-45 (Ethernet 1G / 2.5G / 10G)](../../../assets/img/20-conectores_externos/rj45.jpg "RJ-45 (Ethernet 1G / 2.5G / 10G)")

## Fuentes
- https://www.profesionalreview.com/conectores-y-puertos-de-un-pc-guia-completa

# Conector externo: USB-A 2.0 / 3.x

**Descripción breve:** Puerto rectangular clásico para conectar periféricos.
**Pines/Carriles/Voltajes/Velocidad:** 4 pines (2.0) / 9 pines (3.x) · hasta 5 / 10 Gb/s
**Uso principal:** Teclados, ratones, memorias USB, periféricos
**Compatibilidad actual:** Alta

## Identificación física
-Puerto rectangular estándar, colores indican versión (negro 2.0, azul 3.x, turquesa 3.1/3.2).

-Panel trasero y frontal de PCs y portátiles.

## Notas técnicas
- Retrocompatible con versiones anteriores.

-Admite hasta 900 mA (3.0) por puerto.

-Forma no reversible.

## Fotos
![USB-A 2.0 / 3.x](../../../assets/img/20-conectores_externos/USB_A.jpg "USB-A 2.0 / 3.x")

## Fuentes
- https://edraw.wondershare.es/diagrama-de-cableado-usb.html

# Conector externo: USB-B

**Descripción breve:** Puerto cuadrado, habitual en impresoras, escáneres y periféricos.
**Pines/Carriles/Voltajes/Velocidad:** 4 pines · hasta 480 Mb/s (USB 2.0) / 5 Gb/s (USB 3.0)
**Uso principal:** Conexión de impresoras y periféricos al PC
**Compatibilidad actual:** Media

## Identificación física
-Conector cuadrado con bordes biselados superiores.

-Ubicado en periféricos, no en PCs.

## Notas técnicas
- No reversible.

-Compatible con USB 1.1 / 2.0.

-Adaptadores permiten conexión a USB-A.

## Fotos
![USB-B](../../../assets/img/20-conectores_externos/USB_B.jpg "USB-B")

## Fuentes
- https://edraw.wondershare.es/diagrama-de-cableado-usb.html

# Conector externo: USB-C / USB4

**Descripción breve:** Conector reversible de alta velocidad usado para datos, carga y vídeo.
**Pines/Carriles/Voltajes/Velocidad:** 24 pines · USB4 hasta 40 Gb/s / Power Delivery hasta 100 W
**Uso principal:** Transferencia de datos rápida, carga de dispositivos, salida de vídeo
**Compatibilidad actual:** Alta

## Identificación física
-Conector ovalado y simétrico (reversible).

-Color variable según fabricante.

-Panel trasero de placas base y portátiles.

## Notas técnicas
- Compatible con Thunderbolt 3/4 en algunos sistemas.

-Admite Power Delivery (PD) hasta 100 W.

-Compatible con versiones anteriores USB 3.x mediante adaptador.

## Fotos
![USB-C / USB4](../../../assets/img/20-conectores_externos/USB_C.jpg "USB-C / USB4")

## Fuentes
- https://edraw.wondershare.es/diagrama-de-cableado-usb.html

<a id="6-bibliografia"></a>
https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
https://en.wikipedia.org/wiki/12VHPWR
https://es.wikipedia.org/wiki/ATX
https://www.profesionalreview.com/2018/11/10/alimentacion-atx-24-pines-eps
https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
https://www.geeknetic.es/Guia/2251/Conectores-ATX-de-Fuentes-de-Alimentacion-Todos-los-tipos-y-versiones.html
https://www.ultralibrarian.com/blog/power-supply-pcie-power-pin-layout-best-practices
http://jongerow.com/PCIe/index.html
https://en.wikipedia.org/wiki/SATA#SATA_power_connectors
https://tripplite.eaton.com/learn/sata-cables-and-speeds
https://www.geeknetic.es/Guia/2251/Conectores-ATX-de-Fuentes-de-Alimentacion-Todos-los-tipos-y-versiones.html
-Manual de la placa base
https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
-Manual técnico del fabricante (placa base o SSD/HDD)
https://ibertronica.es/blog/actualidad/fuentes-atx-alimentacion
- Manual de la placa base
https://www.profesionalreview.com/conectores-y-puertos-de-un-pc-guia-completa
https://www.profesionalreview.com/conectores-y-puertos-de-un-pc-guia-completa
https://www.profesionalreview.com/conectores-y-puertos-de-un-pc-guia-completa
https://edraw.wondershare.es/diagrama-de-cableado-usb.html
