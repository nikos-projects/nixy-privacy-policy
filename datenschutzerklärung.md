# Nixy Datenschutzerklärung

**Stand:** 16. August 2026

## Zustimmungserklärung

Durch die Nutzung von Nixy auf einem Discord-Server erkennst du die in dieser Datenschutzerklärung beschriebenen Bedingungen an und stimmst ihnen zu. Wenn du mit Teilen dieser Erklärung nicht einverstanden bist, musst du die Nutzung des Bots einstellen und kannst die sofortige Löschung deiner Daten über den in Abschnitt 4 genannten Befehl anfordern.

**Für Server-Administrator**innen:** Indem du Nixy auf deinen Server einlädst und den Nutzungsbedingungen von Discord zustimmst, stimmst du dieser Datenschutzerklärung auch im Namen deiner Server-Mitglieder zu. Es liegt in deiner Verantwortung, deine Community über die Datenverarbeitungspraktiken von Nixy zu informieren (einschließlich, aber nicht beschränkt auf Server-Snapshots, Nachrichten-Logging und KI-Moderation). Wenn deine Serverregeln auf diese Erklärung verweisen, sind Mitglieder, die diesen Regeln zustimmen, an deren Bedingungen gebunden.

---

## Inhaltsverzeichnis
1. [Erhebung von Daten](#1-erhebung-von-daten)
2. [Verwendung deiner Daten](#2-verwendung-deiner-daten)
3. [Datenspeicherung und Löschung](#3-datenspeicherung-und-löschung)
4. [Nutzerrechte (Löschung deiner Daten)](#4-nutzerrechte-löschung-deiner-daten)
5. [Minderjährige Nutzer](#5-minderjährige-nutzer)
6. [Kontaktinformationen](#6-kontaktinformationen)

---

## 1. Erhebung von Daten

Wir erheben spezifische Nutzer- und Serverdaten über die folgenden Kernfunktionen:

- **Server-Snapshots:** Nixy erstellt automatisch Snapshots des Discord-Servers (einschließlich Kanal-Layouts und Emojis) zusammen mit den letzten 20 Nachrichten jedes Kanals. Dies umfasst die Speicherung deines Discord-Anzeigenamens, deines Profilbildes und deiner Nachrichteninhalte. Gemäß DSGVO erfolgt dies auf Grundlage unseres **berechtigten Interesses**. Du kannst deine eigenen Daten jederzeit aus diesen Snapshots entfernen lassen, indem du den in dieser Erklärung angegebenen Löschbefehl ausführst.
- **Server-Logging:** Wir verfolgen Server-Ereignisse über die Discord-API, um Moderations-Logs bereitzustellen. Dies beinhaltet die Verarbeitung von Nachrichteninhalten (zur Protokollierung bearbeiteter oder gelöschter Nachrichten), Namensänderungen, Profilbild-Updates und anderen Standard-Ereignissen auf dem Server. Diese Logs können aus dem Log-Kanal gelöscht werden, verbleiben jedoch im offiziellen Audit-Log von Discord, wenn du den Löschbefehl ausführst.
- **KI-Feature-Moderation:** Bei der Interaktion mit den KI-Funktionen über Discord-Direktnachrichten (DMs) erheben wir deinen Nachrichteninhalt und deine Discord-User-ID.

**Daten-Gerichtsstand:** Alle Daten werden auf Servern gespeichert, die sich physisch in **Deutschland** befinden. Die Daten verlassen zu keinem Zeitpunkt der Verarbeitung oder Speicherung den deutschen bzw. EU-Rechtsraum. Durch die Abschaltung der DeepSeek-API-Integration wird dies zusätzlich sichergestellt.

---

## 2. Verwendung deiner Daten

- **Server-Snapshots:** Werden ausschließlich verwendet, um den Zustand, die Struktur und den aktuellen Kontext eines Servers im Falle eines "Raids" oder einer böswilligen Zerstörung wiederherzustellen.
- **Server-Logging:** Wird verwendet, um Echtzeit-Änderungen am Server, seinen Kanälen, Nachrichten und Nutzern in dafür vorgesehenen administrativen Log-Kanälen anzuzeigen.
- **KI-Feature-Moderation:** Wird verwendet, um Unterhaltungen automatisch auf illegale oder hochgradig unangemessene Inhalte zu überprüfen. Diese automatische Überprüfung stellt die Einhaltung von Sicherheitsrichtlinien sicher. Nutzer, die gegen diese Regeln verstoßen, können automatisch von der Nutzung der KI-Funktionen ausgeschlossen werden.
- **Polizeiberichte / Strafverfolgung:** Wenn illegale Inhalte festgestellt werden, können Server-Snapshots als Beweismittel herangezogen werden. Nutzer, die nicht mit diesen Beweisen in Zusammenhang stehen, werden aus dem extrahierten Snapshot entfernt, um deren Privatsphäre zu wahren. Die Beweissicherung auf diese Weise ist ein letztes Mittel. Bitte nutze diesen Bot nicht für illegale Aktivitäten wie das Verbreiten von Falschinformationen über Entwickler ("Üble Nachrede") oder das Belästigen von Discord-Nutzer*innen.

**Rechtsgrundlage der Verarbeitung:** Wir verarbeiten deine Daten auf Grundlage von **Berechtigtem Interesse** (Server-Wiederherstellung, Moderation und Durchsetzung der Sicherheit) sowie **Einwilligung** (wenn du freiwillig KI-Funktionen über Discord-DMs nutzt). Du kannst deine Einwilligung jederzeit durch die Nutzung des in Abschnitt 4 beschriebenen Löschbefehls widerrufen.

**Verarbeitung durch Dritte:** Nixy nutzt **keine** externen KI-Anbieter, Cloud-Speicher oder Analysedienste. Alle Datenverarbeitungen, Speicherungen und KI-Inferenzen finden vollständig auf unserer eigenen privaten Infrastruktur in Deutschland statt. Es werden niemals Nutzerdaten an Dritte verkauft, weitergegeben oder übermittelt.

---

## 3. Datenspeicherung und Löschung

- **Server-Snapshots:** Snapshots werden automatisch jede Stunde erstellt. Wir führen eine strikte fortlaufende Historie der letzten 50 Snapshots. Folglich werden Daten innerhalb eines spezifischen Snapshots nach ca. 50 Stunden dauerhaft überschrieben und gelöscht. Im Falle einer beantragten Löschung werden die Inhalte des Nutzers, der die Löschung anfordert, sofort aus diesen Snapshots entfernt. Der gesamte Snapshot wird jedoch nicht gelöscht, um zu verhindern, dass "Raider" die letzte Wiederherstellungsmöglichkeit von Server-Besitzern löschen.
- **Server-Logging:** Protokollierte Daten werden unbegrenzt gespeichert, um die Server-Historie für Administrator*innen aufrechtzuerhalten. Nutzer können jedoch eine*n Server-Moderator*in bitten, spezifische Log-Einträge manuell aus den Log-Kanälen zu löschen. Logs werden auch automatisch entfernt, wenn der Datenlöschbefehl ausgeführt wird. Du kannst zusätzlich beim Entwickler die manuelle Löschung deiner geloggten Daten anfordern. Bitte beachte, dass die geloggten Daten im offiziellen Audit-Log von Discord verbleiben.

---

## 4. Nutzerrechte (Löschung deiner Daten)

Wir bieten einen einzigen, einheitlichen Befehl, der eine vollständige und automatisierte DSGVO-konforme Löschung auslöst. Dieser Befehl lautet `$gdprdelete` (`$` ist ein Beispiel-Präfix, bitte beachte die unten aufgeführten Präfixe für alle funktionierenden Präfixe). Ähnliche Varianten findest du über `$help`. Du kannst jedes vom Bot unterstützte Präfix verwenden.

Die Ausführung dieses Befehls löscht deine Daten sofort und dauerhaft aus internen und externen Datensätzen, entfernt alle Nachrichten, in denen der Bot deine Daten gesendet hat, und entfernt ("kickt") dich automatisch vom aktiven Server, um ein weiteres Tracking zu verhindern. Du kannst den entsprechenden Servern wieder beitreten; unter diesen Umständen kann Nixy einige der oben aufgeführten Daten erneut unter berechtigtem Interesse erheben. Dieser Befehl löscht auch Logs, die an den dafür vorgesehenen Log-Kanal gesendet wurden.

Da sich Befehlsnamen oder Präfixe im Laufe der Zeit ändern können, sollten Nutzer die aktuelle Befehlsliste überprüfen, indem sie `help` mit einem beliebigen gültigen Bot-Präfix eingeben (einschließlich, aber nicht beschränkt auf: `&`, `=`, `$`, `;`, `:`, `?`, `!`, `.`) und nach der Befehlsbeschreibung bezüglich Datenlöschung suchen. Dies gilt nur, falls der obige Befehl nicht funktioniert. Bitte stelle sicher, dass Nixy online ist, falls der Befehl nicht reagiert.

**Widerruf der Einwilligung:** Durch die Nutzung des Löschbefehls widerrufst du formell deine Einwilligung zur Verarbeitung deiner Daten durch Nixy. Nach der Ausführung werden alle zugehörigen Daten dauerhaft entfernt und es findet keine weitere Verarbeitung statt.

---

## 5. Minderjährige Nutzer

Nixy erhebt, verarbeitet oder speichert nicht wissentlich Daten von Personen unter 13 Jahren (bzw. unter 16 Jahren im Europäischen Wirtschaftsraum). Wenn Sie als Erziehungsberechtigte*r glauben, dass Ihr Kind Nixy genutzt hat, kontaktieren Sie uns bitte umgehend über die Angaben in Abschnitt 6. Wir werden alle zugehörigen Daten unverzüglich löschen.

---

## 6. Kontaktinformationen

Bei Fragen zu dieser Datenschutzerklärung oder wenn du manuelle Unterstützung bezüglich deiner Daten benötigst, kannst du den Entwickler direkt über Discord unter `niko_3992` oder per E-Mail unter [taubert.philipp2@gmail.com](mailto:taubert.philipp2@gmail.com) kontaktieren.

*Hinweis zu diesen Kontaktinformationen:* Ich wurde in letzter Zeit belästigt, weil diese Datenschutzerklärung einige Dinge nicht im Detail klargestellt hatte, was zu Missverständnissen über die Datenerhebung des Bots führte. Ich bitte jedoch darum, von weiteren Belästigungen abzusehen. Es macht niemandem Spaß, und ich bin immer noch minderjährig.
