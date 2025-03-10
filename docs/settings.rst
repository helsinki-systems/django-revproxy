Settings
========

Our configurations are all namespaced under the ``REVPROXY`` settings.

For example:

.. code-block:: python

    REVPROXY = {
        'QUOTE_SPACES_AS_PLUS': True,
        'MIN_STREAMING_LENGTH': 4 * 1024,
    }


List of available settings
--------------------------

QUOTE_SPACES_AS_PLUS
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Default: ``True``

Indicates whether spaces should be replaced by %20 or + when parsing a URL.

MIN_STREAMING_LENGTH
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Default: ``4 * 1024``

Variable used to represent a minimal content size required for response to be
turned into stream
