#!/bin/bash
apt-get update -y
apt-get install -y apache2
cat <<EOF> /var/www/html/index.html
<html>
<body>
<p style="font-size:50px;">Direct script </p>
</body>
</html>