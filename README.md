# volotovskiy.sasha@gmail.com

#!/bin/bash
sudo apt update
sudo apt install apache2
cd /var/www/html/
sudo service apache2 start

nano index.html
echo '<!DOCTYPE html>' > index.html
echo '<html>' >> index.html
echo '<head>' >> index.html
echo '</head>' >> index.html
echo '<body>' >> index.html
echo '<h1>Oleksandr Volotovskyi</h1>' >> index.html
echo '</body>' >> index.html
echo '</html>' >> index.html
#sudo service apache2 start








