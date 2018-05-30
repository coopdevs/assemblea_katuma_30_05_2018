# Assemblea de Katuma

Diapositives de la presentació de l'Assemblea de Katuma del 30 de maig de 2018.

* [Diapositives en HTML](http://coopdevs.org/assemblea_katuma_30_05_2018/)

## Desenvolupament

Assegura't que tens el repositori
[slides_template](https://github.com/coopdevs/slides_template) clonat perquè la
[plantilla de la
presentació](https://github.com/coopdevs/assemblea_katuma_30_05_2018/blob/master/template) apunta a `../slides_template/template` amb un symlink.

### Exportar a HTML

Des de la branca `master` executeu:

```sh
$ bs export presentation.md
```

Un cop fet, canvieu a la branca `gh-pages` i moveu l'arxiu `dist/presentation.html` a `index.html`. Des d'aquesta mateixa branca commitejeu i publiqueu els canvis. Això generarà un nou build que estarà disponible a la URL de Github pages.


### Exportar a PDF

Des de la branca `master` executeu:

```sh
bs pdf presentation.md --verbose
```

Això us generarà un pdf a la carpeta `pdf/`. Comprimiu-lo (pot arribar a pesar molt) i penjeu-lo al [compte de Speakerdeck de Coopdevs](speakerdeck.com/coopdevs).
