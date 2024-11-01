# Movies List

> DON'T use Typescirpt in this task

You are given movies loaded from the API and initial markup. Your task is to:

1. Render movies from a given `moviesFromServer` array (for the simplicity, you can do it inside the `App` and split later).
1. Extract a `.movies` block to a `MovieList` component.
1. The `App` should pass the `moviesFromServer` to the `MovieList` as a `movies` prop.
1. Extract a `.card` block to a `MovieCard` component.
1. The `MovieList` should pass a `movie` to the `MovieCard`.
1. Use `movie.imdbId` as a key.
1. Keep all `data-cy` attributes to pass the tests.

## Instructions
- Install Prettier Extention and use this [VSCode settings](https://mate-academy.github.io/fe-program/tools/vscode/settings.json) to enable format on save.
- Implement a solution following the [React task guideline](https://github.com/mate-academy/react_task-guideline#react-tasks-guideline).
- Open one more terminal and run tests with `npm test` to ensure your solution is correct.
- Replace `<your_account>` with your Github username in the [DEMO LINK](https://Dorosh90.github.io/react_movies-list-js/) and add it to the PR description.
