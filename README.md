# jquery-qr: a jQuery plugin

jquery-qr is a jQuery plugin that create QR code image popups from &lt;a&gt; tags href values.


## Usage

    <html>
      <head>
        <script type="text/javascript" src="http://code.jquery.com/jquery-1.4.2.js"></script>
        <script type="text/javascript" src="jquery-qr.js"></script>
    
        <script type="text/javascript">
          $(document).ready(function() {
            $("a").qr();
          });
        </script>
        
      </head>
  
      <body>
        <a href="http://www.google.com">Google</a><br/>
        <a href="mailto:farmisen@gmail.com">farmisen@gmail.com</a><br/>
      </body>
  
    </html>


## Inspired by:

* [New AndroidPolice.com Feature: Instant QR Magic - Hover On Any Link In Any Post To Get The Corresponding QR Code](http://www.androidpolice.com/2010/09/15/new-androidpolice-com-feature-instant-qr-magic-hover-on-any-link-in-any-post-to-get-the-corresponding-qr-code-poll/) by  Artem Russakovskii

## Author

[Fabrice Armisen]

## Other

[MIT License](http://www.opensource.org/licenses/mit-license.php)

Copyright (c) 2010, Fabrice Armisen (farmisen [*at*] gmail [*dot*] com)