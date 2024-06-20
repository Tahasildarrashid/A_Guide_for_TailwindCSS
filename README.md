# A_Guide_for_TailwindCSS

## How to setup Tailwind CSS
#### Step 1: Run the following commands

```bash
  npm install -D tailwindcss
```
```bash
  npx tailwindcss init
```

## Step 2: Now Update tailwind.conf.js file to include this line:
```bash
  content: ["*.html"],
```

## Step 3: create src/input.css to include:

```bash
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
```

## Step 4: Include the src/output.css file to your html

## Step 5: Run the following command:

```bash
  npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```
