Install and initial Tailwind CSS:
```cd tailwind
npm install -D tailwindcss
npx tailwindcss init
```

Update the content array of your tailwind.config.js to:

```
content: ["./dist/**/*.html"]
```

Create a input.css file in your project root ./tailwind/input.css and add the following tailwind directives:

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Run Tailwind build command
```
npx tailwindcss -i ./tw.css -o ./dist/main.css --watch
```
