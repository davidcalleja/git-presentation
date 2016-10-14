##  git pull

	git pull [options] [<repository> [<refspec>…​]]

Básicamente es un git fetch seguido de un git merge FETCH_HEAD. A continuación se ve el proceso que se desencadena.

	  A---B---C master on origin
	 /
    D---E---F---G master
	^
	origin/master in your repository

Resultado:

	  A---B---C origin/master
	 /         \
    D---E---F---G---H master