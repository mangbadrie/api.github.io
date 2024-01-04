

- Install package

    ```bash
    composer install
    ```

- Create .env file

    ```bash
    cp .env.example .env
    ```

- Create key application

    ```bash
    php saya key
    ```

- Push on your github.
- Create new project in vercel.
- Import from your repository.
- Change environment variables in your project on vercel.
- Add this :
  - DB_HOST (your host cloud dbms)
  - DB_PASS (your password cloud dbms)
  - DB_USER (your username cloud dbms)
  - DB_NAME (your name of database cloud dbms)
  - DB_PORT (your port cloud dbms)
  - DB_DRIV (type cloud dbms [ex. mysql or pgsql])
  - JWT_KEY [ex. 123]
  - HTTPS [true]
  - DEBUG [false]
  - LOG [false]
  - COOKIE [false]
  - APP_KEY [copy from your local env]
- Click deployments tab in vercel project.
- Click the most recent deploy.
- Click dot three and redeploy.
- Finish.

## Get Started Project

- Create a project with composer

    ```bash
    composer create-project kamu/kamu coba-app
    ```

- Move the folder

    ```bash
    cd coba-app
    ```

- Run in development server

    ```bash
    php saya coba
    ```

## Contributing

I'm very open to those of you who want to contribute to Kamu framework!

## Security Vulnerabilities

If you find a security vulnerability in this Kamu, please email DKL via [dewanakretarta29@gmail.com](mailto:dewanakretarta29@gmail.com).

## License

Kamu framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
