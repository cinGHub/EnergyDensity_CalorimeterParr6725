**Description/ Descripción**



**---English**



The Parr 6725 Calorimeter generates one output file per determination, with the .det.finl.csv extension and without column names.



This workflow is designed to operate in a universal and reproducible manner. Using the RunDataTemplate.csv file as a reference, the script assigns the appropriate column names and compiles all calorimetric determinations into a single dataset.



The code subsequently removes non-essential variables and converts binary and numeric codes from the calorimeter output into descriptive categorical values.



Finally, two energy density variables are calculate from the measured heat of combustion, HOC: DE\_kJ\_g\_DM and DE\_kJ\_g\_AFDM, which represent energy density (in kJ·g⁻¹) on a dry matter basis, without and with ash correction, respectively.





**---Español**



El Calorímetro Parr 6725 genera un archivo de salida por cada determinación, con la extensión .det.finl.csv y sin nombres en las columnas.



Este código está diseñado para funcionar de manera universal: a partir del archivo "RunDataTemplate", asigna los nombres correspondientes a las columnas y luego compila un listado de todas las determinaciones realizadas.



Además, el código elimina las columnas que no son necesarias y reasigna los valores binarios a su definición correspondiente.



Por último, genera dos columnas denominadas DE\_kJ\_g\_AFDM y DE\_kJ\_g\_DM, que contienen los valores finales (calculados a partir del calor de combustión medido, HOC) de la densidad energética expresada en kilojoules por gramo de muestra seca, con y sin corrección por cenizas, respectivamente.

