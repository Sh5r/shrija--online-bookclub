# shrija-bookstore
bookstore availability in online 
@@ -0,0 +1,4 @@
RewriteEngine On
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^(.*)$ index.php/$1 [L]
