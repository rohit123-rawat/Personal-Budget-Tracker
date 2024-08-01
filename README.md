## Installation Guidelines :rocket:


1. Navigate to the right directory where your project will be locally saved


2. Clone this repository and move to the `Personal-Budget-Tracker` directory

   ```sh
   git clone https://github.com/rohit123-rawat/Personal-Budget-Tracker.git
   cd Personal-Budget-Tracker
   ```

3. Install dependencies

   ```sh
   composer install
   npm install
   ```

4. npm build

   ```sh
   npm run dev
   ```

5. Make a copy of the `.env.example` file in the same directory and save it as `.env`:

   ```sh
   cp .env.example .env
   ```

6. Run the following command to add the Laravel application key:

   ```sh
   php artisan key:generate
   ```

7. Add the following settings in `.env` file:

   1. define the database configuration.
   2. Add smtp mail configuration to get the mail notification.
8. run migration  

    ```sh
   php artisan migrate
   ```
