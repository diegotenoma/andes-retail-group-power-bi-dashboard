📊 Andes Retail Group — Dashboard de Desempeño Comercial 2024-2025

Dashboard interactivo en Power BI que analiza el desempeño comercial de Andes Retail Group entre 2024 y 2025: ingresos, pedidos, ticket promedio, clientes activos y margen, con cortes por tiempo, país, región, categoría de producto y segmento de cliente.

Archivo: Proyecto9_Diego_Tenorio.pbix Autor: Diego Tenorio Martínez · LinkedIn · GitHub

<!-- Agrega aquí una captura de cada página, por ejemplo: ![Overview](img/overview.png) ![Detalle](img/detalle.png) -->
🎯 Objetivo

Dar a un equipo comercial una vista rápida del estado del negocio y una vista de detalle para investigar qué categorías, países y segmentos explican los cambios en ingresos y margen entre 2024 y 2025.

Preguntas que responde:

¿Cuánto vendimos y cómo cambió de 2024 a 2025?
¿Qué meses, categorías y países concentran los ingresos?
¿Qué segmentos de cliente generan más ingresos y con qué margen?
¿Dónde crecimos o caímos frente al año anterior?
🗂️ Estructura del reporte
Página 1 — OVERVIEW

Vista ejecutiva del desempeño general.

Elemento	Detalle
KPIs (tarjetas)	Ingresos Totales · Pedidos · Ticket Promedio · Clientes Activos · Margen %
Variación interanual	Tarjeta con texto dinámico de la variación 2024 vs 2025
Gráfico de líneas	Ingresos Totales por mes, con una serie por año; el tooltip muestra ingresos 2024, ingresos 2025 y variación %
Barras por categoría	Ingresos Totales por categoría de producto
Barras por país	Ingresos Totales por país
Filtros (slicers)	Año · Trimestre · País · Región · Categoría de producto · Segmento de cliente
Navegación	Botones para moverse entre páginas
Página 2 — DETALLE

Vista analítica para profundizar.

Elemento	Detalle
KPIs comparativos	Ingresos 2024 · Ingresos 2025 · Variación 24-25 % · Cambio 2024-2025
Dispersión de segmentos	Ingresos (eje X) vs. Margen % (eje Y), con el tamaño de burbuja según Clientes Activos
Matriz país × categoría	Ingreso total por país (filas) y categoría de producto (columnas)
Matriz categoría × mes	Ingreso total por categoría (filas) y mes (columnas)
Barras 2024 vs 2025	Ingresos por categoría, comparando ambos años
Filtros (slicers)	Los mismos seis filtros de la página Overview

Marcador incluido: Restablecer filtros, para volver al estado inicial con un clic.

🧮 Modelo de datos

Modelo simple con dos tablas:

Tabla	Rol	Campos principales
Andes_Retail_Group_2024_2025	Tabla de hechos (ventas)	País, Región, Categoría_Producto, Segmento_Cliente y las métricas del negocio
Calendario	Tabla de fechas	Año, Trimestre, Mes
Medidas DAX
Medida	Uso
Ingresos Totales	Ventas totales del periodo filtrado
Pedidos	Número de pedidos
Ticket Promedio	Valor promedio por pedido
Clientes Activos	Clientes con actividad en el periodo
Margen %	Margen sobre ingresos
Ingresos 2024 / Ingresos 2025	Ingresos de cada año, para comparar
Var 24-25 %	Variación porcentual interanual
Cambio 2024-2025	Diferencia absoluta entre años
Var Texto	Texto dinámico con la variación, para la tarjeta de resumen
<!-- Ajusta estas descripciones a la lógica exacta de tus medidas y agrega la fórmula DAX de las más importantes. -->
🔍 Hallazgos clave
<!-- Completa con 3 a 5 conclusiones con cifras reales de tu dashboard. Ejemplos de formato: - Los ingresos crecieron X % de 2024 a 2025, impulsados por la categoría Y. - El país Z concentra el N % de los ingresos, pero tiene el margen más bajo. - El segmento W tiene el mayor margen con pocos clientes activos. -->
🛠️ Herramientas
Power BI Desktop (modelo de datos, medidas DAX, visualizaciones)
Tema personalizado: Innovate
▶️ Cómo usarlo
Descarga Proyecto9_Diego_Tenorio.pbix.
Ábrelo con Power BI Desktop (Windows).
Usa los filtros de la izquierda o superior para segmentar por año, trimestre, país, región, categoría y segmento.
Pasa el cursor sobre las gráficas para ver los tooltips.
Usa el botón Restablecer filtros para volver a la vista completa.
📬 Contacto

Diego Tenorio Martínez Data Analyst | Operaciones & Supply Chain 📍 Morelia, Michoacán 🔗 linkedin.com/in/tenoriodiego · 💻 github.com/diegotenoma
