---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa la colección de objetos CharInfo. </p> <hr> <pre> El ejemplo muestra cómo iterar a través de todos los caracteres y recuperar el carácter //open document Document."
type: docs
weight: 570
url: /es/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Representa la colección de objetos CharInfo. </p> <hr> <pre> El ejemplo demuestra cómo iterar a través de todos los caracteres y recuperar el carácter //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Proporciona acceso a la información de posicionamiento de los caracteres del segmento de texto. </p>

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Aún no soportado. La colección es de solo lectura, lanza una excepción. |
| [clear](#clear--) | Aún no soportado. La colección es de solo lectura. Siempre lanza NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Determina si la colección contiene un valor específico. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino. |
| [get_Item](#get_Item-int-) | Obtiene el elemento CharInfo en el índice especificado 1..n. |
| [getSyncRoot](#getSyncRoot--) | Obtiene un objeto que puede usarse para sincronizar el acceso a la colección. |
| [isReadOnly](#isReadOnly--) | Obtiene un valor que indica si la colección es de solo lectura |
| [isSynchronized](#isSynchronized--) | Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Devuelve un enumerador para toda la colección. |
| [iterator](#iterator--) | Devuelve un enumerador para toda la colección. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Aún no soportado. La colección es de solo lectura, lanza una excepción. |
| [size](#size--) | Obtiene el número de elementos de objeto {@code CharInfo} realmente contenidos en la colección. |

### add {#add-com.aspose.pdf.CharInfo-}
Aún no soportado. La colección es de solo lectura, lanza una excepción.

### clear {#clear--}
```
public void clear()
```

Aún no soportado. La colección es de solo lectura. Siempre lanza NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Determina si la colección contiene un valor específico.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Copia toda la colección a una matriz unidimensional compatible, comenzando en el índice especificado de la matriz de destino.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Obtiene el elemento CharInfo en el índice especificado 1..n.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice dentro de la colección. |

**Returns:**
Objeto CharInfo.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtiene un objeto que puede usarse para sincronizar el acceso a la colección.

**Returns:**
Objeto para sincronización

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtiene un valor que indica si la colección es de solo lectura

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtiene un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos).

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Devuelve un enumerador para toda la colección.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.CharInfo-}
Aún no soportado. La colección es de solo lectura, lanza una excepción.

### size {#size--}
```
public int size()
```

Obtiene el número de elementos de objeto {@code CharInfo} realmente contenidos en la colección.

**Returns:**
valor int
