# How to create an app using ReactJS framework?

<br>

### Create a [new React app](https://reactjs.org/docs/create-a-new-react-app.html).

```shell
# Replace 'my-app-name' with your app directory name
npx create-react-app my-app-name

# Go inside the app directory
cd my-app-name

# IMPORTANT: Don't run this command now. Run it after installing the following packages.
npm start
```

<br>

### Install [Bootstrap](https://getbootstrap.com/) framework.

```shell
# Install Bootstrap version 4.5.0
npm install bootstrap@4.5.0
```

<br>

### Import Bootstrap's CSS file in `src/index.js` file

```shell
import 'bootstrap/dist/css/bootstrap.min.css';
```

<br>

### Install [React Bootstrap](https://react-bootstrap.github.io/) package.

```shell
npm install react-bootstrap
```

To use [`react-bootstrap`](https://react-bootstrap.github.io/) package in your React app, import the component(s) you want to use like this:

```shell
import { Table, Button, Alert } from 'react-bootstrap';
```

<br>

### Install [Material Design Icons](https://materialdesignicons.com/)

```shell
npm install @mdi/react @mdi/js
```

- [How to use Material Design Icons with ReactJS?](https://dev.materialdesignicons.com/getting-started/react).
- When you click any icons from [the Material Design Icons list](https://materialdesignicons.com/), you will see how to use it with ReactJS (This list may take some moments to show up).
- [This is another list of all Material Design Icons and thier names](https://cdn.materialdesignicons.com/5.3.45/).

<br>

### Install [x-framework](https://github.com/AmrMekkawy/x-framework) package

```shell
npm install x-framework
```

<br>



<br>

## Useful Resources

- #### [Airbnb React/JSX Style Guide](https://github.com/airbnb/javascript/tree/master/react).