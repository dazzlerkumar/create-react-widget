
# Create React Widget

The create-react-widget CLI tool is designed to simplify the process of creating web widgets using ReactJS. This tool sets up a template project that leverages React, Axios, Webpack, and React Router DOM to create embeddable widgets for web applications.




## Features

- Quickly create a project template for web widgets.
- Utilizes React for building dynamic user interfaces.
- Integrates Axios for making HTTP requests.
- Uses Webpack for bundling and managing assets.
- Includes React Router DOM for easy navigation within the widget. (Uses virtual routing)



## Installation

Install the create-react-widget CLI tool globally using npm or yarn:

```bash
  npm install -g create-react-widget
  # or
  yarn global add create-react-widget
```
    
## Usage

To create a new widget project, run the following command:
```bash
   create-react-widget my-widget
   cd my-widget
```

Replace my-widget with the name of your widget project. This command will create a new directory containing the project files and dependencies.


### **Development Mode:**

To run the project in development mode, use the following command:

```bash
npm run dev
```

This command will start the webpack development server, and you can access the widget at http://localhost:8080.

### Production Mode (Development Server):

For a production-like environment with the webpack development server, use:

```bash
npm run devprod
```

### Production Build:

To build the project for production, run:

```bash
npm run prod
```

This will generate optimized files in the `dist` directory.

### Testing: (test cases aren't defined yet)

Run tests using the following command:

```bash
npm run test
```
## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an [issue](https://github.com/dazzlerkumar/create-react-widget/issues/new).


## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/dazzlerkumar/create-react-widget/blob/main/LICENSE) file for details.


## Authors

- [@dazzlerkumar](https://www.github.com/dazzlerkumar)

