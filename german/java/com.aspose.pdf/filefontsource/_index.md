---
title: "FileFontSource"
linktitle: "FileFontSource"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine einzelne Schriftdateiquelle dar."
type: docs
weight: 1450
url: /de/java/com.aspose.pdf/filefontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.FileFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.FileFontSource

```
public final class FileFontSource extends FontSource
```

Stellt eine einzelne Schriftdateiquelle dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileFontSource](#FileFontSource-java.lang.String-) | Initialisiert eine neue Instanz der {@code FileFontSource}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Überprüft, ob Font-Dateiquellen-Objekte gleich sind. |
| [getFilePath](#getFilePath--) | Pfad zur Schriftdatei. |
| [hashCode](#hashCode--) | Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie z. B. von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während der Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben ganzzahligen Wert zurückgeben, vorausgesetzt, dass keine Informationen, die in {@code equals}-Vergleichen des Objekts verwendet werden, geändert wurden. Dieser ganzzahlige Wert muss nicht von einer Programmausführung zur nächsten gleich bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe ganzzahlige Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass bei ungleichen Objekten gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche ganzzahlige Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher ganzzahliger Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> Soweit praktisch möglich, gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Ganzzahlen für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in eine Ganzzahl umgewandelt wird, aber diese Implementierungstechnik ist für die Java <span style=\"font-size:70%\"><sup>TM</sup></span>-Programmiersprache nicht vorgeschrieben.) |
| [setFilePath](#setFilePath-java.lang.String-) | Pfad zur Schriftdatei. |

### FileFontSource {#FileFontSource-java.lang.String-}
Initialisiert eine neue Instanz der {@code FileFontSource}-Klasse.

### equals {#equals-java.lang.Object-}
Überprüft, ob Font-Dateiquellen-Objekte gleich sind.

### getFilePath {#getFilePath--}
```
public String getFilePath()
```

Pfad zur Schriftdatei.

**Returns:**
String Wert

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie z. B. von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während der Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben ganzzahligen Wert zurückgeben, vorausgesetzt, dass keine Informationen, die in {@code equals}-Vergleichen des Objekts verwendet werden, geändert wurden. Dieser ganzzahlige Wert muss nicht von einer Programmausführung zur nächsten gleich bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe ganzzahlige Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass bei ungleichen Objekten gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche ganzzahlige Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher ganzzahliger Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> Soweit praktisch möglich, gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Ganzzahlen für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in eine Ganzzahl umgewandelt wird, aber diese Implementierungstechnik ist für die Java <span style=\"font-size:70%\"><sup>TM</sup></span>-Programmiersprache nicht vorgeschrieben.)

**Returns:**
ein Hashcode-Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### setFilePath {#setFilePath-java.lang.String-}
Pfad zur Schriftdatei.
