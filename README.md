# CURSO: APRENDE BLAZOR

# LECCIÓN 5: Cómo crear tu primer Componente (Visual Studio 2022)

1. Abrir la aplicación Blazor con Visual Studio 2022

2. Crear un nuevo Componente **Mensaje.razor**

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

5. Incluir la ruta del nuevo componente en el **NavMenu.razor** 

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
