# HjaalQuizBot

## Eigenständige Befehle

> !botcheck
Um zu prüfen, ob der Bot aktiv ist.
Wenn ja, wird er dem Anwender antworten.

## Gefragt:

> !startgefragt [AnzahlAntworten]

Startet eine neue Runde "Gefragt" im Chat. 
Standardmäßig wird die Runde für 3 Antworten pro Person gestartet, alternativ kann die Anzahl der Antworten mit angegeben werden.

> !gefragt [Antwort(en)]

Mit diesem Befehl können Nutzer ihre Antworten einreichen.
Antworten können entweder einzeln oder mit Komma getrennt als Liste eingereicht werden.
Hat der Nutzer bereits die maximale Anzahl an Antworten eingereicht und reicht eine neue ein, wird die erste wieder gelöscht.

> !gefragtcheck

Zeigt dem Anwender eine Liste seiner eingreichten Antworten an.

> !endgefragt

Beendet die Runde "Gefragt" und gibt die meistgenannten Antworten des Chats aus.

## Einkaufsliste:

> !starteinkaufsliste

Startet eine neue Runde "Einkaufsliste" im Chat.

> !preis [Preis]

Mit diesem Befehl können Nutzer ihren geschätzten Gesamtpreis einreichen.
Akzeptiert werden ganzzahlige Preise sowie mit Komma oder Punkt als Trennzeichen.
Hat der Nutzer bereis einen Preis eingereicht, wird dieser überschrieben.

> !endeinkaufsliste

Beendet die Runde "Einkaufsliste" und gibt den Durchschnittlichen Preis aller genannten Antworten des Chats aus.
