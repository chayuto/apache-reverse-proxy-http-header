Apache milti-server HTTP-header reserve proxy with RewriteEngine
===================================

Typical route of localhost will bring to apache, and shows 

`It works!`

with specific header set in browser `X-GoToNginxHeader` , traffic will be routed to dummy nginx docker and shows:

`Welcome to nginx!`

REF:
- https://httpd.apache.org/docs/2.4/mod/mod_rewrite.html
- https://httpd.apache.org/docs/2.4/rewrite/flags.html


Chrome Plugins:
- https://docs.modheader.com/using-modheader/redirect-urls