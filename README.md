# Anki-Translator (Forked and updated to Anki 2.1.54+)

Works on config:
Anki 2.1.54 (b6a7760c) Python 3.9.7 Qt 6.3.1 PyQt 6.3.1
Platform: Mac 12.5.1
Flags: frz=True ao=True sv=2


Anki-Translator is a Add-On for the flashcard program [Anki](http://ankisrs.net/).

This Add-On translates vocabularies for you. So if you want to add a new flashcard to your deck you can open this Add-On 
and let it find translations for you from the web.

All the Translations come from [PONS](http://en.pons.com/).

### Available Languages (Not all combinations):
* Arabic
* Chinese
* Dutch
* English
* French
* German
* Greek
* Italian
* Latin
* Polish
* Portuguese
* Russian
* Slovenian
* Spanish
* Turkish
* Czech
* Danish
* Hungarian
* Norwegian
* Swedish
* Elvish

## Usage
![alt tag](https://raw.githubusercontent.com/jannewulf/Anki-Translator/master/docs/Button.png)

Just click this translate button in Anki's Editor. 

![alt tag](https://raw.githubusercontent.com/jannewulf/Anki-Translator/master/docs/translated-tree.png)

A new window opens where you choose the source and target languages and if you want grammar infos (like grammatical
gender, etc.).

After you entered the vocable and clicked on 'Translate' the translations get loaded. You mark the checkboxes of the 
translations you want to have on your flashcard and leave the window with a click on 'OK'.

The chosen translations get copied on your flashcard.

## Default Values
You can change the default values for source and target language and also for the grammar infos. Just change the values 
of the variables in the file '__init__.py'. You can find the file in the Add-Ons Folder of your Anki Installation.

![alt tag](https://raw.githubusercontent.com/jannewulf/Anki-Translator/master/docs/settings.png)

(See the highlighted lines.)

## Installation

Download this project as a zip and uncompress the folder into your Anki Addon folder (../addons21/Anki-Translator-master).
