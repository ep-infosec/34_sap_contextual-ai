# Contextual AI Auto-doc
Contextual AI documentation is automatically generated by Sphinx. Here are the steps to regenerate them.

- Install Sphinx and other required packages in requirements.txt in this doc folder.
- Install a stand-alone program pandoc (NOT the python package with the same name) using 
'conda install -c conda-forge pandoc' if you have conda, otherwise refer to http://pandoc.org/installing.html.
- Go to folder doc and run ./apidoc.sh to generate latest HTML documentation.
- Your documentation entry point is doc/build/html/index.html


