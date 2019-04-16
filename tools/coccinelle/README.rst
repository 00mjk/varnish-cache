This directory contains `coccinelle`_ semantic patches to facilitate code
maintenance.

Each patch should, in a comment section, explain its purpose. They may be fit
for both the in-tree code style or out-of-tree VMOD and VUT development.

Unless noted otherwise, all patches should work when invoked as::

	spatch --dir . --in-place --sp-file $COCCI

.. _coccinelle: http://coccinelle.lip6.fr/
