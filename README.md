## How to use it to develop with React and NExt.js apps locally

On your computer, create a new parent folder or go to an existing folder that you would like to be the parent, for both this library and your React (or Next.js) app. Clone this library and add your
React app inside the parent folder, so that the structure looks like this:

```
Parent folder
|_ _ _ Folder for this library
|_ _ _ Your react or nextjs app's folder
```

### **A. Open a terminal (for the library)**

1. cd into the root of the library folder
2. Install dependencies:
    ```sh
    npm install
    ```
3. Build the library:
    ```sh
    npm run build
    ```

### **B. Open a terminal (for your react or nextjs app)**

1. cd into the root of your app's folder:
2. Link your app to the library:
    ```sh
    npm install ../build-a-component-library-for-react/
    ```
3. Run your app as usual

### **C. Import and use library in your app**

Import at the top of the file:

```sh
import { Button } from 'build-a-component-library-for-react';
```

Use in your react page or component:

```sh
<Button>Any String can be here</Button>
```

### Knowledge from this free and awesome YouTube tutorials:

[The Nerdy Canuck (without webpack)](https://www.youtube.com/watch?v=V_5ImTOmMh0)
