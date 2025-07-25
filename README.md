# Caso Practico SQL Restaurantes del Mundo
El restaurante "Sabores del Mundo", es conocido por su auténtica cocina y su ambiente acogedor.

Este restaurante lanzó un nuevo menú a principios de año y ha estado recopilando información detallada sobre las transacciones de los clientes para identificar áreas de oportunidad y aprovechar al máximo sus datos para optimizar las ventas.

# Contexto
El restaurante "Sabores del Mundo", es conocido por su auténtica cocina y su ambiente acogedor.

Este restaurante lanzó un nuevo menú a principios de año y ha estado recopilando información detallada sobre las transacciones de los clientes para identificar áreas de oportunidad y aprovechar al máximo sus datos para optimizar las ventas.
# Objetivo.
 Identificar cuáles son los productos del menú que han tenido más éxito y cuales son los que menos han gustado a los clientes.

# Programación y analsis de datos:
 Se adjunta archivo con codigo de SQL

# Conclusiónes Generales: 
## Volumen de Pedidos:
 Se registraron 787 pedidos en el período analizado (del 1 al 14 de enero de 2023), con un promedio de ~56 pedidos por día. Esto indica una actividad constante, pero es importante analizar picos horarios y días de mayor demanda.
## Productos Más Vendidos:
Los ítems con item_id más frecuentes en order_details son: Chicken burrito 117 (aparece en múltiples pedidos, posiblemente un producto estrella). 101, 108, 124, 129 (Hamburguer, Tofu Pad Thai, Spaghetti, Mushroom Ravioli. Son recurrentes), estos productos deberían ser priorizados en gestión de inventario y promociones.
## Horarios de Mayor Demanda: 
Los pedidos se concentran en horarios de comida: 12:00–14:00 (almuerzo) y 19:00–21:00 (cena), |Esto sugiere reforzar recursos (personal/cocina) en esas franjas.

# Recomendaciones Estratégicas:
## A) Optimización de Inventario y Menú; 
Enfoque en Productos Populares: Asegurar stock suficiente para los ítems más vendidos (ej. 117, 101, 108).

Analizar costos y márgenes de estos productos para maximizar rentabilidad.

Revisión de Productos Menos Vendidos: Identificar ítems con baja frecuencia (ej. item_id con pocas apariciones) y evaluar su eliminación o promoción.

Paquetes o Combos: Agrupar productos frecuentemente comprados juntos (ej. 108 y 124 aparecen en el mismo pedido varias veces) en combos para aumentar el ticket promedio.
## B. Mejora Operativa
Refuerzo de Personal en Horas Pico: Aumentar personal en cocina y servicio durante almuerzo y cena para reducir tiempos de espera.

Capacitación en Sistema de Pedidos: Corregir errores de registros nulos (item_id NULL) con capacitación en el sistema POS o validación automática.

Análisis de Tiempos de Preparación: Cruzar datos con tiempos de preparación para identificar cuellos de botella (si hay datos disponibles).
