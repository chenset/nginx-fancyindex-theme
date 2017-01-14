# nginx-fancyindex-theme

Copy ```fancyindex-theme``` to web root directory;

Nginx configure
```
server {

  ...
  
  fancyindex on;
  fancyindex_localtime on;
  fancyindex_exact_size off;
  fancyindex_header "/fancyindex-theme/header.html";
  fancyindex_footer "/fancyindex-theme/footer.html";
  fancyindex_ignore "fancyindex-theme";
  fancyindex_name_length 255;
  
  ...
  
```
