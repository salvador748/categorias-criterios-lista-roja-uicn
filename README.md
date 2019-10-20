# Categorías y criterios de la Lista Roja de la UICN
Este repositorio contiene un [Jupyter Notebook](https://jupyter.org/), desarrollado en el lenguaje de programación [Python](https://www.python.org/), para la aplicación de las [categorías y criterios](https://www.iucn.org/es/content/categor%C3%ADas-y-criterios-de-la-lista-roja-de-la-uicn-versi%C3%B3n-31-segunda-edici%C3%B3n) de la [Lista Roja de la Unión Internacional para la Conservación de la Naturaleza (UICN)](https://www.iucnredlist.org/es/).

El _notebook_ recibe como entrada una lista de nombres científicos de especies y genera para cada una:
* Un mapa de distribución basado en registros de presencia de especies.
* Un mapa de registros de presencia agrupados (_clustered_).
* Un archivo CSV con:
  * El área de extensión de la especie.
  * El área de ocupación de la especie.
  * La altitud mínima y la altitud máxima en las que la especie ha sido reportada.
  * La lista de países en los que está presente la especie.
  * La lista de áreas protegidas en las que está presente la especie.


Para ejecutar el _notebook_, se recomienda utilizar versión de Jupyter incluida en la plataforma [Anaconda](https://www.anaconda.com/) para ciencia de datos.

Primero, debe clonarse el repositorio:
```
git clone https://github.com/mfvargas/categorias-criterios-lista-roja-uicn.git
```

Luego, debe abrirse y ejecutarse, con la interfaz de Jupyter, el _notebook_ llamado **categorias-criterios-lista-roja-uicn.ipynb**. Lea las instrucciones contenidas en el _notebook_.

## Referencias
UICN. (2012). _Categorías y Criterios de la Lista Roja de la UICN: Versión 3.1_. Segunda edición. Gland, Suiza y Cambridge, Reino Unido: UICN. vi + 34pp. Originalmente publicado como _IUCN Red List Categories and Criteria: Version 3.1_. Second edition. (Gland, Switzerland and Cambridge, UK: IUCN, 2012).
