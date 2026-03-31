# ConnectaTel_Analysis
📊 Análisis de Comportamiento y Segmentación: ConnectaTel 📡
Este proyecto realiza un análisis exploratorio de datos (EDA) y una segmentación de clientes para ConnectaTel, una empresa de telecomunicaciones. El objetivo es identificar patrones de consumo, limpiar inconsistencias y proponer estrategias comerciales basadas en datos reales de uso.

🎯 Objetivos del Proyecto
Limpieza de Datos: Identificar y tratar valores nulos y duplicados.

Análisis Exploratorio (EDA): Visualizar distribuciones de edad, mensajes, llamadas y minutos.

Detección de Outliers: Aplicar el método de Rango Intercuartílico (IQR) para identificar usuarios de consumo extremo.

Segmentación de Clientes: Clasificar a los usuarios por niveles de uso y rangos de edad para mejorar la toma de decisiones.

🛠️ Tecnologías Utilizadas
Python 3.x

Pandas: Manipulación y limpieza de datos.

NumPy: Operaciones lógicas y matemáticas.

Matplotlib & Seaborn: Visualización de datos avanzada.

📈 Hallazgos Clave (Insights)
1. Calidad de los Datos
Se detectó un 1% de valores nulos en la edad de los usuarios, los cuales fueron imputados mediante la mediana para mantener la integridad de la muestra (4,000 registros).

2. Comportamiento del Consumidor
Distribución Homogénea: No se encontró una diferencia significativa en los hábitos de consumo entre los planes Básico y Premium, lo que sugiere una oportunidad para reestructurar la propuesta de valor.

Dominio de Adultos: El 50% de la base de clientes tiene entre 30 y 60 años, siendo el segmento más estable financieramente para la empresa.

3. Segmentación Estratégica
Grupo de Uso Medio: Representa la mayoría de la base, operando con una eficiencia de red óptima.

Power Users (Outliers): Se identificaron usuarios con hasta 156 minutos de llamada, quienes son los principales generadores de ingresos por excedentes pero tienen mayor riesgo de fuga.

💡 Recomendaciones de Negocio
Upselling Directo: Migrar a los usuarios de "Alto Uso" del plan Básico al Premium mediante promociones dirigidas.

Plan Senior: Crear una oferta simplificada para el segmento de Adultos Mayores enfocado en voz.

Captación Juvenil: Lanzar paquetes de datos optimizados para redes sociales para atraer al segmento menor de 30 años (actualmente el más pequeño).
