Facturación sobre symfony.
========================

(usabilidad y validaciones generales)

Parte 1:															 
--------------------------------

### Importacion y visualizacon de xmls.
### Templatets  de facturas en pdf.

Parte 2:															(usabilidad y validaciones generales)
--------------------------------

### Generacion de xmls desde formulario y web service. 				.
	

Depende de Sonata Admin Bundle:
	
	sigan el link para ver la instalacion
	
	http://sonata-project.org/bundles/admin/master/doc/reference/installation.html


y tambien depende de FOSUserBundle:  

### Using the vendors script

Add the following lines in your deps file:

	[FOSUserBundle]
		git=git://github.com/FriendsOfSymfony/FOSUserBundle.git
		target=bundles/FOS/UserBundle

### Using submodules

If you prefer instead to use git submodules, then run the following:

	$ git submodule add git://github.com/FriendsOfSymfony/FOSUserBundle.git vendor/bundles/FOS/UserBundle
	$ git submodule update --init

