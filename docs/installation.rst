############
Installation
############

.. vim:tw=0:ts=3:sw=3:et:norl:nospell:ft=rst

.. |virtualenv| replace:: ``virtualenv``
.. _virtualenv: https://virtualenv.pypa.io/en/latest/

.. |workon| replace:: ``workon``
.. _workon: https://virtualenvwrapper.readthedocs.io/en/latest/command_ref.html?highlight=workon#workon

To install system-wide, run as superuser::

    $ pip3 install tempita-hotoffthehamster

To install user-local, simply run::

    $ pip3 install -U tempita-hotoffthehamster

To install within a |virtualenv|_, try::

    $ cd "$(mktemp -d)"

    $ python3 -m venv .venv

    $ . ./.venv/bin/activate

    (tempita-hotoffthehamster) $ pip install tempita-hotoffthehamster

To develop on the project, link to the source files instead::

    (tempita-hotoffthehamster) $ deactivate
    $ git clone git@github.com:doblabs/tempita-hotoffthehamster.git
    $ cd tempita-hotoffthehamster
    $ python3 -m venv tempita-hotoffthehamster
    $ . ./.venv/bin/activate
    (tempita-hotoffthehamster) $ make develop

After creating the virtual environment, it's easy to start
developing from a fresh terminal::

    $ cd tempita-hotoffthehamster
    $ . ./.venv/bin/activate
    (tempita-hotoffthehamster) $ ...

