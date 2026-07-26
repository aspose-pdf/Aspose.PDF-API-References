---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Ermöglicht die Steuerung, wie ein PDF-Dokument in ein Textverarbeitungsdokument konvertiert wird. Verwenden Sie den Modus RecognitionMode.Textbox, wenn das resultierende Dokument nicht stark bearbeitet werden soll."
type: docs
weight: 1050
url: /de/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Ermöglicht die Steuerung, wie ein PDF-Dokument in ein Textverarbeitungsdokument konvertiert wird. Verwenden Sie den Modus RecognitionMode.Textbox, wenn das resultierende Dokument nicht stark weiter bearbeitet werden soll. Textfelder lassen sich leicht ändern, wenn nicht viel zu tun ist. Verwenden Sie den Modus RecognitionMode.Flow, wenn das Ausgabedokument weitere Bearbeitung benötigt. Absätze und Textzeilen im Flow-Modus ermöglichen eine einfache Textbearbeitung, jedoch sehen nicht unterstützte Formatierungsobjekte schlechter aus als im RecognitionMode.Textbox-Modus.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | Ein alternativer Flow-Modus, der die Erkennung von Tabellen unterstützt. |
| [Flow](#Flow) | Vollständiger Erkennungsmodus, die Engine führt Gruppierung und mehrstufige Analyse durch, um die Absicht des ursprünglichen Dokumentautors wiederherzustellen und ein maximal bearbeitbares Dokument zu erzeugen. |
| [Textbox](#Textbox) | Dieser Modus ist schnell und gut geeignet, das ursprüngliche Aussehen der PDF-Datei maximal zu erhalten, jedoch kann die Bearbeitbarkeit des resultierenden Dokuments eingeschränkt sein. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

Ein alternativer Flow-Modus, der die Erkennung von Tabellen unterstützt.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Vollständiger Erkennungsmodus, die Engine führt Gruppierung und mehrstufige Analyse durch, um die Absicht des ursprünglichen Dokumentautors wiederherzustellen und ein maximal bearbeitbares Dokument zu erzeugen.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

Dieser Modus ist schnell und gut geeignet, das ursprüngliche Aussehen der PDF-Datei maximal zu erhalten, jedoch kann die Bearbeitbarkeit des resultierenden Dokuments eingeschränkt sein.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
