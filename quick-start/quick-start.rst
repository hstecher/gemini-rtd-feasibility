Quick Start Guide
=================

.. toctree::
   :caption: pandoc

   Pandoc <pandoc>   

**Convert docs to rst**
 1. pandoc -help
 2. Example: 
  * ``pandoc -f pdf -t rst filename.pdf -o filename.rst``
 3. Example with images: 
  * ``pandoc -f pdf -t rst filename.pdf -o filename.rst --extract-media=./media``

**Put docs in Gemini RTD Feasibility Git Repo**
 1. Install git 
  * ``yum install git``
 2. Clone repo 
  * ``git clone https://github.com/hstecher/gemini-rtd-feasibility.git``
 3. Copy rst files into the appropriate repo directory
  * ``pdfs/``
  * ``html/``
  * ``wiki/``
  * ``other/``
 4. Add new files to git 
  * ``git add filename.rst``
 5. Edit the appropriate index.rst 
  * ``vi pdfs/pdfs-index.rst``
    * ``.. toctree::``
      ``   :caption:  PDF Resources ``

      ``   Gemini Application Developers Guide <ade>``
      ``  <add new files here>``
 6. Commit new files 
  * ``git commit filename.rst -m "comment"``
  * ``git commit pdfs-index.rst -m "comment"``
 7. Push new files to git & Read-The-Docs
  * ``git push origin master``
 8. After the ``git push`` Read-The-Docs will take a few minutes to upload your docs
 9. View updated `docs <https://gemini-rtd-feasibility.readthedocs.io/en/latest/index.html>`_
  * The github.com repo page will also have a link to the documents on Read-The-Docs

 `reStructuredText Primer <https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>`_

 `TOC Tree usage <https://www.sphinx-doc.org/en/1.5/markup/toctree.html>`_ 


