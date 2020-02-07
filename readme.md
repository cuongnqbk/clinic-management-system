<p align="center"><a href="https://ibb.co/QFCRvVb"><img src="https://i.ibb.co/8DdpgwK/Screenshot-from-2019-06-09-19-32-25.png" alt="Screenshot-from-2019-06-09-19-32-25" border="0"></a></p>

# Login as Admin(*must import sql file ./database/hms.sql to mysql database*)

username = Superadmin

password = superadmin


# Migration and DB seeder (after changing your DB settings in .env)
php artisan migrate --seed

# Generate JWT secret key
php artisan jwt:secret

# install dependency
npm install

# develop
npm run dev # or npm run watch

# Build on production
npm run production
