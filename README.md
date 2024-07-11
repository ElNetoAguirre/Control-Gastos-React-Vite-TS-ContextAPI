<div style="display: flex; justify-content: space-between;">
  <p align="center">
    <a href="https://react.dev/" target="blank"><img src="public/react.svg" width="200" alt="React Logo"/></a>
  </p>
  
  <p align="center">
    <a href="https://vitejs.dev/" target="blank"><img src="public/vite.svg" width="200" alt="Vite Logo"/></a>
  </p>

  <p align="center">
    <a href="https://www.typescriptlang.org/" target="blank"><img src="public/typescript.svg" width="200" alt="TypeScript Logo"/></a>
  </p>
</div>

# Control de Gastos - React + Vite + TypeScript + ContextAPI

Aplicación creada con [React](https://react.dev/) y [Vite](https://vitejs.dev/) usando [TypeScript](https://www.typescriptlang.org/), la cual es un Planificador de Gastos en que puedes definir un presupuesto y añadir diferentes tipos de gastos, puedes editar, filtrar o eliminar dichos gastos y la aplicación irá haciendo los cálculos necesarios para indicarte como van tus finanzas, es persistente hasta que presiones el botón de **Reiniciar App**.

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. [TailwindCSS](https://www.npmjs.com/package/tailwindcss).
2. [HeadlessUI](https://headlessui.com/).
3. UseState.
4. useEffect.
5. UseReducer.
6. UseMemo.
7. ContextAPI.
8. [uuid](https://www.npmjs.com/package/uuid).
9. Local Storage.
10. [Heroicons](https://www.npmjs.com/package/@heroicons/react).
11. Formularios.
12. Validaciones.
13. [react-date-picker](https://www.npmjs.com/package/react-date-picker).
14. [react-calendar](https://www.npmjs.com/package/react-calendar).
15. [react-swipeable-list](https://www.npmjs.com/package/react-swipeable-list).
17. [react-circular-progressbar](https://www.npmjs.com/package/react-circular-progressbar).
18. Y más.

# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
