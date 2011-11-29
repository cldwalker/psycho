Description
===========

Going psycho with syck to psych conversions? Let psycho handle this syck-psych-o-ness!

Usage
=====

    # I know, I'm the only one who still uses rip
    $ rip install psycho

    # If somebody actually wants this as a gem, let me know
    # $ gem install psycho

    # Before
    $ ruby-1.9.3-p0 -ryaml -e 'p YAML.load_file "some_file.yaml"'
    $*#J$*##*#!!

    $ pyscho some_file.yaml

    # After
    $ ruby-1.9.3-p0 -ryaml -e 'p YAML.load_file "some_file.yaml"'
    :)



Limitations
============

* Assumes you're converting from 1.9.2 to 1.9.3
* Assumes you use rvm for ruby versioning
* Assumes you want the last alphabetically sorted ruby version
* Don't like these assumptions? Pull request!
