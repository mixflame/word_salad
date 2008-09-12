= Word Salad

== DESCRIPTION:

Word Salad is a very simple Ruby library for generating random strings
of English words based on the Unix dictionary file. The gems does its
best to figure out where your particular dictionary file is, but on
some systems may need a little help.

== SYNOPSIS:

Generating random data is helpful for all kinds of testing. You could
just generate random gobble-dee-gook, but why not generate something
that looks a bit English-like? If for no other reason, you'll find great
enjoyment in all of the potential band-names that this gem generates.

    require 'rubygems'
    require 'word_salad'

    include WordSalad

    words(3) ==> ['draw', 'ameliorate', 'bonanza']
    sentences(2) ==> ['Shoot jonesing the make castle.', 'Blue murdered slight bastion.']
    paragraphs(2) ==> []

WordSalad is a module, so including it in your class will activate
WordSalad's latent, random-generation super-powers in your class.

== INSTALL:

To install Word Salad, simply:

    sudo gem install word_salad

== LICENSE:

(The MIT License)

Copyright (c) 2008 Alex Vollmer

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.