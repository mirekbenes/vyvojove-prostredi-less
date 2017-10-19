# Jak nainstalovat vývojové prostředí #
## Windows ##

1. Nainstalovat [Node.js](https://nodejs.org/en/) (ver 6 - latest features).
2. Nainstalovat [GIT](https://git-scm.com/downloads).
3. Spustit GIT příkazový řádek (GIT-CMD).
4. Nainstalovat globálně gulp `npm install gulp --global`
5. Nainstalovat gulp (do adresáře s šablonami)
`npm install gulp --save-dev`
6. Doinstalovat do projektu rozšiřující balíčky
`npm install`
7.	Spustit vývojové prostředí `gulp`
9.	Ukončení je možné kombinací Ctrl+C a potvrzením volby - klávesa "Y" a potvrzení Enterem.

**Odstranění vývojového prostředí**

- odstranění gulpu pro danou složku `npm uninstall --save-dev gulp`
- globální odstranění gulpu `npm uninstall -g gulp`

## Mac OS ##

1. Nainstalovat [Node.js](https://nodejs.org/en/) (ver 6 - latest features).
2. Nainstalovat [GIT](https://git-scm.com/downloads).
3. Spustit Terminál.
4. Nainstalovat globálně gulp `sudo npm install gulp --global`
6. Nainstalovat gulp (do adresáře s šablonami)
`sudo npm install gulp --save-dev`
7. Doinstalovat do projektu rozšiřující balíčky
`sudo npm install`
8.	Spustit vývojové prostředí `gulp`
9.	Ukončení je možné kombinací CONTROL+C.

**Odstranění vývojového prostředí**

- odstranění gulpu pro danou složku `sudo npm uninstall --save-dev gulp`
- globální odstranění gulpu `sudo npm uninstall -g gulp`