# noscript-js-redbar
Add notification to top of page when javascript is disabled, similar to Stack Exchange sites.

To use, either add to templates directory and include in existing template (Jinja, etc, with `{% include noscript.html %}`), or extract parts that suit your needs. For PHP, convert the main file into a PHP (`noscript.php`) file and include as needed `include('path/to/noscript.php')`. For static site, include the `<noscript>` block in your HTML page without CSS and place the CSS in your stylesheet.

For more information or to reach out, contact me at nick (at) cistechconsulting (dot) com
