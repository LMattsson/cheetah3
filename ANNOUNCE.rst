Hello!

I'm pleased to announce version 3.3.3a0, the first alpha release
of release 3.3.3 of branch 3.3 of CheetahTemplate3.


What's new in CheetahTemplate3
==============================

The contributors for this release are ...


What is CheetahTemplate3
========================

Cheetah3 is a free and open source (MIT) Python template engine.
It's a fork of the original CheetahTemplate library.

Python 2.7 or 3.4+ is required.


Where is CheetahTemplate3
=========================

Site:
https://cheetahtemplate.org/

Download:
https://pypi.org/project/CT3/3.3.3a0

News and changes:
https://cheetahtemplate.org/news.html

StackOverflow:
https://stackoverflow.com/questions/tagged/cheetah

Mailing lists:
https://sourceforge.net/p/cheetahtemplate/mailman/

Development:
https://github.com/CheetahTemplate3

Developer Guide:
https://cheetahtemplate.org/dev_guide/


Example
=======

Install::

    $ pip install CT3 # (or even "ct3")

Below is a simple example of some Cheetah code, as you can see it's practically
Python. You can import, inherit and define methods just like in a regular Python
module, since that's what your Cheetah templates are compiled to :) ::

    #from Cheetah.Template import Template
    #extends Template

    #set $people = [{'name' : 'Tom', 'mood' : 'Happy'}, {'name' : 'Dick',
                            'mood' : 'Sad'}, {'name' : 'Harry', 'mood' : 'Hairy'}]

    <strong>How are you feeling?</strong>
    <ul>
        #for $person in $people
            <li>
                $person['name'] is $person['mood']
            </li>
        #end for
    </ul>
