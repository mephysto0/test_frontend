# Prueba Frontend

## Descripción

El proyecto a desarrollar consiste en un panel de control para listar perros en formato de tabla, agregar nuevos ejemplares y exportar dicha tabla en formato PDF.
Para la implementación del proyecto debe utilizar el frameweork Angular con [ANT Desing UI Kit for Angular](https://ng.ant.design/docs/introduce/en) o [React.js](https://github.com/facebook/create-react-app)
y [ANT Desing UI Kit for React](https://ant.design/docs/react/introduce)/.

<br>

## API Rest
La documentación de la API Rest que debera consumir la puede encontrar en el siguiente enlace: [Dog API](https://dog.ceo/dog-api/documentation/).

<br>

## Requerimientos

| Requerimientos funcionales |
| ------------- |
| La plataforma debe permitir agregar un perro a travez de una ventana modal |
|   La plataforma debe permitir seleccionar la raza del perro con un select |
|   La plataforma debe permitir ingresar el nombre del perro, validando que sean solo caracteres alfabeticos |
|   La plataforma debe permitir ingresar el nombre del dueño del perro |
|   La plataforma debe mostrar una foto de la raza del perro |
| La plataforma debe listar todos los perros agregados en formato de tabla |
| La plataforma debe permir exportar la tabla de perros en formato PDF |
<br>

| Requerimientos no funcionales |
| ------------- |
| Toda la interfaz debe ser construida utilizando ANT Desing UI Kit  |
| La interfaz del landing es de libre creación |

 <br>

 
 ## Wireframes (Prototipos)
 Todos los wireframes se encuantran en la carpeta wireframes en este repositorio.
 <br>

 
## Flujo de desarrollo 🔁
### Formato de commits

```bash
git commit -m  "<tipo>( <alcance> ): detalle breve del cambio"
```

### Convención de commits

- **feat:** Se utiliza cuando se esta confirmando una nueva característica estable, es decir que es algo que no se ha creado antes.
- **fix:** Representa la corrección de una falla(bug) dentro del proyecto.
- **docs:** Representa cambios en la documentación del proyecto.
- **style:** Representa cambios en el estilo (interfaz) del proyecto.
- **refactor:** Representa modificaciones y cambios para optimizar y mejorar el diseño y/o arquitectura.
- **test:** Representa cambios o creación en pruebas del proyecto (unitarias, integración, funcionales, aceptación, …)
- **chore:** Representa cambios o creación en archivos que no afectan funcionalidades programáticas del sistema.

### Subida del proyecto

1. Incialize el repositorio:
   `git init`

2. Pull latest changes:

   `git remote add origin https://github.com/consorcioprogresa/test_frontend.git`

3. Cree una rama con el nombre del candidato, por ejemplo Jose Soto:

   `git checkout -b jose-soto/solution`

5. Subir cambios al repositorio:

   `git push origin jose-soto/solution`


