# Git - das unbekannte Wesen

## Binaries holen

### Auf Linux

  * Binaries aus dem Paketmanager (Ubuntu)
    * `apt-get git-core`
    * `apt-get git-gui`
    * `apt-get git-doc`
    * `apt-get git-svn`

  * ... oder kompilieren
    * [Web UI to browse source](http://git.kernel.org/?p=git/git.git;a=summary)
    * Git Repository der Sourcen: `git://git.kernel.org/pub/scm/git/git.git`
    * Zip-Archiv der Sourcen: `http://kernel.org/pub/software/scm/git/`
    * Run `make`
    * Then run `make install`

### Auf Windows
  * [TortoiseGit]: [http://code.google.com/p/tortoisegit/]
  * [msysgit]: [http://code.google.com/p/msysgit/]
	
## Das erste Git-Repository erstellen (init)
	* Erstellen eines leeren Repository
		* `cd <arbeitsverzeichnis>`
		* `git init`
Mit nur einem Befehl erstellt man ein vollwertiges lokales Repository!
	
## Dateien in das Repo aufnehmen (add + commit)
...
## Status und Historie
...
## Synchonisierung von dezentralen Repos (remote, push + pull)
...
## ...
