# Proyecto final Modelos de sistemas 2 

Integrantes:
  
    Wildey Alejandro Gallego Durango CC: 1035233399
    Juan Felipe Gallo Rendón CC: 1214724863

## Installation

Proyecto hecho en Jupyter Python 3.

```bash
Dependencias:
- pandas: pip install pandas
- numpy: pip install numpy
- seaborn: pip install seaborn
- sklearn: pip install sklearn
- imblearn: pip install imblearn
- plotly: pip install plotly
- matplotlib: pip install matplotlib
- __future__: pip install __future__
- scipy: pip install scipy
- qgrid: pip install qgrid
- IPython: pip install IPython
- mlxtend: pip install mlxtend
- time: pip install time
```

## Usage

```python
Ejecutar los algoritmos en el órden pedido por la guía de trabajo que se encuentra dentro del proyecto
```

## Arquitectura
```
ml_CTG: 
        Entrega Final Proyecto -2020-I .pdf
        data:
            -- bases de datos y archivos guardados para procesamiento --
            CTG.ods
            CTG.xls
            CTGsmt with titles.csv
            CTGsmt.csv
            CTGsmtMLP.csv
            CTGsmtRFE.csv
            CTGsmtSVM.csv
        Experiments:
            -- Punto 5 del trabajo, aquí se implementan los experimentos básicos --
            1. QDA.ipynb
            2. Parzen Window.ipynb
            3. Gradient Boosting Tree.ipynb
            4. ANN.ipynb
            5. SVM.ipynb
            utils.py
        Seleccion-Extraccion:
            -- Punto 7 y 8 del trabajo, aquí se vealúan los modelos aplicando selección de características -- 
            1. Fisher Analysis.ipynb -- Todo lo relacionado con análisis de fisher--
            Feature Selection:
                    Experiments Feature Selection:
                        -- Experimentos con los modelos usando dataset generados a partir de análisis y extracción de características --
                        1. GBT - selection.ipynb    
                        3. SVC - Seleccion.ipynb
                -- Todo relacionado con selección de características --
                1. GBT RFESln.ipynb
                2. ANN FwrdSln.ipynb
                3. SVM FwrdSln.ipynb
            3. PCA.ipynb
## License
[MIT](https://choosealicense.com/licenses/mit/)
