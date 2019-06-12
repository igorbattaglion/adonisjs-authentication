# Adonis user authentication

A simple REST API made with adonis.js(**Node.js Framework**) for register new users and authenticate

## Requirements

-   [Node.js](https://nodejs.org)
-   MariaDB or MySQL( or you can use another Database. For supported Databases read [here](https://adonisjs.com/docs/4.1/database#_supported_databases))

## Setup

### Using Git (recommended)

1.  Clone the project from github. Change "myproject" to your project name.

```bash
git clone https://github.com/igorbattaglion/adonisjs-authentication.git ./myproject
```

### Using manual download ZIP

1.  Download repository
2.  Uncompress to your desired directory

### Install Adonis.js globally

```bash
npm install --global @adonisjs/cli
```

### Install npm dependencies after installing (Git or manual download)

```bash
cd myproject
npm install
```

### Setting up environments (development or production)

1.  In the root this repository you will find a file named `.env.example`
2.  The `.env.example` file is configured to use MySQL or MariaDB with default `DB_USER` and `DB_PASSWORD`
3.  Create a new file by copying and pasting the file and then renaming it to just `.env`
4.  The file `.env` is already ignored, so you never commit your credentials.
5.  Change the values of the file to your environment (development or production)
6.  Create the database with the same name as `DB_DATABASE` defined in your `.env` file
7.  Run the following command in your root repository :

    ```bash
    adonis migration:run
    ```


## How to run

Use the following command to run in development mode:

    ```bash
    adonis serve --dev
    ```

By default the server will run in `http://localhost:3333`

## Information

Read more about [Adonis.js](https://adonisjs.com/docs/4.1/installation)

