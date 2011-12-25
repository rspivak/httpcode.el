::

     _   _ _____ _____ ____   ____ ___  ____  _____   _____ _
    | | | |_   _|_   _|  _ \ / ___/ _ \|  _ \| ____| | ____| |
    | |_| | | |   | | | |_) | |  | | | | | | |  _|   |  _| | |
    |  _  | | |   | | |  __/| |__| |_| | |_| | |___ _| |___| |___
    |_| |_| |_|   |_| |_|    \____\___/|____/|_____(_)_____|_____|

`httpcode.el` provides a simple command `hc` that explains the meaning
of an HTTP status code in minibuffer.

Installation
------------

Copy `httpcode.el` to your `load-path` and add to your `.emacs`:

::

    (require 'httpcode)

Then run it with `M-x hc`


Alternately use `Marmalade <http://marmalade-repo.org>`_:

::

    M-x package-install httpcode

Usage
-----

::

    M-x hc RET Enter HTTP code: 418 RET

    Status code 418
    Message: I'm a teapot
    Code explanation: The HTCPCP server is a teapot

Command line alternative
------------------------

`http://github.com/rspivak/httpcode <http://github.com/rspivak/httpcode>`_