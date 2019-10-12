# Projet Robot

Repo pour les cours de Projet Robot à l'IUT de Cachan

## Règles à respecter

* Avant de démarrer un __projet Mbed__, vous devez avoir un __clone local__ de votre
repo.
* Chaque fichier `.h` (ou `.hpp`) créé doit être placé dans le dossier `include`.
* Chaque fichier `.c`(ou `.cpp`) créé doit être placé dans le dossier `src`.

## Par où commencer

### Comment cloner localement votre repo

* Récupérér le lien de votre repo :
    * Cliquer sur le bouton vert __Clone or download__ et copier l'URL

* Cloner avec __Visual Studio Code__ :
    * Ouvrir Visual Studio Code
    * Appuyer sur `F1`, ensuite taper `clone`, choisissez `Git: Clone`
    * Coller l'URL dans le champ demandé
    * Sauvegarder quelque part (à l'IUT, ce sera dans votre dossier qui est
    dans `C:\Travail`)
    * Cliquer sur `Open Repository`


### Branches, Commits, et Synchronisation
Pas d'explications, il faut pratiquer !

### À la maison

Vous devez installer les logiciels qui vous seront utiles pour travailler à
la maison. Dans l'ordre, installer :
* [Git](https://www.git-scm.com/download)
* [Visual Studio Code](https://code.visualstudio.com/download)
* [Driver ST Link](https://www.st.com/en/development-tools/stsw-link009.html)
* [OpenOCD](http://gnutoolchains.com/arm-eabi/openocd/) (Décompresser le contenu dans `C:\OpenOCD`)
* [Gnu ARM Embedded Toolchain](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads)
(Accepter d'ajouter les éléments dans la variable d'environnement `Path`)
* [Ninja](https://github.com/ninja-build/ninja/releases) (Décompresser le contenu dans `C:\Ninja`)
* [CMake](https://cmake.org/download/)

#### Modification des variables d'environnement sous Windows
* Taper _variables d'environnement_ sur le bouton _Démarrer_
* Cliquer sur le bouton `variables d'environnement`
* Sélectionner la variable `Path` puis cliquer sur `Modifier`
    * Ajouter le chemin vers _OpenOCD_ (par exemple : `C:\OpenOCD\bin`)
    * Ajouter le chemin vers _Ninja_ (par exemple : `C:\Ninja`)

Ensuite, installer les extensions sur Visual Studio Code
* Pour cela, cloner juste votre repo sous Visual Studio Code
* Accepter toutes les requêtes de Visual Studio Code.
