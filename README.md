# 2xx
php/mysql steps to the inside-out-project

https://2xx.nightwolfonline.com


Version 200.0
 - pulled files from clients HTML site and uploaded to development server.
 - updated title tag and header title with PHP variable.
 - converted all HTML comments to PHP comments.
 
 Version 201.0
 - replaced top level pages by changing them to php files (love, who, challenges, you)
 - removed header and footer from the pages replaced
 - created the include files
 - created the header.inc.php and footer.inc.php files
 
 Version 202.0
 - replaced navigation menu with top level pages by creating a function and array to dynamically create the menu(love, who, challenges, you)
 - created the functions.inc.php file
 		created the menuBuilder function
 - created the menu.data.php file
 		created menuItems arrays
 - included in the very top of the header.inc.php a require_once to the include/menu.data.php file
 - included in the very top of the header.inc.php a require_once to the include/functions.inc.php file
  