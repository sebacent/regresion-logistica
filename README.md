# Proyecto de Regresión Logística 4Geeks

## 📝 Instrucciones

### Campaña de Marketing Bancario

**Comprensión empresarial**

Los depósitos a largo plazo permiten a los bancos retener dinero durante un período de tiempo específico, lo que permite al banco utilizar ese dinero para mejorar sus inversiones. Las campañas de marketing de este producto se basan en llamadas telefónicas. Si un usuario no se encuentra disponible en un momento dado, entonces se le volverá a llamar de nuevo en otro momento.

**Descripción del problema**

El banco portugués está teniendo una disminución en sus ingresos, por lo que quieren poder identificar a los clientes existentes que tienen una mayor probabilidad de contratar un depósito a largo plazo. Esto permitirá que el banco centre sus esfuerzos de marketing en esos clientes y evitará perder dinero y tiempo en clientes que probablemente no se suscribirán.

Para abordar este problema crearemos un algoritmo de clasificación que ayude a predecir si un cliente contrará o no un depósito a largo plazo.

#### Paso 1: Carga del conjunto de datos

El conjunto de datos se puede encontrar en esta carpeta de proyecto bajo el nombre `bank-marketing-campaign-data.csv`. Puedes cargarlo en el código directamente desde el enlace (`https://raw.githubusercontent.com/4GeeksAcademy/logistic-regression-project-tutorial/main/bank-marketing-campaign-data.csv`) o descargarlo y añadirlo a mano en tu repositorio. En este conjunto de datos encontrarás las siguientes variables:

1. `age`. Edad del cliente (numérico)
2. `job`. Tipo de trabajo (categórico)
3. `marital`. Estado civil (categórico)
4. `education`. Nivel de educación (categórico)
5. `default`. ¿Tiene crédito actualmente? (categórico)
6. `housing`. ¿Tiene un préstamo de vivienda? (categórico)
7. `loan`. ¿Tiene un préstamo personal? (categórico)
8. `contact`. Tipo de comunicación de contacto (categórico)
9. `month`. Último mes en el que se le ha contactado (categórico)
10. `day_of_week`. Último día en el que se le ha contactado (categórico)
11. `duration`. Duración del contacto previo en segundos (numérico)
12. `campaign`. Número de contactos realizados durante esta campaña al cliente (numérico)
13. `pdays`. Número de días que transcurrieron desde la última campaña hasta que fue contactado (numérico)
14. `previous`. Número de contactos realizados durante la campaña anterior al cliente (numérico)
15. `poutcome`. Resultado de la campaña de marketing anterior (categórico)
16. `emp.var.rate`. Tasa de variación del empleo. Indicador trimestral (numérico)
17. `cons.price.idx`. Índice de precios al consumidor. Indicador mensual (numérico)
18. `cons.conf.idx`. Índice de confianza del consumidor. Indicador mensual (numérico)
19. `euribor3m`. Tasa EURIBOR 3 meses. Indicador diario (numérico)
20. `nr.employed`. Número de empleados. Indicador trimestral (numérico)
21. `y`. TARGET. El cliente contrata un depósito a largo plazo o no.

#### Paso 2: Realiza un EDA completo

Este segundo paso es vital para asegurar que nos quedamos con las variables estrictamente necesarias y eliminamos las que no son relevantes o no aportan información. Utiliza el Notebook de ejemplo que trabajamos y adáptalo a este caso de uso.

Asegúrate de dividir convenientemente el conjunto de datos en `train` y `test` como hemos visto en lecciones anteriores.

#### Paso 3: Construye un modelo de regresión logística

No es necesario que optimices los hiperparámetros. Comienza utilizando una definición por defecto y mejórala en el paso siguiente.

#### Paso 4: Optimiza el modelo anterior

Después de entrenar el modelo, si los resultados no son satisfactorios, optimízalo empleando alguna de las técnicas vistas anteriormente.

> NOTA: Solución: https://github.com/4GeeksAcademy/logistic-regression-project-tutorial/blob/main/solution.ipynb
