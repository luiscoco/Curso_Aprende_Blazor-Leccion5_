# CURSO: APRENDE BLAZOR

# LECCIÓN 6: Cómo crear tu primer Componente (Visual Studio 2022)

1. Abrir la aplicación Blazor con Visual Studio 2022

2. Crear un nuevo Componente **Mensaje.razor** pulsando sobre el botón derecho del ratón en la carpeta **Pages** y seleccionando la opción **Agregar->Componente de Razor...**

![image](https://github.com/user-attachments/assets/71a3d640-1419-4c17-b165-3089e245b68b)

Vemos el nuevo Componente en el **Explorador de Soluciones**

![image](https://github.com/user-attachments/assets/981d0069-472d-4b6d-b348-22e0ba7d2e44)

Este es el **código del nuevo Componente**:

```razor
@page "/mensaje"

<PageTitle>Nuevo componente Mensaje</PageTitle>

<h3>Mensaje de Bienvenida</h3>

@code {

}
```

3. No olvidar incluir la ruta del nuevo componente: **@page "/mensaje"**

4. (Opcional) Incluir el título del Tab del buscador de internet cuando navegamos al nuevo componente:

```razor
<PageTitle>Nuevo Componente Mensaje</PageTitle>
```

5. Incluir la ruta del nuevo componente en el componente Menú de navegación: **NavMenu.razor** 

```razor
...
 <div class="nav-item px-3">
     <NavLink class="nav-link" href="mensaje">
         <span class="bi bi-list-nested-nav-menu" aria-hidden="true"></span> Mensaje Nuevo
     </NavLink>
 </div>
...
```

6. Ejecutar la aplicación y validar el nuevo componente

![image](https://github.com/user-attachments/assets/cd8e844a-7854-4169-860c-0c9026191942)

