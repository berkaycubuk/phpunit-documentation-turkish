# Çeviriler

Her bir çeviri kendisi için ayrılmış özel bir repoda saklanır ve yönetilir:

* [İngilizce Dokümentasyon](https://github.com/sebastianbergmann/phpunit-documentation-english)
* [İspanyolca Dokümentasyon](https://github.com/sebastianbergmann/phpunit-documentation-spanish)
* [Fransızca Dokümentasyon](https://github.com/sebastianbergmann/phpunit-documentation-french)
* [Brazilian Portuguese Dokümentasyon](https://github.com/sebastianbergmann/phpunit-documentation-brazilian-portuguese)
* [Japonca Dokümentasyon](https://github.com/sebastianbergmann/phpunit-documentation-japanese)
* [Basitleştirilmiş Çince Dokümentasyon](https://github.com/sebastianbergmann/phpunit-documentation-chinese)
* [Rusça Dokümentasyon](https://github.com/sebastianbergmann/phpunit-documentation-russian)

## Yeni çevirilerin eklenmesi

If you want to create a new translation, please open an issue in the issue
tracker of the English documentation, stating which language you would like to
translate. A repository will be created and added to the available translations.

Ideally, you would already have prepared a first version based on a fork or
a copy of the English documentation, which will then be imported into the 
official repository. 

# Dokümentasyonun Hazırlanması

## Gereksinimler

- Python
- [Sphinx](http://www.sphinx-doc.org/)
- [Read the Docs Sphinx Theme](https://github.com/rtfd/sphinx_rtd_theme)

## HTML Dokümentasyonun Hazırlanması

To build the complete documentation run:

```
$ make html
```

Afterwards you will find the HTML files in `build/html`.

## Proofreading Otomasyonu

### Kurulumu

```
$ pip install docutils-ast-writer
$ npm install
```

### Kullanımı

```
$ ./node_modules/.bin/textlint src
```

