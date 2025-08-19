
# Challenge TelecomX: parte 1

## **Propósito del análisis realizado.**
Analizar los datos de la base de datos para así comprender el perfil de los clientes que cancelan sus servicios (churn o fuga de clientes) e identificar los factores más relevantes detrás de ello.

## **Estructura del proyecto y organización de los archivos**

1. **Extracción de Datos (E)**
2. **Transformación (T)**
   - Exploración de columnas y verificación de tipos de datos
   - Transformación de los datos
   - Creación de la columna cuentas_diarias
   - Análisis de correlación y selección de variables relevantes
3. **Carga y análisis (L)**
   - Análisis descriptivo con Describe
   - Análisis general del Churn
   - Evasión por variables categóricas
   - Evasión por variables numéricas
   - Impacto de las variables en Churn
   - Exportación de dataset limpio
4. **Informe final**
   - Introducción
   - Limpieza y tratamiento de datos
   - Análisis Exploratorio de Datos (EDA)
   - Conclusiones e Insights
   - Recomendaciones

## **Ejemplos de gráficos e insights obtenidos**
![Distribución de churn](http://github.com/remBits/Challenge-Telecom-X-parte-1/blob/main/reportes_graficos/distribucion_y_countplot_churn.png)
![Variables categóricas multiclase](https://github.com/remBits/Challenge-Telecom-X-parte-1/blob/main/reportes_graficos/ev_por_var_cat_mul.png)
![Boxplot de costos mensual y total](https://github.com/remBits/Challenge-Telecom-X-parte-1/blob/main/reportes_graficos/boxplot_cargos_mensual_total_vs_churn.png)

- Los clientes más nuevos cancelan más.
- Los clientes con contratos mes a mes, que es el contrato más corto y que se renueva un mayor número de veces, cancelan más.
- Los clientes que contratan el servicio de internet por fibra óptica cancelan más.
- Los clientes sin servicios adicionales cancelan más.
## **Instrucciones para ejecutar el notebook**

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/remBits/Challenge-Telecom-X-parte-1.git
```
2. Acceder a la carpeta del proyecto:
   ```bash
   cd Challenge-Telecom-X-parte-1
```
3. Instalar librerías:
```bash
pip install pandas numpy matplotlib seaborn
```
4. Ejecutar Notebook: 
```bash
jupyter notebook
```
5. Abrir el archivo Challenge-Telecom-X-parte-1.ipynb y ejecutar las celdas.



