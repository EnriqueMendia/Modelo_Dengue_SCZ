
🌍 Modelo Matemático del Dengue en Santa Cruz, Bolivia
Este proyecto utiliza ecuaciones diferenciales para modelar la propagación del dengue en Santa Cruz, Bolivia. Basado en datos reales del Ministerio de Salud, el modelo simula la dinámica de la enfermedad utilizando una función logística para estimar la cantidad de personas infectadas a lo largo del tiempo.

🔬 ¿Qué estamos haciendo?
Aplicamos un modelo logístico para simular el comportamiento de la propagación del dengue.
Usamos datos reales para validar el modelo y prever la expansión futura de la enfermedad.
Desarrollamos una solución matemática utilizando ecuaciones diferenciales para describir la dinámica de la población infectada.
💻 ¿Cómo lo implementamos?
El modelo está basado en una ecuación diferencial de variables separables, resuelta con métodos matemáticos como fracciones parciales. Aquí un ejemplo simplificado de la ecuación que usamos:

𝑑
𝑁
/
𝑑
𝑡
=
𝑘
∗
(
𝑀
−
𝑁
)
∗
𝑁
/
𝑀
dN/dt=k∗(M−N)∗N/M
Donde:

N es la población infectada,
M es la población total,
k es una constante de tasa de infección.
Luego, resolvimos esta ecuación utilizando integración numérica y aplicamos un algoritmo de simulación para estimar cómo se propagará el dengue en el futuro.

📊 Resultados
Los resultados muestran cómo la población infectada crece rápidamente en las primeras semanas, lo que refleja la naturaleza explosiva de las epidemias. Por ejemplo, si tenemos un punto de partida con 712 casos, después de una semana ya se estima que el número sube a 2012 infectados.

📄 Descargar el PDF
Si deseas más detalles sobre la formulación matemática, el código y el análisis de resultados, puedes descargar el PDF completo del proyecto:
Descargar Ecuaciones Diferenciales del Dengue

Este proyecto tiene un enfoque práctico que demuestra el poder de las ecuaciones diferenciales para abordar problemas reales como la propagación de enfermedades. ¡Contribuye o comenta si tienes sugerencias o mejoras para el modelo!
