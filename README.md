# Module 5: Developing Views

## Lab: Developing Views

1. **Nombres y apellidos:** Francisco Javier Moreno Quevedo
2. **Fecha:** 28/11/2020
3. **Resumen del Ejercicio:** Añadir los componentes necesarios para hacer funcional la aplicacion de ciudades1/3 
4. **Dificultad o problemas presentados y como se resolvieron:** Ninguna



- Ejercicio 1: Adding Views to an MVC Application

  - En la clase **CityProvider** completamos el constructor para que cargue las ciudades
  - Completamos la propiedades de la clase **CIty** y CityPopulastion
  - En el **CityController** completamos el constructor para que cargue las ciudades del provider
  - En la accion **showcities** añadimos un viewBag
  - Añadimos de esta accion una vista **ShowCities**
  - En la vista añadimos el codigo para que muestre una lista de ciudades
  - EN **CityController** añadimos el parametro "**string** **cityName**" en la accion  **ShowDataForCity**, 
  - en esta acción añadimos un **ViewBag** y creamos una vista parcial **ShowDataForCity** 
  - En esta vista parcial añadimos codigo para mostrar el detalle de la ciudad seleccionada
  - Añadimos un **Razor View Imports** que le llamaremos **_ViewImport**  y añadiremos un **tag helper**
  - EN la vista  **ShowDataForCity** añadimos un asp-action y 

