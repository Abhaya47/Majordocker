Step 1
Copy the .env.sample to .env (create the .env file)
Download backend project inside www folder (run the following command in a terminal in this directory)

cd www && git clone https://github.com/Abhaya47/Major_backend.git

Step 2: (start all containers)

docker-compose up -d

Step 3:

ssh inside the lamp-php8 server and run the following commands

cd  /var/www/major_backend
composer install
./init.sh