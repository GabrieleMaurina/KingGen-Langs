# KingGen-Langs
Translations for the KingGen software for 7 Days to Die

## What it is
This repo contains text files that are used by KingGen to translate its GUI into different languages to help players who do not speak English. We are currently looking for volunteers to help with the translations.

## Contributions
If you can speak a language other than English and you would like to see KingGen translated into your language, than your help is welcome!
You are going to need:
* A [git](https://git-scm.com/) client
* A text editor
* Good knowledge of English
* Good knowledge of a language other than English

## Steps
These are the steps to take to submit a new translation:
* [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo
* [Clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) your forked repo
* Create a new [branch](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches) with the name of the language you are intending to translate. The name must be in English and must be lowercase (e.g. russian, german, italian, spanish...)
* Switch to the newly created branch
* Copy the file en_us.txt and rename it to match the locale of the language you want to translate into (e.g. ru_ru.txt, de_de.txt, it_it.txt, es_es.txt...). The file name must be lowercase
* Edit your newly created file. Replace the English part to right of the character "=" with your translation. Do not change the structure of the file!
* Save
* [Commit](https://github.com/git-guides/git-commit) and [push](https://github.com/git-guides/git-push)
* Create a [pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
* Wait for the request to be checked and approved

Once a translation is approved, it will appear in the next release of KingGen.

You can also submit a pull request for an existing translation if you want to improve it, or fix it, or add missing parts. In that case you don't need to create a new branch, but use the existing branch of the language.

## Rules
These rules must be followed when creating a translation.
* Do not change the file structure (do not add lines, do not change the lines order)
* Edit ONLY the text to the right of the character "=". The part to the left is used by KingGen to identify the string and must be left untouched
* Translate accurately (find the translation most similar in meaning to the English version)
* Do not add words or text that is not explicity stated in the English version. (Do not change the meaning, do not add meaning)
* Respect the puctuation. Leave periods, commas and spaces where they are
* Respect the capitalization
* Do not translate words such as "POI" and "KingGen"
* Be consistent, translate the same word always in the same way
* Use clear language
* Do not use slang
* Do not use swear words or offensive language (all translations will be double checked)

## Can't use git?
If you can't use git and you would like to contribute, you can still help! Create the translation file (respecting all the editing rules) and get in touch either here or on the forum page. Your translation will be added by an admin.
