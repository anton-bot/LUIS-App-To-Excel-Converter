# LUIS-App-To-Excel-Converter
Converts an exported LUIS app in JSON format into an Excel (CSV) containing the intents and utterances.

##LUIS app to HTML converter

This small script converts the utterances from your LUIS app (exported as JSON from LUIS.ai) into an Excel table containing your intents and phrases.

This is useful if you want to train the bot in another language (meaning a separate LUIS app) using the same phrases as you used before.

##How to use

- Go to LUIS.ai an on main page, click Export App.

- Open the downloaded .json file in Notepad

- Copy the whole text and paste it into the box below

- Click Download to download the Excel file containing the utterances

#License and Usage

MIT license. 

Uses on HTML to CSV converter from https://github.com/rubo77/table2CSV. 
