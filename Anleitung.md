# Git - das unbekannte Wesen

## Binaries holen

### Auf Linux

  * Binaries aus dem Paketmanager (Ubuntu)
	apt-get git-core
	apt-get git-gui
	apt-get git-doc
	apt-get git-svn

  * ... oder kompilieren
    * [Web UI to browse source](http://git.kernel.org/?p=git/git.git;a=summary)
    * Git Repository der Sourcen: `git://git.kernel.org/pub/scm/git/git.git`
    * Zip-Archiv der Sourcen: `http://kernel.org/pub/software/scm/git/`
    * Run `make`
    * Then run `make install`

### Auf Windows
  * [TortoiseGit](http://code.google.com/p/tortoisegit/)
  * [msysgit](http://code.google.com/p/msysgit/) bzw. [PortableGit](http://code.google.com/p/msysgit/downloads/list?can=2&q=PortableGit)
	
## Das erste Git-Repository erstellen (init)
Es ist recht simpel, eines leeren Repository zu erstellen.

	cd <arbeitsverzeichnis>
	git init

Mit nur einem Befehl erstellt man ein vollwertiges lokales Repository!

## Arbeitskopie erstellen (fetch / clone)
Besteht bereits ein Repository mit Inhalt, erstellt man sich
eine lokalte Arbeitskopie in einem eigenen Git-Repository. Dazu erstellt man im gewuenschten Verzeichnis ein neues Repository (init) und holt sich eine Kopie.

	git fetch <URL>

Alternativ zu `git init` und `git fetch` gibt es auch die `git clone`, mit dem erst ein neues Verzeichnis erstellt wird, und dann die gewuenschte Kopie gemacht wird.
	
## Dateien in das Repo aufnehmen (add + commit)
...
## Status und Historie (status + log)
...
## Synchonisierung von dezentralen Repos (remote, push + pull)
...
## ...
