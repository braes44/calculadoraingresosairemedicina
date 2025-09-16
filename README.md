Manual de Uso — Calculadora de Oxígeno Hospitalario
Este manual explica cómo utilizar la plantilla calculadora_oxigeno_hospital.html para estimar el consumo hospitalario de oxígeno, calcular equivalentes en cilindros, evaluar plantas PSA y LOX, y analizar riesgos. El documento está diseñado con base en las recomendaciones de la OPS/OMS para garantizar un uso racional, seguro y sostenible del oxígeno medicinal.
1) Cálculo del Consumo de Oxígeno
En esta sección se definen los parámetros principales para estimar el consumo de oxígeno en un hospital:
- Nº de camas: Total de camas instaladas en el hospital.
- % Ocupación: Porcentaje de camas que se espera estén en uso.
- % Pacientes graves: Proporción de pacientes que requieren oxígeno a flujo medio (10 L/min).
- % Pacientes críticos: Proporción de pacientes que requieren oxígeno a flujo alto (30 L/min).
- Horas de operación diarias: Usualmente 24 h/día.
- Días por mes: Se recomienda usar 30 días para cálculos mensuales.

La calculadora estima automáticamente el consumo en L/min, m³/h, m³/día y m³/mes.
2) Puntos Adicionales de Consumo
Además de los pacientes hospitalizados, existen consumos adicionales en quirófanos, urgencias o recuperación. La calculadora permite añadir manualmente estos puntos de consumo para un cálculo más realista.
3) Cálculo de Equivalentes en Cilindros
- Volumen interno (L): Capacidad física del cilindro.
- Presión de llenado: Se ingresa en bar o psi.
- Precio por llenado: Costo de recarga de un cilindro.

La fórmula aplicada es la Ley de Boyle: Volumen utilizable = V_cil × (P_abs / P_atm).
La calculadora muestra el contenido en m³ por cilindro y el costo unitario por m³.
4) Plantas PSA (Adsorción por Cambio de Presión)
- Capacidad (m³/h): Producción de oxígeno por hora.
- Potencia (kW): Consumo energético promedio.
- Disponibilidad (%): Tiempo de operación real esperado (ej. 95%).
- Tarifa eléctrica: Costo de la energía en USD/kWh.
- Mantenimiento anual: Costos preventivos.
- CAPEX: Inversión de capital.
- Vida útil: Años de funcionamiento estimado.

El resultado entrega la producción anual de oxígeno y el costo por m³.
5) Comparación de LOX y Cilindros
- Precio LOX por m³: Costo en USD/m³.
- Pérdida por evaporación: % de pérdidas.
- Precio por cilindro: Costo de mercado.

La calculadora compara los costos unitarios por m³ de cada fuente de oxígeno.
6) Análisis de Escenarios y Matriz de Riesgos
La matriz de riesgos permite evaluar vulnerabilidades del suministro de oxígeno:
- Fiabilidad eléctrica (0-100): Probabilidad de contar con suministro eléctrico estable.
- Disponibilidad de repuestos (0-100): Facilidad de acceso a repuestos y servicio técnico.
- Proximidad del proveedor (0-100): Distancia o tiempo de respuesta del proveedor.
- Respaldo disponible: Indicar si existe suministro secundario o de emergencia (0 = no, 1 = sí).

La herramienta genera un puntaje de riesgo y recomendaciones.

Según la OPS, siempre debe existir:
1. Suministro primario (principal).
2. Suministro secundario (igual capacidad que el primario).
3. Suministro de emergencia (mínimo necesario para continuidad).
7) Ejemplo Ilustrado
Supongamos un hospital con 100 camas, 80% de ocupación, 75% pacientes graves y 25% críticos.

Consumo proyectado:
- Graves: 75% de 80 camas = 60 pacientes × 10 L/min = 600 L/min.
- Críticos: 25% de 80 camas = 20 pacientes × 30 L/min = 600 L/min.
Total: 1.200 L/min = 72 m³/h ≈ 2.160 m³/día ≈ 64.800 m³/mes.

Si un cilindro de 50 L a 150 bar contiene ~7,500 L (~7.5 m³), se necesitarían:
64.800 ÷ 7.5 = 8,640 cilindros al mes.

La matriz de riesgos, con fiabilidad eléctrica 80, repuestos 60, proveedor 50 y respaldo = 1, daría un riesgo medio y la recomendación de reforzar servicio técnico.
Conclusión
La calculadora permite dimensionar el consumo hospitalario de oxígeno, comparar diferentes tecnologías de suministro (cilindros, LOX, PSA) y analizar riesgos. Su uso siguiendo este manual asegura alineación con las guías OPS/OMS y facilita la toma de decisiones técnicas y financieras.
