### Installation

1. Get your free Pusher API Keys at [https://pusher.com](https://pusher.com)
2. Clone this repo
3. Install Composer packages
    ```sh
    composer install
    ```
4. Install NPM packages
    ```sh
    npm install
    ```
5. Create a mysql database with your desired name and update DB_DATABASE in `.env`
6. Enter your API keys in `.env`
    ```
     PUSHER_APP_ID=
     PUSHER_APP_KEY=
     PUSHER_APP_SECRET=
     PUSHER_APP_CLUSTER=
    ```
7. Migrate
    ```sh
    php artisan migrate
    ```
8. Compile the webpages and run it
    ```sh
    npm run dev
    php artisan serve
    ```

<!-- USAGE EXAMPLES -->

## Usage

Go to http://127.0.0.1:8000/, register a couple of users and start chatting!

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
