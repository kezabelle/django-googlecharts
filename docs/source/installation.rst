Installing django-googlecharts
******************************

.. todo::

    document the download location on PyPI.

.. todo::

    document usage with pip, when it works.

.. todo::

    document usage with easy_install, when it works.

Via GitHub
==========

To get up and running using the latest development copy, issue the following command in your shell::

    git clone git://github.com/kezabelle/django-googlecharts.git

Additionally, you may wish to add this fork's originating repository::

    git remote add jacobian git://github.com/jacobian/django-googlecharts.git

Depending on where you were when you cloned the repository, you may need to use a *symbolic link* to add the ``googlecharts`` directory to your python path. It is assumed, if you're familiar with git, you're familiar enough with python to know how to do so.

About the git branches
----------------------

The github repository should give you access to the following branches:

* master

  Master is expected to always contain working, runnable code, ad should for the most part by synonymous with the latest release tag.

* develop

  The develop branch is where major changes occur, and is not guaranteed to be in a usable state for any length of time. It should be treated as bleeding-edge, not-for-production use.

.. note::

    There may, from time to time, be more branches running in parallel. Similarly, there may be short lived branches that are used for hacking on specific features or bugs. It is highly recommended you avoid using them.


.. todo:: 

    provide bulletproof line that'd symlink correctly on most systems?
