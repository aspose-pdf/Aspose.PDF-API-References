---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine einzelne Schriftdateiquelle dar."
type: docs
weight: 3040
url: /de/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Stellt eine einzelne Schriftdateiquelle dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Initialisiert eine neue Instanz der {@code MemoryFontSource}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [dispose](#dispose--) | Gibt interne Ressourcen frei. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [equals](#equals-java.lang.Object-) | Überprüft, ob Font-Dateiquellen-Objekte gleich sind. |
| [getFontBytes](#getFontBytes--) | Byte-Array der Schriftdatei. |
| [hashCode](#hashCode--) | Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Initialisiert eine neue Instanz der {@code MemoryFontSource}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontBytes |  | Byte-Array der Schriftdatei. |

### close {#close--}
```
public void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Gibt interne Ressourcen frei. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### equals {#equals-java.lang.Object-}
Überprüft, ob Font-Dateiquellen-Objekte gleich sind.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Byte-Array der Schriftdatei.

**Returns:**
byte[] Array

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.)

**Returns:**
ein Hashcode-Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
