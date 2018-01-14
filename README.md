# About

This Chrome extension adds an accent to mark the stress on words in Russian. Hovering over a words brings up a popover with its definition(s) from wiktionary.

The extension contains an index of all Russian words from the English wiktionary site with all their grammatical forms and accent position.

# How to build

```bash

pip3 install pipenv
cd scripts
pipenv install

./download-resources.sh
pipenv run python3 download-pages.py
pipenv run python3 parse-pages.py
pipenv run python3 build-indexes.py
./package-extension.sh

```bash

# License

This work is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

Icon originally by karthikeyan (https://openclipart.org/detail/owl-by-karthikeyan) [Public domain], via Wikimedia Commons (https://commons.wikimedia.org/wiki/File:Clipart_owl.png).