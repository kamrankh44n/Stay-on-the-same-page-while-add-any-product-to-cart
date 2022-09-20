# Stay-on-the-same-page-while-add-product-to-cart
In your theme.liquid file add this {% render 'ajaxify-cart' %} before the closing body tag </body>.
In the Snippets diretory section, click Add a new snippet:
Name your snippet ajaxify-cart, and click Create snippet:
paste your snippet file code there and save it.
Done. You are ready to go.
NOTE:
Caution: In the pasted code, replace all instances of .size() with .length. The .size() method is depreciated as of JQuery 1.8.
