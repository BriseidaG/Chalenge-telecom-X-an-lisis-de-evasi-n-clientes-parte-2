# Informe Final - Evasión de Clientes en Telecom X  

## Introducción  
Este análisis utiliza datos de **Telecom X**, empresa ficticia con alta tasa de *churn* (cancelación de clientes).  
El objetivo fue identificar factores que influyen en la baja de servicios para apoyar al equipo de Data Science en la creación de modelos predictivos y estrategias de retención.  

## Limpieza y Datos  
- Datos obtenidos en **JSON** y procesados con `requests` y `pandas`.  
- Normalización de la estructura.  
- Conversión de variables categóricas y numéricas.  
- Eliminación de registros incompletos (<5%).  
- Verificación de consistencia de tipos.  

## Análisis Exploratorio  
Se usaron `matplotlib` y `seaborn` para explorar las variables:  
- **Churn**: mayoría permaneció, aunque la cancelación es significativa.  
- **Cargos mensuales**: clientes que cancelaron pagaban en promedio **74.44** vs **61.30** de quienes permanecen.  
- **Cargos totales**: clientes leales acumulan mayor gasto.  
- **Antigüedad**: quienes se fueron tenían **17.9 meses**, los que permanecen **37.6**.  

## Hallazgos Clave  
- Altos cargos mensuales aumentan la probabilidad de churn.  
- Clientes nuevos son los más vulnerables.  
- La fidelización se fortalece con el tiempo y mayores gastos acumulados.  

## Conclusiones y Recomendaciones  
La evasión se relaciona con precios elevados y baja antigüedad. Se sugiere:  

1. Ofrecer **descuentos** a clientes nuevos con cargos altos.  
2. Implementar **programas de fidelización temprana**.  
3. Aplicar **encuestas** para conocer causas de cancelación.  
4. Revisar la **política de precios** para asegurar valor percibido.  
