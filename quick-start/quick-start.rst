Quick Start Guide
=================

.. toctree::
   :caption: pandoc

   Pandoc <pandoc>   

**Convert docs to rst**
 1. pandoc -help
 2. Example: ''pandoc -f pdf -t rst filename.pdf -o filename.rst''
 3. Example with images: ''pandoc -f pdf -t rst filename.pdf -o filename.rst --extract-media=./media''

**Put docs in Gemini RTD Feasibility Git Repo**
 1. Install git (yum install git)
 2. Clone repo
	* git clone https://github.com/hstecher/gemini-rtd-feasibility.git


   'reStructuredText Primer <https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html>'_

   'TOC Tree usage <https://www.sphinx-doc.org/en/1.5/markup/toctree.html>'_ 
