# VAE_UPM

En este repositorio guardo los cuadernos Jupypter para el problema siguiente:


# DESCRIPCIÓN

Se propone emplear el conocido dataset “Breast cancer”, formado por 286 pacientes con 9 features en formato tabular. El dataset es de acceso público .
Los pasos a implementar son los siguientes:
(1)	Preprocesamiento: 
a.	Aplicar el preprocesamiento necesario a los datos para que puedan ser empleados en los demás pasos. Incluye conversión de variables de texto a categóricas, normalizaciones, etc., que se estimen necesarias y/o convenientes. 
b.	Dividir el dataset en datos de entrenamiento y validación. Los de validación sólo se emplearán en el paso de validación, siendo muy importante que, bajo ningún concepto, se empleen para entrenar ningún método de generación. 


(2)	Generador de datos:
a.	Emplear un VAE para generar pacientes virtuales. El output de este paso debe ser una tabla de pacientes virtuales. 


(3)	Validación de pacientes virtuales:
a.	Validar los pacientes virtuales usando distribuciones marginales. Comparar las distribuciones de los pacientes reales y virtuales por cada covariable, analizando los resultados obtenidos. 
b.	Validar los pacientes virtuales usando la distribución conjunta. Entrenar un clasificador y ver si es capaz de distinguir entre pacientes reales y virtuales, analizando los resultados obtenidos. 
c.	Validar los pacientes virtuales usando otros métodos que al candidato se le ocurran, analizando los resultados obtenidos. 


(4)	Generación y validación de pacientes estratificados. 
a.	Implementar un VAE condicional (CVAE) que genere pacientes estratificados. La estratificación de pacientes puede hacerse empleando un método de clusterización que permita dividir a los pacientes en subpoblaciones. 
b.	Validar los pacientes virtuales estratificados empleando los métodos del paso 3, y analizando los resultados por estratos. 
