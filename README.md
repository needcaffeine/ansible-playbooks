# Readme

This is a collection of my [ansible](https://github.com/ansible/ansible) playbooks.

Usage
-----
The right way to use this repository is to first clone it locally:

    $ git clone git@github.com:needcaffeine/ansible_playbooks.git

Go into the directory and set up a [virtualenv](https://virtualenv.pypa.io), then activate it:

    $ cd ansible_playbooks
    $ virtualenv usr
    New python executable in usr/bin/python2.7
    Also creating executable in usr/bin/python
    Installing setuptools, pip...done.
    $ source usr/bin/activate

What the above does is that it prepares you for the next step, which is installing a whole bunch of ansible dependencies. By setting up and activating a virtualenv, we will be installing all our dependencies inside our repo directory instead of in the global scope, which is bad if different projects need different versions of a package.

Next, we need to install our requirements:

    $ pip install -r requirements.txt

At this point, you're ready to actually run your ansible playbook.
