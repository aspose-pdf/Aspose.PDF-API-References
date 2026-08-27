---
title: "Ressourcen"
linktitle: "Ressourcen"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die Seitenressourcen darstellt."
type: docs
weight: 4220
url: /de/java/com.aspose.pdf/resources/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Resources

```
public final class Resources extends Object
```

Klasse, die Seitenressourcen darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [clearImagesCache](#clearImagesCache--) |  |
| [freeMemory](#freeMemory--) | Löscht zwischengespeicherte Daten, gibt Speicher frei usw. |
| [getExtGStates](#getExtGStates--) | Ruft alle ExGStates aus den Ressourcen ab. |
| [getFonts](#getFonts--) | Ruft die {@code Fonts}-Ressourcensammlung ab |
| [getFonts](#getFonts-boolean-) | Gibt die Schriftartsammlung zurück. Wenn die Ressourcen keinen Schriftarteintrag enthalten, wird er abhängig vom CreateIfAbsent-Flag erstellt. |
| [getForms](#getForms--) | Ruft die {@code Forms}-Formsammlung ab |
| [getImages](#getImages--) | Ruft die {@code Images}-Bildsammlung ab |
| [getResourceDictionary](#getResourceDictionary--) | Internes Feld |
| [getResourcesFor](#getResourcesFor-com.aspose.pdf.Form-) | Ruft Ressourcen für ab |
| [isCommonResource](#isCommonResource--) | Wahr, wenn diese Ressourcen gemeinsam sind, d.h. für mehrere Seiten geteilt werden (im Seitenwörterbuch platziert oder in jeder Seite als Objektverweis). Die Manipulation gemeinsamer Ressourcen muss sehr vorsichtig durchgeführt werden, zum Beispiel kann das Löschen eines Objekts aus gemeinsamen Ressourcen auf einer Seite Fehler auf anderen Seiten verursachen, wenn das gelöschte Objekt auf anderen Seiten verwendet wurde. |
| [setResourceDictionary](#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-) | Nur für den internen Gebrauch! |

### clearImagesCache {#clearImagesCache--}
```
public final void clearImagesCache()
```



### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Löscht zwischengespeicherte Daten, gibt Speicher frei usw.

### getExtGStates {#getExtGStates--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , Resources.ExtGStateValue > getExtGStates()
```

Ruft alle ExGStates aus den Ressourcen ab.

**Returns:**
Gibt ein Wörterbuch mit den Namen der ExGStates als Schlüssel zurück.

### getFonts {#getFonts--}
```
public FontCollection getFonts()
```

Ruft die {@code Fonts}-Ressourcensammlung ab

**Returns:**
FontCollection-Objekt

### getFonts {#getFonts-boolean-}
```
public FontCollection getFonts(boolean createIfAbsent)
```

Gibt die Schriftartsammlung zurück. Wenn die Ressourcen keinen Schriftarteintrag enthalten, wird er abhängig vom CreateIfAbsent-Flag erstellt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createIfAbsent |  | Wenn dieses Flag wahr ist, werden Schriftarten erstellt, falls dieser Eintrag fehlt. |

**Returns:**
Schriftartsammlung.

### getForms {#getForms--}
```
public XFormCollection getForms()
```

Ruft die {@code Forms}-Formsammlung ab

**Returns:**
XFormCollection-Objekt

### getImages {#getImages--}
```
public XImageCollection getImages()
```

Ruft die {@code Images}-Bildsammlung ab

**Returns:**
XImageCollection-Objekt

### getResourceDictionary {#getResourceDictionary--}
```
public com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary getResourceDictionary()
```

Internes Feld

### getResourcesFor {#getResourcesFor-com.aspose.pdf.Form-}
Ruft Ressourcen für ab

### isCommonResource {#isCommonResource--}
```
public boolean isCommonResource()
```

Wahr, wenn diese Ressourcen gemeinsam sind, d.h. für mehrere Seiten geteilt werden (im Seitenwörterbuch platziert oder in jeder Seite als Objektverweis). Die Manipulation gemeinsamer Ressourcen muss sehr vorsichtig durchgeführt werden, zum Beispiel kann das Löschen eines Objekts aus gemeinsamen Ressourcen auf einer Seite Fehler auf anderen Seiten verursachen, wenn das gelöschte Objekt auf anderen Seiten verwendet wurde.

**Returns:**
boolescher Wert

### setResourceDictionary {#setResourceDictionary-com.aspose.pdf.engine.commondata.pagecontent.IResourceDictionary-}
Nur für den internen Gebrauch!
