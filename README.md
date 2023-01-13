# -RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://ALLEN911010.github.io/Aircondition/index.html$1 [R,L]
