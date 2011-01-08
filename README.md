# ensembl-download-java

This is some code I have developed during my PhD thesis to download genomes
and orthologues from Ensembl in Java, using the
[ensj](https://sourceforge.net/projects/ensj/) API.

The repository has been reconstructed from regular backups I had, but this
means there are no useful commit messages.
It is there for historical purposes, as a legacy. It worked at the time,
but I quickly decided to use BioMart instead.

It is very likely that the code won't work on recent versions of Ensembl !

## Dependencies

You will need to add two JAR files in your _CLASSPATH_:
- [`ensj-39.2.jar`](http://genesis.ugent.be/maven2/org/ensembl/ensj/39.2/ensj-39.2.jar)
- `mysql-connector-java-3.1.8-bin.jar`

# License and copyright

This code may be freely distributed and modified under the terms of the GNU General Public License version 3 (GPL v3)
and the CeCILL licence version 2 of the CNRS. These licences are contained in the files:

1. LICENSE-GPL.txt (or (http://www.gnu.org/licenses/gpl-3.0-standalone.html))
2. LICENCE-CeCILL.txt (or [http://www.cecill.info/licences/Licence_CeCILL_V2-en.html])

Copyright for this code is held jointly by the Dyogen (DYnamic and
Organisation of GENomes) team of the Institut de Biologie de l'Ecole
Normale Supérieure (IBENS) 46 rue d'Ulm Paris, and the individual authors
(Matthieu Muffato).

