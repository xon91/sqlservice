Versioning
==========

This project follows `Semantic Versioning`_ with the following caveats:

- Only the public API (i.e. the objects imported into ``sqlservice.__init__``) will maintain backwards compatibility between MINOR version bumps.
- Objects within any other parts of the library are not guaranteed to not break between MINOR version bumps.

With that in mind, it is recommended to only use or import objects from the main module.


.. _Semantic Versioning: http://semver.org/
