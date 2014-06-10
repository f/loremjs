Lorem.js Dummy Text/Image Generator jQuery and Native JS
========================================================
A Lorem Ipsum creator service written on JavaScript.


Implementation
--------------

Implementation of Lorem.js is so simple,

You just download and add

    <script src="path/to/lorem.js"></script>

into your website/application and run.

If you want to put a lorem text inside a DIV (etc.) tag just write:

    <div data-lorem="2p"></div>

If you want a random length of lorem text within a range just write:

    <div data-lorem="2-4p"></div>

Querying
--------

Lorem.js has a simple query language: "how many?, what?"

    2p = 2 paragraphs
    5s = 5 sentences
    6w = 6 words
    1-6w = between 1 and 6 words

That's it.

Dummy Images
------------

And Lorem.js uses lorempixum.com for images for now.

Usage:

    <img src="" data-lorem="sports/1/Test message" width="223" height="223">
    <img src="" data-lorem="gray" width="100" height="124">
    <img src="" data-lorem="gray animals" width="100" height="124">

And watch what happens :)

Native JavaScript (without any framework)
----------------------------------------

If you want to use Lorem generator natively, (without jQuery).

With Native support, you can lorem.js into your framework.

Usage:

    var lorem = new Lorem;
    lorem.type = Lorem.TEXT;
    lorem.query = '2p';
    lorem.createLorem(document.getElementById('lorem'));

Feel free to ask questions.