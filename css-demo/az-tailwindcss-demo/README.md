# Alfred's tailwindcss examples

## Installation
Pretty much follow the [official guide](https://tailwindcss.com/docs/installation)

### Install tailwind css

```
npm install -D tailwindcss
npx tailwindcss init
```

### Edit tailwind.config.js
```javascript
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### Edit src/input.css
```javascript
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Start the tailwind CLI build process
```
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```


## How to run?
