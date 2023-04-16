# chatgpt-playground
Ein kleiner Wrapper, um über die API mit OpenAI GPT chatten zu können. 

## Was man braucht
- Ein Google-Konto (um das Notebook in Colab auszuführen); ersatzweise eine lokale juPyter-Installation
- Ein gültiges Token für die OpenAI-API

## Wie man es nutzt
- Das [Notebook](./chatgpt_fuer_alle.ipynb) in Colab öffnen
- Das kleine "Play"-Dreieck bei der ersten Code-Zelle anklicken - die Vorbereitungen werden ausgeführt
- Das kleine "Play"-Dreieck bei der nächsten Code-Zelle anklicken - und die Fragen an den Bot ins "Du: "-Eingabefeld tippen und mit Return abschicken.

## Bekannte Probleme
- Anders als chatGPT formatiert das Skript die Ausgaben (noch) nicht sehr schön. Das wird am deutlichsten bei Gedichten oder bei Programmiercode.
- Manchmal verschluckt das Eingabefeld die letzten ein, zwei Zeichen - dann ein Momentchen warten, bis man Return drückt. 
