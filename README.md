Cascade-Server-SCSS
===================

Modular CSS Compiler/Manager for Cascade Server

Uses the following projects:
- https://github.com/leafo/scssphp
- https://code.google.com/p/cssmin/


Installation
------------
The easiest method of installation is to import the “Modular-SCSS.csse” file. All PHP, Blocks, Formats, and Data Definitions are included. The Formats, Data Definitions, etc., are also included here to make updates easier going forward.

After the Site is imported, the following steps need to be performed:
- Set up Transport/Destination: needs to point to PHP-enabled server compiled with SOAP support
- Fill in fields for “/-system/—Web Services Authentication” Block
—- Web Services Username & Password (needs access to all CSS files)
—- URL of Cascade Server Instance 
—- URL of SCSS Publish Site