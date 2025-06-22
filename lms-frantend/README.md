# lms-frantend

## setup instruction 
1. clone the project 
``` 
git clone https://github.com/Anilkumar7182/Lms/lms-frantend.git
``` 
2. move into the directory
``` 
cd lms-frotend

```
3. install dependencies
```  
npm install 
```
4.1 install tailwindcss 
```
npm install -D tailwindcss
npx tailwindcss init

```
 4.2 tailwind.config.js
```
 content: ["./src/**/*.{html,js,jsx,ts,tsx,}"],

```
4.3 src/input.css -->

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
5. Add plugins and  dependencies
```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axios react-hot-toast @tailwindcss/line-clamp 
```

5. run server
```
npm run dev

```

