Ab der DATAflor BUSINESS Version 2023 unterstützt der Digitale Posteingang das Update von Mengenansätzen in das DATAflor BUSINESS.

Das Update erfolgt über die Verzeichnisüberwachung (ein Update über die Programmoberfläche wird nicht unterstützt) und verwendet als Dateiformat XML. Der Dateiname der Updatedatei spielt keine Rolle, die Dateiendung muss allerdings .xml sein. Das Encoding der Datei muss UTF-8 sein.

Der Aufbau der XML-Datei muss dem Schema DFMengenansatzUpdate.xsd entsprechen. Für ein erfolgreiches Update muss entweder das Feld IdPosition oder die Kombination aus den Feldern PosNr (Positions-Nr.) und LvNr (Leistungsverzeichnis-Nr.) einem Datensatz im DATAflor BUSINESS entsprechen.

Wenn ein Datensatz nicht zugeordnet werden kann oder sonstige Fehler enthält, werden die Updates für die komplette Datei nicht ausgeführt! Die eingelesene Datei wird dann (zusammen mit einer Fehlerbeschreibungsdatei, die den gefundenen Fehler beschreibt) in das Verzeichnis BusinessData\Inbox Files\failed (in der BUSINESS-Freigabe auf dem Server) verschoben.
