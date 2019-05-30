# EasySignTool
Eine lokalisierte, grafische Benutzeroberfläche (Winforms), um mit der Signtool.exe, die im Windows SDK zur Verfügung gestellt wird, ausführbare und DLL-Inhalte leicht zu signieren.

> Arbeitstitel: Signtool UI

## Einige häufige Fragen
### Wo befindet sich die Signtool.exe Datei?
Das hängt von der Version Ihrer SDK-Installation ab.
Überprüfen Sie es, indem Sie folgende Schritte ausführen:
* Öffnen Sie eine Visual Studio Developer Befehlszeile 
* Geben Sie `where signtool.exe` ein 
* Kopieren Sie den Pfad zur Datei

### Was ist eine PFX Datei?
Das PFX ist das Zertifikat, mit dem Sie Ihre Binärdateien signieren möchten. Die Signatur dieser Dateien stellt sicher, dass es sich um die ursprüngliche Datei handelt, die von Ihnen/Ihrem Unternehmen veröffentlicht wurde, und beweist, dass sich niemand damit beschäftigt hat.
> Bitte daran denken: Keine Sicherheitsvorkehrung ist stark genug 😉

### Brauche ich einen Zeitstempel-Server?
Nein, aber Sie können eine verwenden, wenn sie von Ihrer Zertifizierungsstelle zur Verfügung gestellt wird.

## Systemanforderungen
* .NET Framework 4.0+
* Windows SDK oder eine Visual Studio Installation, die Signtool.exe enthält

