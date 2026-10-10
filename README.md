# AngularDashboard

Colección de plantillas y ejemplos de *dashboards* construidos con [Angular](https://angular.dev). El repositorio reúne tres subproyectos —cada uno incluido como un submódulo de Git— con distintos enfoques para crear paneles de administración:

| Subproyecto | Descripción |
|---|---|
| `SemanticUI-Admin-Template` | Plantilla de panel de administración construida con [Semantic UI](https://semantic-ui.com). |
| `angular-charts` | Ejemplos de gráficas y visualización de datos en Angular. |
| `angular-material-dashboard` | Dashboard construido con [Angular Material](https://material.angular.io). |

## Requisitos

- [Node.js](https://nodejs.org) (se recomienda una versión LTS)
- npm (incluido con Node.js)
- [Angular CLI](https://angular.dev/tools/cli):

  ```bash
  npm install -g @angular/cli
  ```

## Uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/psehgaft/AngularDashboard.git
   cd AngularDashboard
   ```

2. Entra al subproyecto que quieras explorar e instala sus dependencias:

   ```bash
   cd angular-material-dashboard
   npm install
   ```

3. Levanta el servidor de desarrollo:

   ```bash
   ng serve
   ```

   y abre <http://localhost:4200> en tu navegador.

## Nota sobre los subproyectos

Cada subproyecto está fijado como un *gitlink* (referencia a un commit de su repositorio original) al commit que se muestra en la raíz del repositorio. El repositorio no incluye un archivo `.gitmodules`, por lo que las referencias no se inicializan automáticamente con `--recurse-submodules`.

## Licencia

Este repositorio no declara una licencia explícita.
