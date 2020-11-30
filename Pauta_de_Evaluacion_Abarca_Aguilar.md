# Pauta de Evaluación

| Item | Puntaje Ideal | Puntaje Real| Observaciones generales |
|------|---------------|-------------|-------------------------|
| README | 0.5 | 0.4 | Faltan especificaciones tecnicas del repositorio. |
| Commits | 0.5 | 0.4 | Muchos commits por defecto, señalen las diferencias entre ellos. |
| Ejercicio 1 - Teoría | 0.5 | 0.5 | Impecable. |
| Ejercicio 1 - Practico | 1 | 1 | Buena proteccion a la resta, excelente observación |
| Ejercicio 2 - Teoria | 1 | 1 | Bien, cuidado con la redacción |
| Ejercicio 2 - Practico | 1.5 | 1.3 | Error en los ejes, eje Y mal señalado y eje X sin unidad de medida |
| Ejercicio 3 - Teorico | 0.75 | 0.75 | Impecable |
| Ejercicio 3 - Practico | 1.25 | 1.05 | Nuevamente error con los ejes |
| **Total** | 7 | 6.4 | ||

+ El README debe contener las especificaciones tecnicas del repositorio, de manera que cualquier usuario pueda replicarlo, sucedio error con modulo extra de pandas ```xlrd```.
+ Muchos commits por defecto, si estan realizando el mismo proceso de mejorar un documento, señalen cuales fueron las mejoras en cada proceso.
+ Buen uso de DataFrame de Pandas, como estaban trabajando con columnas se sugiere usar el objeto asociado a las columnas:

```python
columna_n = df.['nombre de columna n'].values #asi obtienen el array con los datos presentes en esta columna del DataFrame
```

+ Buena observación con los `if` de la resta, excelente trabajo.
+ Cuidado al trabajar con decibeles, a lo más una cifra significativa.
+ Excelente declaración de variables, nombres acordes a lo que contienen excepto `sum` y `H`, la primera es una palabra reservada para la función nativa de python, mientras que la otra no hace referencia a lo que contiene.
+ Cuidado con la redacción, en el ejercicio 2 se les cuela un "que no si no fueron medidos...".
+ Al momento de trabajar con la ponderación A, no era necesario el uso del `for`, ya sea si fueran listas o arreglos, se podian trabajar como una resta de macro-objetos.
+ Cuando se trabaja en tercios de octava o en octava, es recomendable representar los niveles con graficos de barra ya que de por sí ya son promedios que abarcan toda una banda de frecuencia.
+ Tuvieron el error en ambos graficos de señalar mal el eje Y, ya que se trataban de niveles de presión sonora en dB, no de amplitud. Tambien el eje X no contemplaba su unidad de medida correspondiente (Hz).
+ Trabajo muy bien elaborado, con notoria dedicación y profesionalismo.
  