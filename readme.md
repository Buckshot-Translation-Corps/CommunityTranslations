Create a fork of this repository, the GitHub actions will create a copy of `EN.csv`
<br/>
called `EDIT_ME.csv` for you to work on.
<br/>

Replace the `en` at the top with the [locale code](https://docs.godotengine.org/en/latest/tutorials/i18n/locales.html) for your translation and replace
<br/>
the line `ENGLISH, ENGLISH` with your language's name in English in the right
<br/>
column and the localised name in the left column.
<br/>
_e.g._
* `ITALIAN,ITALIANO`
* _or_
* `TURKISH,TÜRKÇE`
* _etc..._

The second column contains the sentences for you to translate.

While editing the text, remember that any line containing `%s` will have that symbol
<br/>
replaced with other text, such as the player's name, shell count, _etc..._

When you're finished, move your translation's CSV file into the `/translations/`
<br/>
folder and submit a pull request.