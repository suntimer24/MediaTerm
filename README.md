Dies ist die Version MediaTerm 14.0. 
Die letzte die Martin veröffentlicht hat und die letzte die vor der Abschaltung seiner Website im April 2025 zum Download freigegeben wurde. 
Man findet die gesamte Website samt Skript auch noch im Webarchiv:
https://web.archive.org/web/20240930223043/https://martikel.bplaced.net/skripte1/mediaterm.html

Das Repo hier dient ebenfalls nur der Archivierung. 
Wenn sich ein neuer Entwickler oder mehrere neue Entwickler für das Skript finden würde mich das sehr freuen!

--

# MediaTerm
Mit dem Bash-Skript MediaTerm lassen sich Filme aus den Mediatheken der öffentlich-rechtlichen Fernsehsender ressourcenschonend im Linux-Terminal suchen, abspielen, herunterladen und als Bookmarks speichern.

Für das Abspielen der Filme wird standardmäßig der Medienplayer mpv eingesetzt, der aus den Paketquellen der gängigen Linux-Distributionen installiert werden kann. Vorausgesetzt werden außerdem wget, ffmpeg und xz bzw. xz-utils; zusätzlich empfohlen wird yt-dlp.

Bei der ersten Suchanfrage mit MediaTerm erfolgt (nach Bestätigung durch den Benutzer) automatisch ein Download der Filmliste (Filmliste-akt.xz) von MediathekView,
 die im – ebenfalls automatisch vom Skript angelegten – Verzeichnis 
$HOME/MediaTerm entpackt und aufbereitet wird. Später lässt sich die 
Filmliste jederzeit unter Verwendung der Option "-u" aktualisieren.

Ein Überblick über alle Funktionen von MediaTerm einschließlich Anwendungsbeispielen wird mit mediaterm -h aufgerufen.

