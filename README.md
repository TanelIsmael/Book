<h1>Booking</h1>

git clone https://gitlab.com/i-sepp/bcs-koolitus.git
cd bcs-koolitus/
composer install
sudo apt-get install php7.2-sqlite3
mkdir database
php -S localhost:8000 -t web
git remote remove origin
git remote add origin https://github.com/TanelIsmael/Book.git
