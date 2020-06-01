# Santali-Translations
Translated Resource Files For Android Application and Android Os

What the Project is about ?

The project is to bring the Santali Language Support to the Android Devices and Android Application.
As I have a MIUI Device, the translation work will first begin for MIUI Device and later on for other devices. 
To be specific the files which will be translated comes from the MIUI11 ROM V11.0.3.0 for Redmi Note 5.

Who can edit and contribute ?

Anybody who know's the language from top to bottom, who speaks the language and oviously the language proffesionals.

How to Edit?

Translators just need to go to MIUI > app >   OR  MIUI > priv-app >  folders. After moving into the app folder or priv-app folder translators need to choose the application or folder they want to work with.After choosing the specific folder translators need to go ( res ) folder and then values-sat-rIN and open the following files... arrays.xml plurals.xml and strings.xml The work need to be done in these files. Sometimes only strings.xml file can only be found.

Where do you need to make the changes ?

Let's see an Example. Suppose Say I want to translate the map or clock application. I will go to the respective folder and edit the xml files.
The xml files look like this.
<?xml version="1.0" encoding="utf-8"?>
<resources>
<string name="AAA_CONFIRMATION_CONFIRM">Confirm..Translate the word Confirm like this ᱴᱷᱟᱹᱣᱠᱟᱹᱭ ᱢᱮ </string>
<string name="ACCESSIBILITY_ACTIVATE_KEYBOARD_BUTTON">ᱠᱤᱵᱳᱰ ᱪᱟᱹᱞᱩᱭ ᱢᱮ</string>
</resources>

In the 25th line the word Activate Keyboard was translated.

Some more examples On How to form Words or Sentences ?

Translating an English Word Flower, which in santhali is called baha b+a+h+a..looking the word baha we will write like this ᱵᱟᱦᱟ
Translating an English Word Ask   , which in santali is called kuli k+u+l+i ...How we write this? In spoken word or during speaking it's not just Ask (kuli). It's Ask Him so will write Ask as Ask Him which is ( k+u+l+i m ) Now in santali we write as ᱠᱩᱞᱤ ᱮᱢ
There are many English Words which do not have a santhali word Like Remote Screen Samsung ..etc..How we will write ? We will write remote as 
r+e+m+o+t+e ᱨᱤᱢᱚᱴ     Screen as S+c+r+e+e+n ᱤᱥᱠᱨᱤᱱ Samsung as S+a+m+u+n+g ᱥᱟᱢᱥᱩᱝ
  

Final Words

Where to look for translation resources or look for reference
Visit wesanthals.org or search online for English to Santali Dictionary or Hindi Santali Sabhdkos.
Please use only Unicode Font....The one which is used is Noto Sans Ol Chiki.** 
Looking Forward for your contributions.

Just An updated note that the main framework file has been translated upto 80%. 300 lines still need to be translated by me,they are from line no. 1400, and other 100 lines have been left out because they complicated for me and requires someone proffessional to translate them.From line no. 921
People can start focusing on translating the basic application like contact,weather,phone dialer,clock,calculator
