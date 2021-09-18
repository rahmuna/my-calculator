# my-calculator



## How to set up and run it

We have firstly to clone the project locally: `git clone https://github.com/rahmuna/my-calculator.git`

1. As soon as the clone process is finished, please run `composer install` so to install the project and all its dependencies.
2. Then, we need to copy `.env.example` file into the same directory (base dir) and rename it to `.env`. This file stores our configuration settings.
3. Next step is to generate a new unique application key by typing `php artisan key:generate`.
4. In our terminal we start a new server `php artisan serve`, which uses PHP's built-in server and by default listens to port `:8000`.