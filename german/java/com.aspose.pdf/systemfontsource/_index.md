---
title: "SystemFontSource"
linktitle: "SystemFontSource"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt alle im System installierten Schriftarten dar."
type: docs
weight: 4770
url: /de/java/com.aspose.pdf/systemfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.SystemFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.SystemFontSource

```
public final class SystemFontSource extends FontSource
```

Stellt alle im System installierten Schriftarten dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SystemFontSource](#SystemFontSource--) | Initialisiert eine neue Instanz der Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Prüft, ob System‑Font‑Quellobjekte gleich sind. |
| [getFontDefinitions](#getFontDefinitions--) | Nur für den internen Gebrauch |
| [hashCode](#hashCode--) | Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.) |

### SystemFontSource {#SystemFontSource--}
```
public SystemFontSource()
```

Initialisiert eine neue Instanz der Klasse.

### equals {#equals-java.lang.Object-}
Prüft, ob System‑Font‑Quellobjekte gleich sind.

### getFontDefinitions {#getFontDefinitions--}
```
public com.aspose.font.FontDefinition[] getFontDefinitions()
```

Nur für den internen Gebrauch

**Returns:**
FontDefinition[]‑Objekt

### hashCode {#hashCode--}
```
public int hashCode()
```

Gibt einen Hashcode-Wert für das Objekt zurück. Diese Methode wird zum Nutzen von Hashtabellen unterstützt, wie sie von {@link java.util.HashMap} bereitgestellt werden. <p> Der allgemeine Vertrag von {@code hashCode} lautet: <ul> <li>Immer wenn sie während einer Ausführung einer Java-Anwendung mehr als einmal für dasselbe Objekt aufgerufen wird, muss die {@code hashCode}-Methode konsistent denselben Integer zurückgeben, vorausgesetzt, dass keine in {@code equals} Vergleichen des Objekts verwendeten Informationen geändert werden. Dieser Integer muss nicht von einer Programmausführung zur nächsten konsistent bleiben. <li>Wenn zwei Objekte gemäß der {@code equals(Object)}-Methode gleich sind, muss der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte dasselbe Integer-Ergebnis liefern. <li>Es ist <em>nicht</em> erforderlich, dass wenn zwei Objekte gemäß der {@link java.lang.Object#equals(java.lang.Object)}-Methode ungleich sind, der Aufruf der {@code hashCode}-Methode für jedes der beiden Objekte unterschiedliche Integer-Ergebnisse liefert. Der Programmierer sollte jedoch beachten, dass das Erzeugen unterschiedlicher Integer-Ergebnisse für ungleiche Objekte die Leistung von Hashtabellen verbessern kann. </ul> <p> So weit wie praktisch möglich gibt die von der Klasse {@code Object} definierte hashCode-Methode unterschiedliche Integer für unterschiedliche Objekte zurück. (Dies wird typischerweise implementiert, indem die interne Adresse des Objekts in einen Integer umgewandelt wird, aber diese Implementierungstechnik ist nicht durch die Java<span style="font-size:70%"><sup>TM</sup></span>-Programmiersprache vorgeschrieben.)

**Returns:**
ein Hashcode-Wert für dieses Objekt. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
