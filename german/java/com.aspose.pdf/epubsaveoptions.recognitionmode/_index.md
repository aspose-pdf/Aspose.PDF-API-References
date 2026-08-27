---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Wenn eine PDF-Datei (die normalerweise ein festes Layout hat) konvertiert wird, versucht die Konvertierungs-Engine, Gruppierungen und mehrstufige Analysen durchzuführen, um das Originaldokument wiederherzustellen."
type: docs
weight: 1250
url: /de/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

Wenn eine PDF-Datei (die normalerweise ein festes Layout hat) konvertiert wird, versucht die Konvertierungsengine, Gruppierungen und mehrstufige Analysen durchzuführen, um die Absicht des ursprünglichen Dokumentautors wiederherzustellen und ein Ergebnis im Flow-Layout zu erzeugen. Diese Eigenschaft stellt diese Konvertierung für die gewünschte Methode der Inhaltserkennung ein.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Fixed](#Fixed) | Dieser Modus ist schnell und gut, um das ursprüngliche Aussehen der Seiten maximal zu erhalten, aber leider unterstützen viele EPUB-Reader kein xhtml mit festem Layout. |
| [Flow](#Flow) | Vollständiger Erkennungsmodus, die Engine versucht, Gruppierungen und mehrstufige Analysen durchzuführen, um die Absicht des ursprünglichen Dokumentautors wiederherzustellen und xhtml im Fließlayout zu erzeugen. |
| [PdfFlow](#PdfFlow) | Die Hauptidee dieser Konvertierung basiert darauf, die "natürliche" Reihenfolge der Inhaltsdarstellung zu speichern, die während der Verarbeitung von PDF‑Dokumenten entsteht. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

Dieser Modus ist schnell und gut, um das ursprüngliche Aussehen der Seiten maximal zu erhalten, aber leider unterstützen viele EPUB-Reader kein xhtml mit festem Layout.

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Vollständiger Erkennungsmodus, die Engine versucht, Gruppierungen und mehrstufige Analysen durchzuführen, um die Absicht des ursprünglichen Dokumentautors wiederherzustellen und xhtml im Fließlayout zu erzeugen.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

Die Hauptidee dieser Konvertierung basiert darauf, die "natürliche" Reihenfolge der Inhaltsdarstellung zu speichern, die während der Verarbeitung von PDF‑Dokumenten entsteht.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
