magicxml
========

Simple, cross-browser JavaScript XSLT plugin

What does it do?
----------------

Using JavaScript to render XSLT transformed XML in all browsers is annoying and unecessarily time consuming. Magic XML simplifies cross-browser implementation of this functionality.

By decorating your elements with attributes, Magic XML can also automatically pull in the appropriate XML for you, transform it using a specified XSLT and then push it onto your page - all with just a single line of code.

Setting up your page for Magic XML
----------------------------------
Just [download Magic XML](http://tomdavies.azurewebsites.net/magicxml/downloads/m-xml.zip), unzip the archive and then place either the minified version (m-xml.min.js) or the non-minified (m-xml.js) version into a suitable directory of your site.

Then be sure to add in a reference to Magic XML on the pages where you want to use it, like so...

`<script type="text/javascript" src="m-xml.min.js"></script>`

Full documentation, demo and examples
-------------------------------------
Currently hosted [on the Magic XML page](http://tomdavies.azurewebsites.net/magicxml/).