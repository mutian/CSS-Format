CSS Formatter
=============


Description
-----------

You can convert CSS/SASS/SCSS/LESS code to Expanded, Compact or Compressed format. CSS Formatter is just only a formatter, do not supports grammar check and auto correct feature.

**Example:**

* Expanded:

        body {
            background: #fff;
            font: 12px/2em Arial, Helvetica, sans-serif;
        }
        a {
            color: rgba(65, 131, 196, 0.8);
        }
        ol, ul, li {
            margin: 0;
            padding: 0;
        }

* Expanded (Break Selectors):

        body {
            background: #fff;
            font: 12px/2em Arial, Helvetica, sans-serif;
        }
        a {
            color: rgba(65, 131, 196, 0.8);
        }
        ol,
        ul,
        li {
            margin: 0;
            padding: 0;
        }

* Compact:

        body { background: #fff; font: 12px/2em Arial, Helvetica, sans-serif; }
        a { color: rgba(65, 131, 196, 0.8); }
        ol, ul, li { margin: 0; padding: 0; }

* Compact (No Spaces):

        body{background:#fff;font:12px/2em Arial,Helvetica,sans-serif;}
        a{color:rgba(65,131,196,0.8);}
        ol,ul,li{margin:0;padding:0;}

* Compact (Break Selectors):

        body { background: #fff; font: 12px/2em Arial, Helvetica, sans-serif; }
        a { color: rgba(65, 131, 196, 0.8); }
        ol,
        ul,
        li { margin: 0; padding: 0; }

* Compact (Break Selectors, No Spaces):

        body{background:#fff;font:12px/2em Arial,Helvetica,sans-serif;}
        a{color:rgba(65,131,196,0.8);}
        ol,
        ul,
        li{margin:0;padding:0;}

* Compressed:

        body{background:#fff;font:12px/2em Arial,Helvetica,sans-serif}a{color:rgba(65,131,196,0.8)}ol,ul,li{margin:0;padding:0}



Author
------

Created by **Mutian** ([http://mutian.info](http://mutian.info/)).

For more info, you can send email to me: mutian(a)me.com!
