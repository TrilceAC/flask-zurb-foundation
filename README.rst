lask-zurb-foundation
=======================


Flask-Zurb-Foundation packages `Foundation 5
<http://foundation.zurb.com/>`_ (*5.5.1*) into an extension as a blueprint called foundation.
So far it justs wrappes a project in the basic `Foundation 5
<http://foundation.zurb.com/>`_ styles and scripts.


Usage
------

In Flask
***********

Just wrapp your aplication like this::

    from fask_zurb_foundation import Foundation

     [...] # your initiation code here

     Foundation(app)


Now you will have a "*foundation/base.html*" template at your disposition to start developing your project fast enough.

In your templates
*******************

{% extends "foundation/base.html" %}

 <!-- your html/jinja2 code goes here -->



What it loads
---------------

It loads different libraries automatically (support for choosing might be added in the future). Some of these come with Foundation 5

1. `HTML5 shiv
<https://github.com/aFarkas/html5shiv>`_ - The HTML5 Shiv enables use of HTML5 sectioning elements in legacy Internet Explorer and provides basic HTML5 styling for Internet Explorer 6-9, Safari 4.x (and iPhone 3.x), and Firefox 3.x.
#. `RespondJS
<https://github.com/scottjehl/Respond>`_ - A fast & lightweight polyfill for min/max-width CSS3 Media Queries
#. `FastClick
<https://github.com/ftlabs/fastclick>`_ - FastClick is a simple, easy-to-use library for eliminating the 300ms delay between a physical tap and the firing of a click event on mobile browsers.
#. `jQuery
<http://jquery.com/>`_ - v 2.1.3
#. `Modernizer
<http://modernizr.com/>`_ - JavaScript library that detects HTML5 and CSS3 features in the user’s browser

# TODO
------------

Por ahora todo es estático

