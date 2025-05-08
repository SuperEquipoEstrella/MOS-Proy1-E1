# Proyecto A - Entrega 2
Maria Alejandra Londoño <br> 
Angélica Ortiz<br>
María José Amorocho

# Descripción
Este repositorio forma parte de la segunda entrega del Proyecto A del curso Modelado, Simulación y Optimización. Contiene la implementación y soluciones de tres casos de estudio basados en problemas de ruteo vehicular y asignación de recursos, desarrollados en notebooks de Jupyter.

# Estructura del repositorio
El repositorio se organiza de la siguiente manera:

- content/: Datos de entrada para cada caso (clientes, depósitos, vehículos, distancias).

- solutions/: Resultados exportados en formato CSV para cada caso después de ejecutar los modelos.

- `problema_A_caso_1.ipynb`: Notebook con desarrollo y solución del caso 1.

- `problema_A_caso_2.ipynb`: Notebook con desarrollo y solución del caso 2.

- `problema_A_caso_3.ipynb`: Notebook con desarrollo y solución del caso 3.

- `distances_all.csv`: Matriz de distancias usada en el caso 3.

- `Proyecto-Entrega2.pdf`: Informe técnico completo del proyecto.


En cada notebook se muestra el desarrollo de cada problema, implementando el modelo correspondiente. Estos notebooks ya están ejecutados, por lo que puede verse la solución sin necesidad de correrlos. Si quisieran probarse, basta con ejecutar lo que hay en ellos (y descargar las dependencias necesarias). 

# Requisitos
Para ejecutar los notebooks es necesario contar con:

- Python 3.7 o superior.

- Jupyter Notebook o JupyterLab.

- Librerías de Python (instalables vía pip):

```bash
pip install pandas pyomo jupyter openrouteservice folium requests
```
