.. _how-to-refer-page:

===========================
 How to Refer to @package_name@ ?
===========================

Up to now, the official url for @package_name@ is @project_url@

*A permanent redirection will be implemented if the domain change in the future.*

On Github, you can use the **@project_name@** `topic <https://github.com/search?q=topic%3A@project_name@&type=Repositories>`_ for repository related to @package_name@.

A typical `BibTeX <https://en.wikipedia.org/wiki/BibTeX>`_ citation would be, for example:

.. code:: bibtex

    @software{@package_name@,
      author = {Fabrice Salvaire}, % actual author and maintainer
      title = {@package_name@},
      url = {@project_url@},
      version = {x.y},
      date = {yyyy-mm-dd}, % set to the release date
    }

    @Misc{@package_name@,
      author = {Fabrice Salvaire},
      title = {@package_name@},
      howpublished = {\url{@project_url@}},
      year = {yyyy}
    }
