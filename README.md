Ajax Password Strength Meter Script
===================================

Retrieved on 2013-04-09 from http://simplythebest.net/scripts/ajax/ajax_password_strength.html

AUTHOR: Digital Spaghetti
TYPE: [Open Source MIT License](http://www.opensource.org/licenses/mit-license.php)
BROWSERS: JavaScript enabled IE 6.0+, FF 1.5+, Safari 2.0+, Opera 9.0+

Instructions
============

jQuery password strength meter is a small plugin to jQuery that provides an easy way to show the strength of a user's (intended) password. jQuery is required.

To install the script on your Web page follow these instructions:

1) [Download this ZIP](http://simplythebest.net/scripts/ajax/ajax_files/jsquery_pstrength.zip) with jQuery 1.2.1 and jquery.pstrength-min.1.2.js. Unpack the files and upload both to your server.

2) Insert this anywhere before the password field on the page:
```js
<script type="text/javascript" src="js/jquery.js"></script>  // adjust the path as is required
<script type="text/javascript" src="js/jquery.pstrength-min.1.2.js"></script>
<script type="text/javascript">
    $(function() {
        $('.password').pstrength();
    });
</script>
```

3) Insert `class="password"` into your input box tag to identify a password box:

```html
<INPUT class="password" type=password name="Password">
```

4) Insert these tags into your CSS and modify as is needed:

```css
.password {
    font-size : 12px;
    border : 1px solid #cc9933;
    width : 200px;
    font-family : arial, sans-serif;
}

.pstrength-minchar {
    font-size : 10px;
}
```

You can adjust a few more settings inside the jquery.pstrength-min.1.2.js script, such as messages, length/height of the bar, and so forth.

[Visit the jQuery Web site for more details if needed](http://jquery.com/plugins/project/pstrength)
