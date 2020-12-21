|                      | Functional Stability | Performance | Compatibility | Usability | Reliability | Security | Maintainability |	Portability |
| :---                  | :---:                  | :---:         | :---:           | :---:       | :---:         | :---:      | :---:             | :---:          |
| Functional Stability | /                    | <           | <             | <         | <           | <        | <               |  <           |
| Performance          |	^                   |	/	          | ^             |	^	        | ^           |	^        | ^               |	<           |
| Compatibility        |	^ |	< |	/ |	^ |	^ |	< | ^ |	< |
| Usability            |	^ |	< | < |	/ |	< |	< |	< |	< |
| Reliability          |	^ |	< |	< |	^ |	/ |	< |	^ |	< |
| Security             | ^ | < | ^ | ^ | ^ | / | ^ | < |
| Maintainability      |	^	| < |	< |	^ |	< |	< |	/ |	< |
| Portability          |	^	| ^ |	^ |	^ |	^ |	^ | ^ |	/ |


|Kriterium|Begründung|
|---|---|
|Functional Stability| da die Konkurrenten schon weit verbreitet sind, können wir uns keine Fehler bei den Kern-Funktionen erlauben|
|Usability| der Nutzer soll sich selbstständig, ohne große Anleitungen zurecht finden|
|Security| da wir mit Paypal als Zahlungsdienstleister zusammenarbeiten, sind bei uns keine Bezahlinformationen gespeichert. Allerdings sollen die Bewegungsdaten der Nutzer sicher aufbewahrt werden|
|Maintainability| um die erweiterten Funktionen, die wir geplant haben, in den nächsten Releases unkompliziert zu entwickeln, muss es möglich sein die App einfach auf den neusten Stand zu bringen|
|Reliability| der Nutzer sollte möglichst den korrekten Preis angezeigt bekommen, allerdings wäre ist verkraftbar, wenn der Preis um ein paar Minuten zu spät akualisiert wird|
|Compatibility| sobald die App für iOS und Android veröffentlicht wurde, wird erst in späteren Releases an einer Web-Anwendung gearbeitet, allerdings brauchen wir keine Applikation für Windows, Mac oder eine Chrome Extension|
|Performance| da die App sehr schlicht und "leicht" entwickelt wird, sollte sie auf allen aktuellen Geräten ohne Probleme laufen|
|Portability| ist zunächst vernachlässigbar, da die App auf den meisten gewünschten Geräten lauffähig ist, sobald sie für Android und iOS verfügbar ist|
