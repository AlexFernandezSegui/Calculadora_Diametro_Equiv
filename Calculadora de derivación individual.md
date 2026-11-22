# Calculadora de derivación individual

Sección de los conductores, protección, cortocircuito y tubo según REBT ITC-BT-15, en cobre o aluminio, en tubo o enterrada.

## Datos del suministro

Sistema

Monofásico 230 V Trifásico 400 V

Conductor

Cobre Aluminio

Potencia prevista (kW)

Longitud (m)

cos φ

Caída de tensión máxima

Cable e instalación

Conductividad

Factor de corrección Agrupamiento o temperatura

Protección (fusible / IGA)

Icc en el origen de la derivación (kA) En la centralización de contadores. Déjalo vacío para no comprobar el cortocircuito.

## Resultado

## Todas las secciones para estos datos

## Criterios aplicados

- Sección mínima de 6 mm² en fases, neutro y protección, y 1,5 mm² en el hilo de mando (rojo). Neutro igual a la fase. En aluminio se parte de 16 mm², la menor sección habitual de fabricación.
- Aluminio: conductividad 35 a 20 °C, 30 a 70 °C y 28 a 90 °C. Al aire, la intensidad admisible se estima como 0,78 veces la del cobre de igual sección. Es una aproximación: confírmala con la tabla de aluminio de la norma.
- Enterrada: tablas 4 (aluminio) y 5 (cobre) de la ITC-BT-07 para cables 0,6/1 kV con aislamiento XLPE, terreno a 25 °C, 0,7 m de profundidad y 1 K·m/W, multiplicadas por 0,8 por ir bajo tubo. En monofásico se usa el mismo valor que en trifásico, que queda del lado de la seguridad. Corrige otras condiciones con el factor de corrección.
- Cortocircuito: la impedancia aguas arriba se deduce de la Icc en el origen (230 V / Icc). Icc mínima al final = 0,95·230 / (Z origen + 2·L/(γ·S)) con el conductor caliente, y debe superar la corriente de fusión en 5 s del fusible gG. Icc máxima al final con el conductor a 20 °C, para elegir el poder de corte del IGA. El cable aguanta t = (k·S/Icc)², con k = 115 o 143 en cobre y 76 o 94 en aluminio (70 o 90 °C). Compara ese tiempo con la curva del fusible.
- Caída de tensión: S = 2·L·P / (γ·e·U) en monofásico y S = L·P / (γ·e·U) en trifásico, con e en voltios. No incluye la reactancia, que empieza a pesar en secciones grandes.
- Intensidad admisible: tabla 1 de la ITC-BT-19 (aire a 40 °C), métodos B1 y B2. Compruébala con la UNE-HD 60364-5-52 vigente y con el catálogo del fabricante.
- Protección: Ib ≤ In ≤ Iz. Conductor de protección según la tabla 2 de la ITC-BT-18.
- Tubo: diámetro exterior mínimo de 32 mm y hueco para ampliar la sección un 100 %. El valor es orientativo, tomado de la tabla 5 de la ITC-BT-21 para la sección doble. En canalización enterrada consulta la tabla 9 de la ITC-BT-21.
- Es una ayuda de cálculo. El resultado no sustituye al proyecto o la memoria técnica del instalador.