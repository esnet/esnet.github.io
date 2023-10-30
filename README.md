# ESnet Software Page

The repository here contains HTML (and document sources) for
http://software.es.net/.  This file provides information deemed useful
when committing changes to that page.

## Dependencies

The rendering infrastructure for software.es.net is based on what's in the
esnet-gh-pages-base repo, and the software dependencies are in fact
the same.  Primarily this means installing Sphinx, a Python
documentation tool.  The Sphinx installation steps below are copied
from the esnet-gh-pages-base documentation:

### Sphinx Installation using Mac OS X Base Python

1. ```sudo /usr/bin/easy_install pip```
2. ```sudo /usr/local/bin/pip install sphinx sphinx-bootstrap-theme```

### Sphinx Installation using MacPorts

1. ```sudo port install python27 py27-pip py27-sphinx```
2. ```sudo port select pip py27-pip```
3. ```sudo port select sphinx py27-sphinx```
4. ```pip install sphinx sphinx-bootstrap-theme```

In general, building the HTML and previewing works the same as for any
other ESnet software project using the esnet-gh-pages-base
infrastructure.

## Updates

A major difference between this repo and project documentation sites
is that for project documentation sites, the document sources live in
a subdirectory on the master branch and get deployed to the gh-pages
branch of the repo.  For this repo, the document sources live in the
page-source branch of this repo and they get deployed to the master
branch.

1.  ```git clone git@github.com:esnet/esnet.github.io.git```
2.  ```git checkout origin/page-source -b feature/featureChange```
3.  Edit ```docs/index.rst```.  This file is in ReStructured Text
    format (see http://www.sphinx-doc.org/en/stable/rest.html for
    details).
4.  Push your branch and create a pull request.
5.  Once approved, the software.es.net should automatically be updated.
