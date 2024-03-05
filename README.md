# Resultados y Conclusiones

## Conclusiones de la Ejecución con Diferentes Niveles de Optimización

- **-o0 (sin optimización):**
- El tiempo de ejecución real fue de aproximadamente 0.019 segundos, con un tiempo de usuario de 0.000 segundos y un tiempo de sistema de 0.002 segundos.

  ![Ejecución con -o0](/img/jac3.png)

- **-o1 (optimización básica):**

  - El tiempo de ejecución real fue de aproximadamente 0.05 segundos, con un tiempo de usuario de 0.000 segundos y un tiempo de sistema de 0.002 segundos.

  ![Ejecución con -o1](/img/jac4.png)

- **-o2 (optimización estándar):**

  - El tiempo de ejecución real fue de aproximadamente 0.013 segundos, con un tiempo de usuario de 0.000 segundos y un tiempo de sistema de 0.002 segundos.

  ![Ejecución con -o2](/img/jac5.png)

- **-o3 (optimización agresiva):**
- El tiempo de ejecución real fue de aproximadamente 0.019 segundos, con un tiempo de usuario de 0.000 segundos y un tiempo de sistema de 0.002 segundos.
  ![Ejecución con -o3](/img/jac6.png)

- **-ofast:**
- Tiempo de ejecución real: 0m0.012s

  - Tiempo de usuario: 0m0.000s
  - Tiempo del sistema: 0m0.002s
  - El tiempo de ejecución es ligeramente más largo que las otras opciones de optimización, lo que sugiere que las optimizaciones agresivas pueden no ser siempre la mejor opción en términos de velocidad de ejecución en este caso específico.

  ![Ejecución con -ofast](/img/ofast.png)

- **-og:**
- Tiempo de ejecución real: 0m0.011s
- Tiempo de usuario: 0m0.001s
- Tiempo del sistema: 0m0.001s
- El tiempo de ejecución es similar al de -Ofast, pero ligeramente más rápido. Esto puede indicar que las optimizaciones específicas para la depuración pueden ser más eficientes en este caso.

![Ejecución con -og](/img/og.png)

- **-os:**
- Tiempo de ejecución real: 0m0.005s
  - Tiempo de usuario: 0m0.000s
  - Tiempo del sistema: 0m0.002s
  - El tiempo de ejecución es el más rápido de todas las opciones de optimización. Esto sugiere que optimizar para el tamaño del código puede resultar en una ejecución más eficiente en este caso.

![Ejecución con -os](/img/os.png)

# Conclusiones Generales de las Ejecuciones con Diferentes Niveles de Optimización

Después de analizar los resultados de todas las ejecuciones con diferentes niveles de optimización, podemos concluir lo siguiente:

- En general, se observa una mejora en el rendimiento del código al utilizar optimización en comparación con la compilación sin optimización (-O0).
- Los niveles de optimización -O1, -O2 y -O3 muestran una mejora progresiva en el tiempo de ejecución, siendo -O2 el nivel que proporciona el tiempo de ejecución más rápido en este caso específico.
- Aunque el nivel de optimización -O1 mostró un aumento en el tiempo de ejecución en comparación con -O0 en este caso particular, este resultado puede variar según el código y las características del sistema.
- La diferencia en el tiempo de ejecución entre los niveles de optimización puede ser pequeña en algunos casos, lo que sugiere que la optimización no siempre conduce a mejoras significativas en el rendimiento del código.
- Es importante tener en cuenta que los resultados pueden variar según el entorno de ejecución y las características específicas del código.
- Se debe considerar cuidadosamente el equilibrio entre el tiempo de compilación, el rendimiento del código y otros factores al elegir el nivel de optimización adecuado para un proyecto específico.
