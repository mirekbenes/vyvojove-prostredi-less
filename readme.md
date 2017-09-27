# Jak nainstalovat vývojové prostředí #
## Windows ##

1. Nainstalovat [Node.js](https://nodejs.org/en/) (ver 6 - latest features).
2. Nainstalovat [GIT](https://git-scm.com/downloads).
3. Do adresáře s šablonami vložit package.json. Pokud není součástí šablon je ke stažení [zde](https://github.com/mirekbenes/vyvojove-prostredi-less/archive/master.zip).
4. Spustit GIT příkazový řádek (GIT-CMD).
5. Nainstalovat globálně gulp `npm install gulp --global`
6. Nainstalovat gulp (do adresáře s šablonami)
`npm install gulp --save-dev`
7. Doinstalovat do projektu rozšiřující balíčky
`npm install gulp-connect gulp-watch gulp-webserver gulp-less gulp-autoprefixer gulp-rename gulp-cache gulp-concat gulp-notify jshint gulp-jshint gulp-uglify gulp-rimraf gulp.spritesmith gulp-svg-sprite gulp-filter gulp-svg2png gulp-plumber gulp-pixrem gulp-cssnano gulp-sourcemaps postcss-critical-split gulp-postcss --save-dev`
8.	Spustit vývojové prostředí `gulp`
9.	Ukončení je možné kombinací Ctrl+C a potvrzením volby - klávesa "Y" a potvrzení Enterem.

**Odstranění vývojového prostředí**

- odstranění gulpu pro danou složku `npm uninstall --save-dev gulp`
- globální odstranění gulpu `npm uninstall -g gulp`

## Mac OS ##

1. Nainstalovat [Node.js](https://nodejs.org/en/) (ver 6 - latest features).
2. Nainstalovat [GIT](https://git-scm.com/downloads).
3. Do adresáře s šablonami vložit package.json. Pokud není součástí šablon je ke stažení [zde](https://github.com/mirekbenes/vyvojove-prostredi-less/archive/master.zip).
4. Spustit Terminál.
5. Nainstalovat globálně gulp `sudo npm install gulp --global`
6. Nainstalovat gulp (do adresáře s šablonami)
`sudo npm install gulp --save-dev`
7. Doinstalovat do projektu rozšiřující balíčky
`sudo npm install gulp-connect gulp-watch gulp-webserver gulp-less gulp-autoprefixer gulp-rename gulp-cache gulp-concat gulp-notify jshint gulp-jshint gulp-uglify gulp-rimraf gulp.spritesmith gulp-svg-sprite gulp-filter gulp-svg2png gulp-plumber gulp-pixrem gulp-cssnano gulp-sourcemaps postcss-critical-split gulp-postcss --save-dev`
8.	Spustit vývojové prostředí `gulp`
9.	Ukončení je možné kombinací CONTROL+C.

**Odstranění vývojového prostředí**

- odstranění gulpu pro danou složku `sudo npm uninstall --save-dev gulp`
- globální odstranění gulpu `sudo npm uninstall -g gulp`