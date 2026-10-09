# Calculadora REBT

Cambios
Beta 2 (9-10-2026)

Nuevo:

Tipo de línea "Interiores (no vivienda)" (ITC-BT-19): circuitos libres con caída del 3 % en alumbrado y 5 % en otros usos, o 4,5 % y 6,5 % con transformador propio.
Recargos por receptor: un motor al 125 % (ITC-BT-47, ap. 3.1); línea a varios motores, con lista de motores y 125 % del mayor (ap. 3.2 y 3.3); ascensores y grúas con comprobación del 5 % en el arranque (ITC-BT-32); lámparas de descarga con 1,8 VA por vatio (ITC-BT-44).
Locales con riesgo de incendio o explosión: intensidad admitida reducida un 15 % (ITC-BT-29, ap. 9.1).
Caída disponible: límite, más el sobrante de la derivación individual, menos la caída ya gastada aguas arriba (ITC-BT-19, ap. 2.2.2).
Botón "Continuar desde esta línea", que guarda cada tramo calculado y lo descuenta en el siguiente.
Interruptores de más de 125 A tratados como regulables: basta Imax ≤ Icab y se indica el margen de ajuste. Afecta a interiores que no son vivienda y a vehículo eléctrico.
Botón "Restablecer datos".
Tipos de línea agrupados en redes y acometidas, instalación de enlace e instalación interior.

Corregido:

Al cambiar la forma de instalación se reiniciaban la potencia, la longitud, el material y el esquema.

Criterios fijados:

En motores, el 125 % se aplica a la intensidad que debe admitir el cable. La caída de tensión y el interruptor se calculan con la intensidad a plena carga.
El coeficiente 1,3 de ascensores y grúas no se aplica a la sección: la ITC-BT-47, ap. 6, lo usa solo para la relación de intensidad de arranque.
Sin sección mínima en interiores que no son vivienda: el REBT no fija ninguna general.
Beta 1 (8-10-2026)

Primera versión publicada: línea general de alimentación, derivación individual, vivienda, vehículo eléctrico, red subterránea y red aérea, con criterio REBT o e-distribución (NRZ103) en instalaciones de enlace.

Versión beta 1 (8-10-2026).

Calculadora de sección de cable, caída de tensión y protección para instalaciones eléctricas de baja tensión según el REBT. Es una sola página (`index.html`) que funciona en el navegador, sin servidor y sin conexión.

## Tipos de línea

- Línea general de alimentación (ITC-BT-14)
- Derivación individual (ITC-BT-15)
- Circuitos de vivienda (ITC-BT-25)
- Recarga de vehículo eléctrico (ITC-BT-52)
- Red subterránea (ITC-BT-07)
- Red aérea trenzada (ITC-BT-06)

## Qué calcula

- Intensidad máxima de la línea (Imax) e intensidad admitida por el cable (Icab)
- Sección por caída de tensión y por intensidad, con neutro, protección y tubo
- Fusible o interruptor (Iprot) con las condiciones Imax ≤ Iprot ≤ Icab e I2 ≤ 1,45 · Icab
- Criterio REBT o e-distribución (NRZ103) en instalaciones de enlace
- Modo de comprobación de una sección existente y resumen para copiar

## Fuentes

- REBT, texto consolidado del BOE a 3-9-2025
- Guía técnica de aplicación: anexo 2 (caídas de tensión) y BT-22
- UNE-HD 60364-5-52:2022, según recopilación de Prysmian
- Guía de interpretación NRZ103, edición 7, de e-distribución

## Aviso

Cálculo orientativo. No sustituye al proyecto ni a la memoria técnica, y la empresa distribuidora determina la solución final de la instalación de enlace.

## Licencia

© 2026 east101. Esta obra está bajo licencia Creative Commons
Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0).
https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es
