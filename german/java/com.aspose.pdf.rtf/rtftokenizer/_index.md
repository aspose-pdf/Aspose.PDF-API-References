---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die entwickelt wurde, um gestreamten RTF‑Inhalt als Menge von Token zu extrahieren."
type: docs
weight: 40
url: /de/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Klasse, die entwickelt wurde, um gestreamten RTF‑Inhalt als Menge von Token zu extrahieren.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [readNextToken](#readNextToken--) | Liest den Eingabestream und gibt das nächste Token zurück. |
| [skip](#skip-int-) | Verbraucht und verwirft die angegebene Anzahl von Zeichen aus dem Eingabestream. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Liest den Eingabestream und gibt das nächste Token zurück.

### skip {#skip-int-}
```
public final void skip(int count)
```

Verbraucht und verwirft die angegebene Anzahl von Zeichen aus dem Eingabestream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Anzahl |  | Die Anzahl der zu überspringenden Zeichen. |
