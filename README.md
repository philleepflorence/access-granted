## Information

Use htaccess to prevent direct access to media files. 
Allows selective access based of allowed referral urls. 
Ideal for sites where assets can only be viewd within the confines of the site.

## How to use

* Place `.htaccess` file in the root site folder.
* Replace `site.domain` with all the sites you wish to allow access. EG. your site, Facebook, etc.
* Replace `protocol` with appropriate http|https protocol.
* RewriteRule extensions should include extensions of the media files to which you wish to control access.
