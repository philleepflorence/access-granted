## Information

Prevent direct access to media files (preventing users from downloading files). 
Allows selective access based of allowed referral urls. 
Ideal for sites where assets can only be viewed within the confines of the site.

## How to use

* Place `.htaccess` file in the root site folder.
* Replace `site.domain` with all the sites you wish to allow access. EG. your site, Facebook, etc.
* Replace `protocol` with appropriate http|https protocol.
* RewriteRule extensions should include extensions of the media files to which you wish to control access.
