---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt eine Sammlung von CharInfo-Objekten dar. </p> <hr> <pre> Das Beispiel zeigt, wie man über alle Zeichen iteriert und das Zeichen abruft //open document Document."
type: docs
weight: 570
url: /de/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Stellt die CharInfo-Objektsammlung dar. </p> <hr> <pre> Das Beispiel demonstriert, wie man über alle Zeichen iteriert und das Zeichen abruft //öffne Dokument Document pdfDocument = new Document(inFile); //erstelle TextFragmentAbsorber-Objekt, um alle Textobjekte der Seite zu sammeln TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //akzeptiere den Absorber für alle Seiten pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //hole die extrahierten Textfragmente TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //durchlaufe die Fragmente for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //durchlaufe die Segmente for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //durchlaufe die Zeichen {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // gib Zeichenposition und Rechteckinformationen aus System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Bietet Zugriff auf Positionsinformationen von Zeichen in Textsegmenten. </p>

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Noch nicht unterstützt. Die Sammlung ist schreibgeschützt und wirft eine Ausnahme. |
| [clear](#clear--) | Noch nicht unterstützt. Die Sammlung ist schreibgeschützt. Wirft immer NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays. |
| [get_Item](#get_Item-int-) | Liefert das CharInfo-Element am angegebenen Index 1..n. |
| [getSyncRoot](#getSyncRoot--) | Liefert ein Objekt, das zur Synchronisation des Zugriffs auf die Sammlung verwendet werden kann. |
| [isReadOnly](#isReadOnly--) | Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist |
| [isSynchronized](#isSynchronized--) | Liefert einen Wert, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread‑sicher) ist. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [iterator](#iterator--) | Gibt einen Enumerator für die gesamte Sammlung zurück. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Noch nicht unterstützt. Die Sammlung ist schreibgeschützt und wirft eine Ausnahme. |
| [size](#size--) | Liefert die Anzahl der {@code CharInfo} Objekt-Elemente, die tatsächlich in der Sammlung enthalten sind. |

### add {#add-com.aspose.pdf.CharInfo-}
Noch nicht unterstützt. Die Sammlung ist schreibgeschützt und wirft eine Ausnahme.

### clear {#clear--}
```
public void clear()
```

Noch nicht unterstützt. Die Sammlung ist schreibgeschützt. Wirft immer NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Bestimmt, ob die Sammlung einen bestimmten Wert enthält.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Kopiert die gesamte Sammlung in ein kompatibles eindimensionales Array, beginnend beim angegebenen Index des Zielarrays.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Liefert das CharInfo-Element am angegebenen Index 1..n.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index innerhalb der Sammlung. |

**Returns:**
CharInfo-Objekt.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Liefert ein Objekt, das zur Synchronisation des Zugriffs auf die Sammlung verwendet werden kann.

**Returns:**
Objekt für Synchronisation

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Liefert einen Wert, der angibt, ob die Sammlung schreibgeschützt ist

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Liefert einen Wert, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread‑sicher) ist.

**Returns:**
boolescher Wert

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Gibt einen Enumerator für die gesamte Sammlung zurück.

**Returns:**
Enumerator-Objekt.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Gibt einen Enumerator für die gesamte Sammlung zurück.

**Returns:**
Enumerator-Objekt.

### remove {#remove-com.aspose.pdf.CharInfo-}
Noch nicht unterstützt. Die Sammlung ist schreibgeschützt und wirft eine Ausnahme.

### size {#size--}
```
public int size()
```

Liefert die Anzahl der {@code CharInfo} Objekt-Elemente, die tatsächlich in der Sammlung enthalten sind.

**Returns:**
int-Wert
