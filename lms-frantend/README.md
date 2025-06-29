# lms-frantend

## setup instruction 
1. clone the project 
``` 
git clone https://github.com/AnilDhuvan/LMS.git
``` 
2. Move into the directory

```
    cd lms-frontend
```

3. install dependencies

```
    npm i
```

4. run the server

```
    npm run dev
```



### Setup instructions for tailwind

[Tail wind official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwindcss

```
    npm install tailwindcss @tailwindcss/vite
```


2. Add file extensions to tailwind config file in the contents property
```
    tailwindcss(),

```

3. Add the tailwind directives at the top of the `index.css` file

```
   @import "tailwindcss";
```


### Adding plugins and dependencies 

```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axi
os react-hot-toast @tailwindcss/line-clamp
```


### Configure auto import sort esline

1. Install simple import sore

```
    npm i -D eslint-plugin-simple-import-sort
```

2. Add rule in `.eslint.cjs`

```
    'simple-import-sort/imports': 'error',
    'simple-import-sort/exports': 'error',
```

3. add simple-import sort plugin in `.eslint.cjs`

```
    plugins: [..., 'simple-import-sort': simpleImportSort,]

```

4. To enable auto import sort on file save in vscode

    - Open `settings.json`
    - add the following config
```
    "editor.codeActionsOnSave": {
    "source.fixAll": true,
    "source.fixAll.eslint": true
  },
  "eslint.experimental.useFlatConfig": true,
  "eslint.validate": ["javascript", "javascriptreact", "typescript", "typescriptreact"]
```