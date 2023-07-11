# Movie-Quotes-Upgraded

This is a client-side app for "Movie Quotes Upgraded" project.

### Table of Contents

- [Prerequisites](#prerequisites)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Development](#development)
- [Project Structure](#project-structure)

### Prerequisites

- <img src="readme/assets/node-js.svg" height="18" style="position: relative; margin-right:3px; top: 4px;" /> Node.js@18 and up
- <img src="readme/assets/npm.png" height="13" style="position: relative; top:4px; margin-right: 2px" /> npm@9.5 and up

### Tech Stack

- <img src="readme/assets/vue.png" height="14" style="position: relative; top: 4px; margin-right: 5px" /> [Vue-3 (vue-router, vue-i18n)](https://laravel.com/docs/6.x) - framework for building web user interfaces
- <img src="readme/assets/vee-validate.png" height="19" style="position: relative; top: 4px; margin-right: 3px" /> [VeeValidate](https://vee-validate.logaretm.com/v4) - takes care of value tracking, validation, errors, submissions and more.
- <img src="readme/assets/pinia.svg" height="19" style="position: relative; top: 4px; margin-right: 10px" /> [Pinia](https://pinia.vuejs.org/) - the intuitive store for Vue.js
- <img src="readme/assets/tailwind.png" height="19" style="position: relative; top: 4px; margin-right: 3px" /> [Tailwind](https://tailwindcss.com/) - utility-first css framework

### Getting Started

1\. First of all you need to clone Movie-Quotes-Upgraded repository from github:

```sh
https://github.com/RedberryInternship/giorgi-kvrivishvili-epic-movie-quotes-front
```

2\. Next step requires you to run _npm install_ in order to install all dependencies.

```sh
npm install
```

3\. Now we need to set our env file. Go to the root of your project and execute this command.

```sh
cp .env.example .env
```

And now you should provide **.env** file all the necessary environment variables:

**API:**

> VITE_SERVER_URL=

**Pusher:**

VITE_PUSHER_APP_KEY=
VITE_PUSHER_APP_CLUSTER=

### Development

You can run development server by executing:

```sh
  npm run dev
```

### Project Structure

```bash
├─── public
├─── readme
├─── src
│   ├─── assets
│   ├─── components
│   ├─── composables
│   ├─── config
│   ├─── router
│   ├─── stores
│   ├───  utils
│   ├───  views
│   - App.vue
│   - main.js
- .env
- index.html
- postcss.config.js
- README.md
- tailwind.config.js
- vite.config.js
```
