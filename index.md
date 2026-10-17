---
title: Scuba Siege – Datenschutz / Privacy
---

# Scuba Siege – Datenschutz / Privacy

## Deutsch

**Stand:** 2026-10-16 · Diese Erklärung gilt für das Spiel „Scuba Siege“ (Benjo Games).

### Wer ist verantwortlich?

Benjamin Bayer, Im Wöhrlet 20, 91227 Leinburg, E-Mail: <code.benjo@gmail.com>

### Welche Daten verarbeitet das Spiel?

- **Konto.** Zum Spielen meldest du dich einmal mit einem Konto an. Die Anmeldung läuft über **Unity Player Accounts** (Unity Technologies): Du gibst deine Zugangsdaten (E-Mail und Passwort, oder Google bzw. Apple) auf der Anmeldeseite von Unity im Browser ein, nicht im Spiel. Das Spiel erhält von Unity eine Spieler-ID und ein Sitzungstoken. Dein Passwort sieht das Spiel nie.
- **Auf deinem Rechner.** Das Spiel speichert die Spieler-ID und den Zeitpunkt der letzten Online-Anmeldung in der Datei `account.json` im Datenordner des Spiels, damit es nach der ersten Anmeldung auch ohne Internet startet. Dazu kommen deine Einstellungen und Bestleistungen (`save.json`) und eine Fehlerdatei (`errors.log`). Die Fehlerdatei liegt nur auf deinem Rechner und wird nicht übertragen. Lautstärken und Bestleistungen aus `save.json` gleicht das Spiel mit Cloud Save ab (siehe nächster Punkt); die übrigen Einstellungen bleiben auf deinem Rechner. Die Anmeldesoftware von Unity legt außerdem selbst ein Sitzungstoken auf deinem Rechner ab, damit du angemeldet bleibst; „Sign out“ im Spiel entfernt es.
- **Cloud Save.** Solange du angemeldet bist, legt das Spiel deine **Lautstärken** (Master, Musik, Effekte) und deine **Bestleistungen** (je Karte: erreichte Wellen, verbleibende Hülle) in deinem Konto bei **Unity Cloud Save** (Unity Technologies) ab und gleicht sie bei jedem Start mit deinem Rechner ab, damit sie auf jedem Rechner gelten. Auflösung, Vollbild und VSync bleiben nur auf deinem Rechner. Wechselt auf einem Rechner das Konto, fragt das Spiel, ob die lokalen Bestleistungen in das neue Konto übernommen oder verworfen werden; beim Verwerfen bleibt eine Kopie der alten Datei (`save.json.previous-account`) im Datenordner liegen.
- **Spielername.** Für Bestenlisten und Freunde hat jeder Spieler einen Spielernamen der Form `Name#1234`. Ihn vergibt Unity (Authentication) automatisch; das Spiel übernimmt keine E-Mail-Adresse und keinen Klarnamen aus deiner Anmeldung als Namen. Du kannst den Namen im Spiel ändern (Hauptmenü → Friends → „Change name“). Der Spielername ist für andere Spieler sichtbar; wähle keinen Namen, der dich identifiziert, wenn du das nicht möchtest.
- **Bestenlisten.** Verbessert ein Lauf deine Bestleistung einer Schwierigkeitsstufe, sendet das Spiel das Ergebnis (Schwierigkeitsstufe, erreichte Wellen, verbleibende Hülle und der Zeitpunkt der Meldung) zusammen mit deinem Spielernamen und deiner Spieler-ID an die Bestenliste dieser Stufe bei **Unity Leaderboards** (Unity Technologies). Die Bestenlisten sind **öffentlich**: Jeder Spieler des Spiels kann deinen Spielernamen und dein Ergebnis dort sehen. Ergebnisse, die sich nicht senden ließen (zum Beispiel ohne Internet), merkt sich das Spiel in `save.json` und sendet sie später; bei der ersten Anmeldung sendet es auch deine schon vorhandenen Bestleistungen. Mit dem Schalter „Show my scores“ (Hauptmenü → Leaderboards, „Show my scores: On/Off“) kannst du dich jederzeit ausblenden: Bei „Off“ sendet das Spiel nichts mehr und löscht deine Bestenlisten-Einträge; lässt sich das gerade nicht erledigen (zum Beispiel ohne Internetverbindung), bleiben die Einträge sichtbar, bis das Spiel sie löschen kann, sobald du wieder online und angemeldet bist; bei „On“ sendet es deine lokalen Bestleistungen wieder.
- **Keine Fälschungssicherheit.** Das Spiel sendet die Ergebnisse selbst und prüft vorher nur, ob die Werte plausibel sind. Die Ergebnisse werden nicht serverseitig geprüft und können gefälscht sein; ein Platz in der Bestenliste ist deshalb kein Beweis für ein tatsächlich gespieltes Ergebnis.
- **Freunde und Anwesenheit.** Unter Hauptmenü → Friends kannst du anderen Spielern anhand ihres vollen Spielernamens (`Name#1234`) eine Freundschaftsanfrage senden, Anfragen annehmen oder ablehnen und Freunde entfernen. Freundesliste, offene Anfragen und deine Anwesenheit verarbeitet **Unity Friends** (Unity Technologies). Deine Freunde sehen deine Anwesenheit („Online“ im Hauptmenü, „In game“ in einem Lauf, sonst offline); eine Anfrage zeigt dem Empfänger deinen Spielernamen.
- **Bei Unity.** Unity verarbeitet Konto, Anmeldung, Cloud Save, Bestenlisten, Freundesliste und Anwesenheit nach eigener Datenschutzerklärung (<https://unity.com/legal/privacy-policy>). Dabei können technische Daten wie IP-Adresse und Gerätekennung anfallen. Unity kann Daten auch außerhalb der EU verarbeiten (zum Beispiel in den USA); Näheres steht in Unitys Erklärung. Das Löschen von Bestenlisten-Einträgen läuft über ein Skript bei **Unity Cloud Code**, weil Unity dafür keine Funktion im Spiel selbst anbietet.
- Das Spiel selbst enthält **keine Werbung, keine Analyse und keine Weitergabe** deiner Daten an Dritte außer an Unity für die Anmeldung, für Cloud Save, für Bestenlisten und für Freunde. Was in den öffentlichen Bestenlisten steht, sehen alle Spieler (siehe oben).

### Wozu und auf welcher Grundlage?

Die Daten werden verarbeitet, um dir das Spiel mit Konto, Bestenlisten und Freunden bereitzustellen (Art. 6 Abs. 1 lit. b DSGVO).

### Wie lange werden sie gespeichert?

Solange dein Konto besteht. Bestenlisten-Einträge lassen sich vorher mit „Show my scores: Off“ löschen, Freunde mit „Remove“ entfernen. Lokale Dateien liegen, bis du sie löschst oder das Spiel deinstallierst.

### Deine Rechte und das Löschen deines Kontos

Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit und Widerspruch sowie auf Beschwerde bei einer Datenschutzaufsichtsbehörde.

- **Im Spiel:** Hauptmenü → Einstellungen → „Delete account“ (zweimal drücken). Das löscht zuerst deine Bestenlisten-Einträge (über das Skript bei Unity Cloud Code) und deine Freundesliste samt offenen Anfragen, dann deine Daten in Cloud Save, dann deinen Spieler bei Unity, und öffnet die Seite <https://player-account.unity.com/delete-account>, auf der du auch dein Unity-Konto löschst. Lassen sich diese Daten nicht löschen (zum Beispiel ohne Internet), wird das Konto nicht gelöscht; du kannst es später erneut versuchen. Die lokale Datei `save.json` bleibt auf deinem Rechner liegen, bis du sie löschst.
- **Auskunft und Löschung bei Unity:** <unity-player-login-privacy@unity3d.com>
- **Bei uns:** <code.benjo@gmail.com>

### Änderungen

Wir passen diese Erklärung an, wenn sich das Spiel ändert (etwa mit Mehrspieler). Die jeweils gültige Fassung steht auf dieser Seite.

## English

**Version:** 2026-10-16 · This policy applies to the game "Scuba Siege" (Benjo Games).

### Who is responsible?

Benjamin Bayer, Im Wöhrlet 20, 91227 Leinburg, e-mail: <code.benjo@gmail.com>

### What data does the game process?

- **Account.** To play you sign in once with an account. Signing in runs through **Unity Player Accounts** (Unity Technologies): you enter your credentials (e-mail and password, or Google or Apple) on Unity's sign-in page in the browser, not in the game. The game receives a player ID and a session token from Unity. The game never sees your password.
- **On your computer.** The game stores the player ID and the time of the last online sign-in in the file `account.json` in the game's data folder, so that it starts without internet after the first sign-in. In addition there are your settings and best results (`save.json`) and an error file (`errors.log`). The error file stays on your computer and is not transmitted. The game compares the volumes and best results from `save.json` with Cloud Save (see the next point); your other settings stay on your computer. Unity's sign-in software also keeps a session token of its own on your computer so that you stay signed in; "Sign out" in the game removes it.
- **Cloud Save.** While you are signed in, the game stores your **volumes** (master, music, effects) and your **best results** (per map: waves reached, hull left) in your account with **Unity Cloud Save** (Unity Technologies) and compares them with your computer at every start, so that they apply on every computer. Resolution, fullscreen and VSync stay on your computer only. If another account signs in on a computer, the game asks whether the local best results are merged into the new account or discarded; discarding keeps a copy of the old file (`save.json.previous-account`) in the data folder.
- **Player name.** For leaderboards and friends every player has a player name of the form `Name#1234`. Unity (Authentication) assigns it automatically; the game does not take an e-mail address or a real name from your sign-in as the name. You can change the name in the game (main menu → Friends → "Change name"). The player name is visible to other players; if you do not want to be identifiable, do not choose a name that identifies you.
- **Leaderboards.** When a run improves your best result for a difficulty, the game sends the result (difficulty, waves reached, hull left and the time of the submission) together with your player name and player ID to the leaderboard of that difficulty at **Unity Leaderboards** (Unity Technologies). The leaderboards are **public**: every player of the game can see your player name and your result there. Results that could not be sent (for example without internet) are kept in `save.json` and sent later; at the first sign-in the game also sends your existing best results. With the switch "Show my scores" (main menu → Leaderboards, "Show my scores: On/Off") you can hide yourself at any time: with "Off" the game stops sending and deletes your leaderboard entries; if deleting is not possible at the moment (for example without an internet connection), the entries stay visible until the game can remove them once you are online and signed in again; with "On" it sends your local best results again.
- **No protection against forged results.** The game sends the results itself and only checks beforehand that the values are plausible. Results are not verified on a server and may be forged; a place on a leaderboard is therefore no proof of a result that was actually played.
- **Friends and presence.** Under main menu → Friends you can send a friend request to other players by their full player name (`Name#1234`), accept or decline requests and remove friends. The friends list, open requests and your presence are processed by **Unity Friends** (Unity Technologies). Your friends see your presence ("Online" in the main menu, "In game" during a run, otherwise offline); a request shows your player name to the recipient.
- **At Unity.** Unity processes the account, sign-in, Cloud Save, leaderboards, friends list and presence under its own privacy policy (<https://unity.com/legal/privacy-policy>). Technical data such as the IP address and a device identifier can occur. Unity may also process data outside the EU (for example in the USA); see Unity's policy for details. Deleting leaderboard entries runs through a script at **Unity Cloud Code**, because Unity offers no function for it in the game itself.
- The game itself contains **no advertising, no analytics and no disclosure** of your data to third parties except to Unity for signing in, for Cloud Save, for leaderboards and for friends. What is on the public leaderboards is visible to all players (see above).

### Why and on what basis?

The data is processed to provide you with the game with an account, leaderboards and friends (Art. 6(1)(b) GDPR).

### How long is it stored?

For as long as your account exists. You can delete leaderboard entries earlier with "Show my scores: Off" and remove friends with "Remove". Local files stay until you delete them or uninstall the game.

### Your rights and deleting your account

You have the right of access, rectification, erasure, restriction of processing, data portability and objection, and the right to lodge a complaint with a data protection supervisory authority.

- **In the game:** main menu → Settings → "Delete account" (press twice). This first deletes your leaderboard entries (through the script at Unity Cloud Code) and your friends list including open requests, then your data in Cloud Save, then your player at Unity, and opens <https://player-account.unity.com/delete-account>, where you also delete your Unity account. If this data cannot be deleted (for example without internet), the account is not deleted; you can try again later. The local file `save.json` stays on your computer until you delete it.
- **Access and deletion at Unity:** <unity-player-login-privacy@unity3d.com>
- **With us:** <code.benjo@gmail.com>

### Changes

We update this policy when the game changes (for example with multiplayer). The current version is always on this page.
