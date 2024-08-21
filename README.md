![cover](https://github.com/user-attachments/assets/b05234b4-784f-4266-9ea7-838af0bac9c0)

# Redux VS Zustand

This project was initially built with Redux for state management. The goal was to understand the fundamentals of this popular library and the Flux architecture.

Subsequently, the goal was to migrate from Redux to Zustand due to its more concise syntax, lower learning curve and often better performance.

# Prerequisites

- Node.js
- Git

# Getting Started

- Clone the repository (`git clone git@github.com:rodrigofontesdev/rezux.git`)
- Install dependencies (`npm install`)
- Run application (`npm run dev`)
- Run server (`npm run server`)

# I've Learned

- Differences among local, global, and server state
- How Flux architecture works
- Debug application's state changes with Redux DevTools
- Create store on Redux (`createStore`)
- Create slices on Redux (`createSlice`)
- Dispatch actions on Redux (`useDispatch`)
- Read state on Redux (`useSelector`)
- Create custom hooks on Redux
- Fetch data on Redux with Async Thunks
- Migrate a store from Redux to Zustand

# Test

Unit tests was built with Vitest library, on terminal type `npm run test` to run tests.

- [x] It should be able to play
- [x] It should be able to play next video automatically
- [x] It should be able to jump to the next module automatically
- [x] It should not update the current module and lesson index if there is no next lesson available

# Built With

- React
- TypeScript
- Tailwind CSS
- JSON Server
- Redux
- Zustand

# License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
