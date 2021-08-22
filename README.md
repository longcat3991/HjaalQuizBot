# HjaalQuizBot

### Inhaltsverzeichnis
[Eigenständige Befehle](#Eigenständige-befehle)

[Gefragt](#Gefragt)

[Einkaufsliste](#Einkaufsliste)

[Sonstige Spiele](#Sonstige-Spiele)

## Eigenständige Befehle

#### Für Zuschauer

* `!botcheck`

  * Um zu prüfen, ob der Bot aktiv ist.

  * Wenn ja, wird er dem Anwender antworten.

* `!teilnehmer`

  * Gibt eine Liste der Quizshow-Teilnehmer aus.

#### Für Mods

* `!setteilnehmer [Teilnehmer]`

  * Mod-Only. Passt den !teilnehmer Command an. Teilnehmer werden mit Komma getrennt erwartet.

  * Um den Command zu leeren, einfach !setteilnehmer ohne weiteren Text abschicken.



## Gefragt:

#### Für Zuschauer:

* `!gefragt [Antwort(en)]`

  * Wenn eine Runde "Gefragt" offen ist, kann man mit diesem Befehl seine Antworten einreichen.

  * Antworten können entweder einzeln oder mit Komma getrennt als Liste eingereicht werden.

  * Hat der Nutzer bereits die maximale Anzahl an Antworten eingereicht und reicht eine neue ein, wird die erste wieder gelöscht.

* `!gefragtcheck`

  * Zeigt dem Anwender eine Liste seiner eingereichten Antworten an.

#### Für Mods:

* `!startgefragt [AnzahlAntworten] (Optional)`

  * Mod-Only. Startet eine neue Runde "Gefragt" im Chat. 

  * Standardmäßig wird die Runde für 3 Antworten pro Person gestartet, alternativ kann die Anzahl der Antworten mit angegeben werden.

* `!endgefragt`

  * Mod-Only. Beendet die Runde "Gefragt" und gibt die meistgenannten Antworten des Chats aus.



## Einkaufsliste:

#### Für Zuschauer:

* `!preis [Preis]`

  * Wenn eine Runde "Einkaufsliste" offen ist, kann man mit diesem Befehl seinen geschätzten Gesamtpreis einreichen.

  * Akzeptiert werden ganzzahlige Preise sowie mit Komma oder Punkt als Trennzeichen.

  * Hat der Nutzer bereits einen Preis eingereicht, wird dieser überschrieben.

#### Für Mods:

* `!starteinkaufsliste`

  * Mod-Only. Startet eine neue Runde "Einkaufsliste" im Chat.

* `!endeinkaufsliste`

  * Mod-Only. Beendet die Runde "Einkaufsliste" und gibt den Durchschnittlichen Preis aller genannten Antworten des Chats aus.



## Sonstige Spiele:

#### Für Zuschauer:

* Bisher werden die anderen Spiele per Chat-Umfrage gespielt. Ihr müsst hier also keinen Befehl benutzen, sondern einfach in der Umfrage auf die richtige Antwort klicken.

#### Für Mods:

* `!pollresult [Nachricht]`

  * Mod-Only. Sendet eine Nachricht in Hjaal's "Antworten"-Discord-Channel.

  * Hiermit könnt ihr also die Umfrageergebnisse oder andere nützliche Informationen in den Channel schicken.
