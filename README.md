
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://minty7410.github.io/lazy/index.html$1 [R,L]
