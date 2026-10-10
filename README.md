# AngularDashboard

A collection of dashboard templates and examples built with [Angular](https://angular.dev). This repository brings together three subprojects — each included as a Git submodule — showcasing different approaches to building admin panels:

| Subproject | Description |
|---|---|
| `SemanticUI-Admin-Template` | Admin panel template built with [Semantic UI](https://semantic-ui.com). |
| `angular-charts` | Chart and data-visualization examples in Angular. |
| `angular-material-dashboard` | Dashboard built with [Angular Material](https://material.angular.io). |

## Requirements

- [Node.js](https://nodejs.org) (an LTS version is recommended)
- npm (bundled with Node.js)
- [Angular CLI](https://angular.dev/tools/cli):

  ```bash
  npm install -g @angular/cli
  ```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/psehgaft/AngularDashboard.git
   cd AngularDashboard
   ```

2. Enter the subproject you want to explore and install its dependencies:

   ```bash
   cd angular-material-dashboard
   npm install
   ```

3. Start the development server:

   ```bash
   ng serve
   ```

   and open <http://localhost:4200> in your browser.

## Note on the subprojects

Each subproject is pinned as a *gitlink* (a reference to a commit in its original repository) at the commit shown in the repository root. The repository does not include a `.gitmodules` file, so the references are not initialized automatically with `--recurse-submodules`.

## License

This repository does not declare an explicit license.
