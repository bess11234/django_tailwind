# INSTALL TAILWIND
```
npm install -D tailwindcss
npx tailwindcss init
```

```js
// tailwind.config.js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    './**/templates/*.html',
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
```
npx tailwindcss -i ./static/input.css -o ./static/output.css --watch
```

# RUN SERVER
```py
npm run start
```
```py
py manage.py runserver
```
