# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/therealsohaib/Full-Stack-CRUD-APP.git).


### How to Run
    1. Clone this repository
    2. Export database
    3. Open dir server-react
    4. Run server, type PORT=5500 node bin/www
    5. Back to root dir, then type npm-start
    6. Done. 

  To get a local copy of the code, clone it using git:

```
git clone https://github.com/therealsohaib/Full-Stack-CRUD-APP.git
cd Full-Stack-CRUD-APP
```
Install dependencies:

```
npm install
```
Now, you can start a local web server by running:

```
npm start
```
and then you can open http://localhost:3000 to view it in the browser.

### Config database
<pre>

    var connection = mysql.createConnection({
        host: 'localhost',
        user: 'root',
        password: '',
        database: 'db_mhs'
    });
</pre>

### Available Scripts
| Script        | Description                                                             |
| ------------- | ----------------------------------------------------------------------- |
| npm start     | Runs the app in development mode.                                   |
| npm test      | Launches the test runner in the interactive watch mode.                 |
| npm run build | Builds the app for production to the `build` folder.                    |
| npm run eject | This command will remove the single build dependency from your project. |

### Credits

CRUD App is built and maintained by [Sohaib Hassan](https://www.linkedin.com/in/sohaibhassan6/).

### License

CRUD App is open-source software licensed under the [MIT License](https://github.com/therealsohaib/Full-Stack-CRUD-APP/blob/main/LICENSE.md).
