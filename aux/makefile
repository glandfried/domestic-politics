all: segato2018-manifesto.pdf segato2016-guerraContraLasMujeres.pdf segato2003-estructuras.pdf segato2013-colonialidad.pdf zaffaroni2013-cuestionCriminal.pdf dussel2004-sistemaMundo.pdf gautier2005-mujeres.pdf

segato2018-manifesto.pdf: biblio/.git
	sh biblio/download.sh segato2018-manifesto
	cp biblio/download/segato2018-manifesto segato2018-manifesto.pdf

segato2016-guerraContraLasMujeres.pdf:
	sh biblio/download.sh segato2016-guerraContraLasMujeres
	cp biblio/download/segato2016-guerraContraLasMujeres segato2016-guerraContraLasMujeres.pdf

segato2003-estructuras.pdf:
	sh biblio/download.sh segato2003-estructuras
	cp biblio/download/segato2003-estructuras segato2003-estructuras.pdf

segato2013-colonialidad.pdf:
	sh biblio/download.sh segato2013-colonialidad
	cp biblio/download/segato2013-colonialidad segato2013-colonialidad.pdf

zaffaroni2013-cuestionCriminal.pdf:
	sh biblio/download.sh zaffaroni2013-cuestionCriminal
	cp biblio/download/zaffaroni2013-cuestionCriminal zaffaroni2013-cuestionCriminal.pdf

dussel2004-sistemaMundo.pdf:
	sh biblio/download.sh dussel2004-sistemaMundo
	cp biblio/download/dussel2004-sistemaMundo dussel2004-sistemaMundo.pdf

gautier2005-mujeres.pdf:
	sh biblio/download.sh gautier2005-mujeres
	cp biblio/download/gautier2005-mujeres gautier2005-mujeres.pdf

biblio/.git:
	git submodule update --init biblio
