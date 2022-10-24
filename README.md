[//]: # (Created by vitusb in 20220920)
[//]: # (Get emojis from here: https://github.com/markdown-templates/markdown-emojis)

# News

### 20221023 (Release-Update Gpg4Win 3.1.25) :smiley: :tada:

- (de):
Diese Version entspricht im Original dem Release "Gpg4Win" 3.1.25 mit einem zusätzlichen IMAP-Patch für GpgOL 2.5.4 (2.5.5), der gegenwärtig im Original von "Gpg4Win" / "GnuPG VS Desktop" der Version 3.1.25 nicht enthalten ist. Dieses Paket befindet sich gegenwärtig im Test und wird in den nächsten Stunden hier verfügbar sein. Alle Änderungen entsprechen ausser dem IMAP-Patch, dem Original-Quellcode. Somit sind die [Release-Informationen](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=blob;f=NEWS;hb=refs/tags/gpg4win-3.1.25) identisch. Der IMAP-Patch ist übrigens in der Version 4.0.4 schon enthalten, da hier "GpgOL 2.5.5" verwendet wird und dies der einzige Unterschied zu "GpgOL 2.5.4" ist.

- (en):
The original version of this version corresponds to the "Gpg4Win" 3.1.25 release with an additional IMAP-patch for GpgOL 2.5.4 (2.5.5), which is currently not available in the original "Gpg4Win"- / "GnuPG VS Desktop"-version 3.1.25. This package is currently in testing and will be available here in the next few hours. Except for the IMAP patch, all changes correspond to the original source code. Thus, the [Release-Notes](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=blob;f=NEWS;hb=refs/tags/gpg4win-3.1.25) are identical. By the way, the IMAP-patch is already included in version 4.0.4, since "GpgOL 2.5.5" is used here and this is the only difference to "GpgOL 2.5.4".

### 20220922 (Bugfix-Release Gpg4Win 3.1.24):

- (de): Fehlerbehebung von GpgOL (Patch dem Build-System hinzugefügt)
<br>&nbsp;&nbsp;GpgOL IMAP-Fehlerbehebung (:pray:):
<br>&nbsp;&nbsp;- Dies behebt den Fall, dass Nachrichten-Kopfzeilen in einer leeren Zeile enden.
<br>&nbsp;&nbsp;- Dies führt bei einer Transition in den E-Mail-Body zu einem Rückgabewert von 42.
<br>&nbsp;&nbsp;- Die Symptome sind Parser-Fehler im Protokoll von GpgOL und ein leerer E-Mail Inhalt mit 2 Attachements.

- (en): Bugfix-Release Update of GpgOL (patch added to build-system)
<br>&nbsp;&nbsp;GpgOL IMAP-Error-Fix (:pray:):
<br>&nbsp;&nbsp;- This fixes the case where the message headers end in an empty line.
<br>&nbsp;&nbsp;- This results in a transition to body with return code 42.
<br>&nbsp;&nbsp;- The symptoms are parser errors in the GpgOL log and an empty email content with 2 attachments.

### 20220914 (Release Gpg4Win 3.1.24):
- (de): Gpg4Win 3.1.24 veröffentlicht :smiley: :tada:
- (en): Gpg4Win 3.1.24 released :smiley: :tada:

# Gpg4Win

(de): [Installer-Builds](https://github.com/landsh-de/Gpg4Win/releases) der "Gpg4Win" [Git-Releases](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=tags)
<br>
(en): [Installer-Builds](https://github.com/landsh-de/Gpg4Win/releases) of the "Gpg4Win" [Git-Releases](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=tags)

<br>
<p align="center">
  <img src="https://user-images.githubusercontent.com/83558069/190190072-1553613a-dc1a-4089-8fbd-1b5963426663.jpg" />
</p>


### (de)

#### Der Release-Quellcode dieser Version von "Gpg4Win" entspricht (abgesehen von Anpassungen zum Debian Compiler-System) zu 100% des Quellcodes der entsprechenden "[Release-Version von GnuPG VS Desktop / Gpg4Win](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=tags)" auf dem GnuPG Git Entwicklungs-Portal. 😃

#### Für Details und Unterschiede zum Original lesen Sie bitte die Datei zur jeweiligen Version von "[Gpg4Win](https://github.com/landsh-de/Gpg4Win/releases)" im Release-Zweig des Projektes ...

#### Bitte installieren Sie zur Aktivierung der "VS-NfD"-Konformität ("de-vs" Modus) von "Gpg4Win" das Companion-Werkzeug "[GpgTools](https://github.com/landsh-de/GpgTools/releases)" in der entsprechenden Version (i. e.: Gpg4Win 3.1.23 <=> GpgTools 1.3.23.x / Gpg4Win 3.1.24 <=> GpgTools 1.3.24.x) ...

#### "[GpgTools](https://github.com/landsh-de/GpgTools)" ist ein "Addon" als Installer-Paket zur Herstellung der "VS-NfD"-Konformität ("de-vs" Modus) für das Open-Source Projekt "[Gpg4Win](https://github.com/landsh-de/Gpg4Win)".


### (en)

#### The release source-code of this version of "Gpg4Win" corresponds (apart from adjustments to the Debian compiler system) to 100% of the source-code of the corresponding "[Release version of GnuPG VS Desktop / Gpg4Win](https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gpg4win.git;a=tags)" on the GnuPG Git development portal.

#### For details and differences to the original version, please read the file for the respective version of "[Gpg4Win](https://github.com/landsh-de/Gpg4Win/releases)" in the release branch of the project ...

#### To activate the "VS-NfD" conformity ("de-vs" mode) of "Gpg4Win", please install the companion tool "[GpgTools](https://github.com/landsh-de/GpgTools/releases)" in the appropriate version (i. e.: Gpg4Win 3.1.23 <=> GpgTools 1.3.23.x / Gpg4Win 3.1.24 <=> GpgTools 1.3.24.x) ...

#### "[GpgTools](https://github.com/landsh-de/GpgTools)" is an "addon" as an installer package to create "VS-NfD" conformity ("de-vs" mode) for the open source project "[Gpg4Win](https://github.com/landsh-de/Gpg4Win)". <br><br>
