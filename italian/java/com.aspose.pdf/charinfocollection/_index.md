---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta la collezione di oggetti CharInfo. </p> <hr> <pre> L'esempio dimostra come iterare attraverso tutti i caratteri e recuperare il carattere //open document Document."
type: docs
weight: 570
url: /it/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Rappresenta la collezione di oggetti CharInfo. </p> <hr> <pre> L'esempio dimostra come iterare attraverso tutti i caratteri e recuperare il carattere //apri documento Document pdfDocument = new Document(inFile); //crea l'oggetto TextFragmentAbsorber per raccogliere tutti gli oggetti di testo della pagina TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accetta l'assorbitore per tutte le pagine pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //ottieni i frammenti di testo estratti TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //itera attraverso i frammenti for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //itera attraverso i segmenti for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //itera attraverso i caratteri {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); //stampa le informazioni di posizione e rettangolo del carattere System.out.println(\"XIndent : \" + charInfo.getPosition().getXIndent()); System.out.println(\"YIndent : \" + charInfo.getPosition().getYIndent()); System.out.println(\"Width : \" + charInfo.getRectangle().getWidth()); System.out.println(\"Height : \" + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Fornisce l'accesso alle informazioni di posizionamento dei caratteri del segmento di testo. </p>

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Non ancora supportato. La collezione è di sola lettura, genera un'eccezione. |
| [clear](#clear--) | Non ancora supportato. La collezione è di sola lettura. Genera sempre NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Determina se la collezione contiene un valore specifico. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Copia l'intera collezione in un Array monodimensionale compatibile, iniziando dall'indice specificato dell'array di destinazione. |
| [get_Item](#get_Item-int-) | Restituisce l'elemento CharInfo all'indice specificato 1..n. |
| [getSyncRoot](#getSyncRoot--) | Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione. |
| [isReadOnly](#isReadOnly--) | Restituisce un valore che indica se la collezione è di sola lettura |
| [isSynchronized](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Restituisce un enumeratore per l'intera collezione. |
| [iterator](#iterator--) | Restituisce un enumeratore per l'intera collezione. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Non ancora supportato. La collezione è di sola lettura, genera un'eccezione. |
| [size](#size--) | Restituisce il numero di elementi oggetto {@code CharInfo} effettivamente contenuti nella collezione. |

### add {#add-com.aspose.pdf.CharInfo-}
Non ancora supportato. La collezione è di sola lettura, genera un'eccezione.

### clear {#clear--}
```
public void clear()
```

Non ancora supportato. La collezione è di sola lettura. Genera sempre NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Determina se la collezione contiene un valore specifico.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Copia l'intera collezione in un Array monodimensionale compatibile, iniziando dall'indice specificato dell'array di destinazione.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Restituisce l'elemento CharInfo all'indice specificato 1..n.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index |  | Indice nella collezione. |

**Returns:**
Oggetto CharInfo.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Restituisce un oggetto che può essere usato per sincronizzare l'accesso alla collezione.

**Returns:**
Oggetto per la sincronizzazione

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Restituisce un valore che indica se la collezione è di sola lettura

**Returns:**
valore booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread safe).

**Returns:**
valore booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Restituisce un enumeratore per l'intera collezione.

**Returns:**
Oggetto enumeratore.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Restituisce un enumeratore per l'intera collezione.

**Returns:**
Oggetto enumeratore.

### remove {#remove-com.aspose.pdf.CharInfo-}
Non ancora supportato. La collezione è di sola lettura, genera un'eccezione.

### size {#size--}
```
public int size()
```

Restituisce il numero di elementi oggetto {@code CharInfo} effettivamente contenuti nella collezione.

**Returns:**
valore int
