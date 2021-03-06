.. RelEng Docs documentation master file, created by
   sphinx-quickstart on Tue Nov 19 11:46:54 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=======================================
Welcome to RelEng Docs's documentation!
=======================================

Here is Mozilla's Release Engineering Group's more technical
documentation. You might also be interested in our `main web site`_.

.. _`main web site`: https://wiki.mozilla.org/Release

Contents:

.. toctree::
   :maxdepth: 2
   :caption: Overview and Procedures

   releng101/index.rst
   releng101/ReleaseDuty-Day-1-Checklist.md
   Cross-team workflows <release_workflows/index.rst>
   procedures/index.rst


.. toctree::
   :maxdepth: 2
   :caption: Documentation and Articles
   :glob:

   architecture/index.rst
   best-practices/index.rst
   future/index.rst
   hosts.rst
   releng_changelog
   software.rst
   addons/addons.rst
   Balrog & Updates <balrog/index.rst>
   Signing <signing/index.rst>
   Release Promotion <release-promotion/overview.rst>

.. toctree::
   :caption: Meta
   :hidden:

   CODE_OF_CONDUCT
   Add a new repo to docs <adding_repo_to_releng_rtfd_account.rst>
   Add existing repo to docs <adding_docs_to_existing_code.rst>
   maintaining_these_docs.rst
   tobewritten.rst


Indices and tables
==================

* :ref:`Modifying these docs`

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

* :ref:`tobewritten`

.. vim: nospell :
