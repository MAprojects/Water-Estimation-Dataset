# Water-Estimation-Dataset

Nombre del Autor : Mohamed Azar

El DOI de Zenodo del dataset generado : https://zenodo.org/badge/DOI/10.5281/zenodo.5652032.svg


Extrae el nivel de agua de los principales embalses de España y datos meteorológicos de la AEMET junto con las coordenadas de Wikipedia.

Para ejecutar se requieren las siguienes dependencias :

pip install pandas
pip install requests
pip install beautifulsoup4


El notebook Web_Scrapping_Dataset_AGUA.ipynb se abre y se ejecutan todas las celdas de forma secuencial para obtener los resultados. 

El notebook hay que ejecutarlo diaraiamente porque los datos se van actualizando en la web de esta forma. Los registros se almacenan en un archivo de tipo CSV diferente para cada dia .Para poder añadirlo de forma incremental y obtener así un histórico de datos.
