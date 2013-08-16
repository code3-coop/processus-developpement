Règles de style
===============

Les règles de style et de nomenclature pour nos projets de développement.

Ces règles de style s'appliquent à tous nos projets de développement de
logiciels, sauf si une exigence du client stipule le contraire.

Définitions
-----------

PascalCase : Aucun espacement entre les mots d'un identifiant et chaque mot
commence par une lettre majuscule. Par exemple : Membre, ServiceExterne,
NumeroDeFacture.

camelCase : Aucun espacement entre les mots d'un identifiant et chaque mot
commence par une lettre majuscule à l'exception du premier mot. Dans ce
document, lorsque nous faisons référence au camelCase, on sous-entend
lowerCamelCase. Il est inutile de spécifier la casse du premier mot car nous
utilisons le terme PascalCase pour identifier le upperCamelCase. Par exemple :
membre, serviceExterne, numeroDeFacture.

snake_case : Le caractère underscore '_' pour séparer les mots, toutes les
lettres en minuscule. Aussi connu sous le nom de underscore_case. Par exemple :
membre, service_externe, numero_de_facture.

hyphen-separated-case : Le caractère hyphen '-' pour séparer les mots, toutes les
lettres en minuscule. Par exemple : membre, service-externe, numero-de-facture.

Règles de nomenclature par technologie
--------------------------------------

### HTML, Jade

* Les noms des éléments et attributs sont en minuscules.
* Les noms de classes et les valeurs des attributs id sont en
  hyphen-separated-case.

### CSS, Stylus

* Les noms de classes sont en hyphen-separated-case.
* Les valeurs des propriétés sont en minuscules.

### Java, Groovy

* http://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html

### JSON (API REST public)

* Les noms des propriétés sont en snake_case.

### Javascript, CoffeeScript

* Les noms de variables et de fonctions sont en camelCase.
* Les noms de classes sont en PascalCase.
* Les documents JSON sont soumis aux mêmes règles que le Javascript (sauf les
  documents JSON d'un API REST public).
* Les objects stockés dans MongoDB sont soumis aux mêmes règles que le
  Javascript.

### SQL

* Les noms de table et noms de colonne sont en snake_case.
