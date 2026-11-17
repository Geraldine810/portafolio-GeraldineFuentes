[\[Geraldine Fuentes Opazo\]](#inicio)

[Sobre mí](#sobre-mi)[Casos de estudio](#casos)[Contacto](#contacto)

# Reportes en Power BI que reemplazan el Excel de todos los días.

Automatizo el seguimiento de inventario, ventas e indicadores para que tu equipo vea qué pasa hoy sin armar planillas.

[Ver casos de estudio](#casos)[Contactarme](#contacto)

## Sobre mí

### Quién soy

\[Escribe aquí 2 o 3 frases: tu nombre, tu profesión, de dónde eres y qué tipo de problemas disfrutas resolver con datos.\]
\[Mi nombre es Geraldine Fuentes, titulada de la carrera Ingenieria estadistica, resido actualmente en Concepción, Chile y disfruto mucho la automatatización de reporteria y todo lo que contenga datos.\]

### Habilidades

- Power BI
- DAX
- Modelado de datos
- Excel avanzado
- Automatización de reportes
- \[Otra herramienta\]

### Estudios

- **\[Título o carrera\]**\[Institución\] · \[años\]
- **\[Curso o certificación\]**\[Institución\] · \[año\]

### Experiencia

- **\[Cargo\]**\[Empresa\] · \[años\]. \[Una línea sobre lo que lograste.\]
- **\[Cargo anterior\]**\[Empresa\] · \[años\]. \[Una línea sobre lo que lograste.\]

## Casos de estudio

[Caso 1 · Retail · Power BI Inventario diario para una cadena de supermercados Reporte de 17 páginas que reemplazó un proceso manual en Excel: calcula la disponibilidad de productos en tienda, alerta quiebres y se actualiza solo. Ver caso de estudio](#caso-1) [Caso 2 · Alimentos · Power BI + HTML · En desarrollo In-stock y mermas para un proveedor de alimentos Reporte que consolida varias cadenas de supermercados, con visuales HTML a medida y tablas ordenadas por la última semana para priorizar lo más crítico. Ver caso de estudio](#caso-2) [Caso 3 · Consumo masivo · Power BI Abastecimiento de punta a punta en varios retailers Reporte de 7 páginas que cubre desde la catalogación hasta la venta, con marcadores para cambiar la vista y botones dinámicos para elegir qué tablas ver y exportar. Ver caso de estudio](#caso-4) [Caso 4 · Retail · Power BI · En desarrollo Reporte multimarca con fuentes unificadas Reporte construido desde cero para una empresa con dos marcas, que une información de fuentes distintas en un solo modelo y ofrece una vista por marca. Ver caso de estudio](#caso-3)

Caso 5

### \[Nombre del caso\]

\[Descripción breve del proyecto.\] Próximamente.

[Volver a los casos](#casos)

# Caso 1: Inventario diario para una cadena de supermercados

Un productor de alimentos frescos necesitaba controlar a diario la disponibilidad de sus productos en cientos de tiendas. El proceso era manual y los quiebres de stock se detectaban tarde. Construí un reporte que se actualiza solo y alerta de inmediato.

**17**páginas con navegación única

**\[N\]**productos en \[N\] tiendas

**\[X\] h a \[X\] min**preparación diaria

**100 %**automatizado

## Pantallas del reporte

### Disponibilidad en tres niveles

Problema

El seguimiento de disponibilidad en tienda se hacía a mano, con retraso y riesgo de errores.

Solución

Indicadores que calculan el producto en góndola, en tránsito y en bodega, con semáforos por día, formato y producto.

Resultado

El equipo ve de inmediato qué productos están bajo la meta.

### Del total nacional a cada tienda

Problema

No había una vista que conectara el panorama general con el detalle de cada tienda.

Solución

Barras apiladas de stock, tránsito y bodega con una línea de in-stock, y tablas por formato, región, comuna, tienda y producto.

Resultado

Se pasa del problema general a la tienda específica en pocos clics.

### Forecast: semana actual vs. siguiente

Problema

Los cambios de pronóstico entre semanas se detectaban tarde y a mano.

Solución

Comparación diaria con % de variación por producto y detalle por tienda.

Resultado

El equipo anticipa ajustes de producción y reposición.

Tienda 001Quiebre00 d

Tienda 002Sobre stock4521 d

Tienda 003Stock OK123 d

Tienda 004Stock fantasma60 d

Tienda 005Quiebre00 d

### Clasificación automática por tienda

Problema

Decidir dónde reponer y dónde frenar envíos exigía revisar tienda por tienda.

Solución

Una regla de negocio que cruza stock, tránsito, bodega, venta y forecast, y marca cada tienda como quiebre, sobre stock, stock OK o stock fantasma.

Resultado

Una lista lista para usar en la operación diaria.

1 de 4

Imágenes ilustrativas: los nombres, cifras y logos reales del cliente fueron ocultados.

### Puntos destacados

- **Automatización completa:** de un archivo Excel manual a un reporte que se actualiza solo.
- **KPIs calculados al instante:** IS1, IS+IT, IS+IT+IW, IS3, días de inventario, avance de forecast y mermas.
- **Fecha dinámica con DAX:** las tablas muestran siempre la última fecha disponible.
- **Semáforos y formato condicional** para detectar problemas de un vistazo.
- **Reglas de negocio automáticas:** quiebre, sobre stock, stock OK y stock fantasma.
- **Navegación y filtros uniformes** en las 17 páginas, con botón para reiniciar la vista.
- **Detalle completo:** del total nacional a cada tienda y producto, con histórico diario y semanal.

### Herramientas

- Power BI
- DAX
- Modelado de datos
- Excel (fuente)

[Volver a los casos](#casos)

# Caso 2: In-stock y mermas para un proveedor de alimentos

Un proveedor de fiambres vende en varias cadenas de supermercados y necesitaba ver en un solo lugar su disponibilidad en tienda, el forecast y las mermas. El cliente ya conocía un estilo de gráficos y quería mantenerlo, así que combiné Power BI con visuales HTML a medida. Reporte en desarrollo.

**3**cadenas consolidadas en un reporte

**12**semanas máximas visibles

**\[N\]**productos en \[N\] tiendas

**\[X\] h a \[X\] min**preparación del seguimiento

## Pantallas del reporte

Producto A · formato 138 %

Producto B · formato 262 %

Producto C · formato 185 %

Producto D · formato 396 %

Producto E · formato 2100 %

### Tablas ordenadas por la última semana

Problema

Las tablas nativas de Power BI no permiten ordenar por la última semana de menor a mayor, y el cliente tenía que buscar a mano dónde estaba el problema.

Solución

Tablas construidas en HTML que ordenan de menor a mayor por la semana más reciente, con semáforos de in-stock.

Resultado

Lo más crítico aparece siempre arriba, como una lista de prioridades.

### Vista siempre enfocada en lo reciente

Problema

Con todo el histórico a la vista, los gráficos se llenaban de información que ya no servía para decidir.

Solución

Una ventana móvil que muestra como máximo las últimas 12 semanas disponibles, con gráficos en HTML que mantienen el diseño que el cliente ya conocía.

Resultado

El reporte es más liviano y se lee de un vistazo.

### Mermas por mes, canal y producto

Problema

La merma se revisaba sin relación con la venta ni con el canal donde ocurría.

Solución

Evolución mensual de la merma en pesos, en unidades y como porcentaje de la venta, con detalle por canal, tienda y producto.

Resultado

El equipo identifica qué productos y tiendas concentran la pérdida.

1 de 3

Imágenes ilustrativas: los nombres, cifras y logos reales del cliente fueron ocultados.

### Puntos destacados

- **Power BI más HTML a medida:** los gráficos y tablas se construyeron en HTML para mantener el diseño que el cliente ya conocía y lograr ordenamientos que Power BI nativo no permite.
- **Orden por la última semana:** las tablas muestran arriba lo más crítico, de menor a mayor.
- **Ventana móvil de 12 semanas:** solo se ve lo reciente y relevante.
- **Varias cadenas en un solo reporte:** in-stock, in-stock más tránsito, días de inventario y forecast.
- **Control de mermas** en pesos, unidades y porcentaje de la venta.

### Herramientas

- Power BI
- HTML y CSS
- DAX
- Modelado de datos

[Volver a los casos](#casos)

# Caso 4: Reporte multimarca con fuentes unificadas

Una empresa con dos marcas necesitaba un reporte que no existía. Lo construí desde cero, con una vista para cada marca. El desafío principal fue que la información venía de varias fuentes distintas, así que conecté las bases y las unifiqué en un solo modelo de Power BI. Reporte en desarrollo.

**2**marcas, cada una con su propia vista

**\[N\]**fuentes de datos conectadas

**1**modelo unificado

**\[X\] h a \[X\] min**preparación del reporte

## Pantallas del reporte

Marca AMarca B

Actualización: dd/mm/aaaa hh:mm

### Portada de navegación

Problema

Cada marca tenía sus propios datos y no había un punto de entrada común.

Solución

Una portada con un botón por marca y la fecha y hora de la última actualización a la vista.

Resultado

Cada equipo llega en un clic a su vista y sabe si los datos están al día.

### Varias fuentes, un solo modelo

Problema

La información venía de varias fuentes desconectadas, así que no había una visión única del negocio.

Solución

Conecté las bases de cada fuente y las unifiqué en un solo modelo de Power BI, del que se alimenta cada vista por marca.

Resultado

\[Por completar: qué pueden ver ahora que antes no podían.\]

1 de 2

Imágenes ilustrativas: los nombres, logos y cifras reales del cliente fueron ocultados.

### Puntos destacados

- **Reporte construido desde cero,** a partir de la necesidad del cliente.
- **Integración de varias fuentes** en una sola tabla o vista de Power BI.
- **Una vista por marca,** para que cada equipo lea solo lo que le corresponde.
- **Portada de navegación** con un botón por marca.
- **Fecha y hora de actualización** visible para confiar en los datos.

### Herramientas

- Power BI
- Modelado de datos
- Integración de fuentes
- DAX

[Volver a los casos](#casos)

# Caso 3: Abastecimiento de punta a punta en varios retailers

Una marca de consumo masivo vende en varios retailers y necesitaba seguir toda su cadena en un solo lugar, desde la catalogación hasta la venta. Construí un reporte de 7 páginas que une fuentes distintas en un solo modelo. Con marcadores, el cliente cambia cómo ve los gráficos, y con botones dinámicos elige qué tablas mirar y exportar.

**7**páginas con navegación común

**4**retailers en un solo reporte

**\[N\]**fuentes de datos unificadas

**\[X\] h a \[X\] min**preparación del seguimiento

## Pantallas del reporte

GeneralHoldingFormatoCategoríaMarcaLínea

### Cambiar la vista sin salir de la página

Problema

El cliente quería mirar los mismos datos por holding, formato, categoría, marca o línea, y eso habría significado una página por cada vista.

Solución

Marcadores que cambian qué gráfico se muestra según el filtro elegido, más selectores de año, semana o trimestre.

Resultado

Un reporte más compacto, donde el cliente explora a su ritmo.

ResumenDetalle por SKUSKU-tiendaExportar

Retailer A · Producto 198 %

Retailer A · Producto 291 %

Retailer B · Producto 184 %

Retailer C · Producto 399 %

### El cliente elige qué ver y qué exportar

Problema

Cada usuario necesitaba un nivel de detalle distinto y llevarse la información a Excel.

Solución

Botones dinámicos que conectan las tablas: resumen, detalle por producto y detalle por producto y tienda, listas para exportar.

Resultado

Cada persona obtiene la tabla que necesita sin pedirla al equipo de reportes.

Forecast altoForecast 00.000Venta 00.000+000 %

Forecast bajoForecast 00.000Venta 00.000−000 %

Forecast correctoForecast 00.000Venta 00.000+00 %

### Desviación del forecast frente a la venta

Problema

Se comparaba forecast y venta, pero no se sabía en qué productos y tiendas el pronóstico fallaba más.

Solución

Clasificación de cada caso como forecast alto, bajo o correcto, con la desviación por semana, retailer, producto y tienda.

Resultado

El equipo ve dónde ajustar el pronóstico primero.

### Toda la cadena en un solo reporte

Problema

La información de cada etapa vivía en fuentes separadas, sin conexión entre sí.

Solución

Un modelo que une las fuentes y alimenta una página por etapa, con los mismos filtros en todas: período, retailer, categoría, marca, región, local y producto.

Resultado

\[Por completar: decisiones que ahora toma el cliente y tiempo ahorrado.\]

1 de 4

Imágenes ilustrativas: los nombres de retailers, marcas, productos y las cifras reales del cliente fueron ocultados.

### Puntos destacados

- **Visión completa de la cadena:** catalogación, forecast, inventario, fill rate y venta.
- **Varias fuentes en un solo modelo,** con cuatro retailers consolidados.
- **Marcadores** para cambiar la vista de los gráficos según el filtro elegido.
- **Botones dinámicos** que conectan las tablas para elegir qué ver y exportar.
- **Análisis de desviación del forecast** (alto, bajo o correcto) frente a la venta real.
- **Indicadores completos** de disponibilidad, días de inventario, quiebres y fill rate, con semáforos.
- **Filtros consistentes** en todas las páginas, con botón para borrarlos.

### Herramientas

- Power BI
- Marcadores y botones
- DAX
- Modelado de datos
- Integración de fuentes

## Contacto

\[correo\] · \[LinkedIn\] · \[teléfono\]

Página privada, compartida solo por invitación. Los datos reales de los proyectos fueron ocultados o reemplazados.