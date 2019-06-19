### What did we build?

A big old todo list, which saves todos to the browser’s `localStorage`; allowing a user to edit and complete their todos.

### Links

- [Basic demo codebase](https://github.com/martinlaws/todo-list/releases/tag/complete%2Fbasic)
- [Code with `vue-router`](https://github.com/martinlaws/todo-list/releases/tag/complete%2Frouter)
- [Code with `SCSS` and `vue-router`](https://github.com/martinlaws/todo-list/releases/tag/complete%2Fscss)

### What did we talk about?

- Project creation using vue-cli
    - `@vue/cli`
    - `vue ui`
- Create project
- Quick demo of `vue ui`
    - Plugins/Dependencies
    - Configuration
    - Tasks
        - Build and show webpack analysis
- Code formatting: who cares?
    - Add `.prettierrc.js`

    ```js
    module.exports = {singleQuote: true,semi: false};
    ```

- Application structure
    - `public/ndex.html` entrypoint
    - JavaScript app instantiates in `src/main.js`
- Single file components
    - `App.vue` & `HelloWorld`
- Props, Rendering using `{{}}`
- Reactivity in Vue
- Directives, `v-for`, `v-on`, `v-bind`, `v-model`
- Create `ToDoContainer` component
- Scoped styles
- Methods
- Add `localStorage` for data persistence
    - `saveTodo(todo)` method
    - `fetchTodos()` method
- [Deploy to GitHub Pages](https://cli.vuejs.org/guide/deployment.html#github-pages)

## Running the app in development
#### Installs dependencies
```
npm install
```

#### Compiles and hot-reloads for development
```
npm run serve
```

#### Compiles and minifies for production
```
npm run build
```

#### Deploy to [GitHub Pages](https://martinlaws.github.io/todo-list)
```
sh deploy.sh
```

#### Lints and fixes files
```
npm run lint
```

#### Running the Vue UI (optional)
```
vue ui
```

## Additional resources

- [Vue Guide](https://vuejs.org/v2/guide/)
- [Vue Cookbook (more in-depth)](https://vuejs.org/v2/cookbook/)
- [vue-router](https://router.vuejs.org/)
- [Vuex (state management)](https://vuex.vuejs.org/)
- [Vue Mastery (paid, and IMHO worth every penny)](https://www.vuemastery.com/)
- [Sarah Drasner’s Twitter (vue core team) 🔥](https://twitter.com/sarah_edo)
- [Form validation in vue in under an hour](https://css-tricks.com/form-validation-in-under-an-hour-with-vuelidate/)
