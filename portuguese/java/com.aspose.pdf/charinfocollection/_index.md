---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa a coleção de objetos CharInfo. </p> <hr> <pre> O exemplo demonstra como percorrer todos os caracteres e recuperar o caractere //open document Document."
type: docs
weight: 570
url: /pt/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Iterable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Representa a coleção de objetos CharInfo. </p> <hr> <pre> O exemplo demonstra como iterar por todos os caracteres e recuperar o caractere //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println(\"XIndent : \" + charInfo.getPosition().getXIndent()); System.out.println(\"YIndent : \" + charInfo.getPosition().getYIndent()); System.out.println(\"Width : \" + charInfo.getRectangle().getWidth()); System.out.println(\"Height : \" + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Fornece acesso às informações de posicionamento dos caracteres do segmento de texto. </p>

## Métodos

| Método | Descrição |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Ainda não suportado. A coleção é somente leitura, lança exceção. |
| [clear](#clear--) | Ainda não suportado. A coleção é somente leitura. Sempre lança NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Determina se a coleção contém um valor específico. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino. |
| [get_Item](#get_Item-int-) | Obtém o elemento CharInfo no índice especificado 1..n. |
| [getSyncRoot](#getSyncRoot--) | Obtém um objeto que pode ser usado para sincronizar o acesso à coleção. |
| [isReadOnly](#isReadOnly--) | Obtém um valor que indica se a coleção é somente leitura |
| [isSynchronized](#isSynchronized--) | Obtém um valor que indica se o acesso à coleção está sincronizado (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Retorna um enumerador para toda a coleção. |
| [iterator](#iterator--) | Retorna um enumerador para toda a coleção. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Ainda não suportado. A coleção é somente leitura, lança exceção. |
| [size](#size--) | Obtém o número de elementos de objeto {@code CharInfo} realmente contidos na coleção. |

### add {#add-com.aspose.pdf.CharInfo-}
Ainda não suportado. A coleção é somente leitura, lança exceção.

### clear {#clear--}
```
public void clear()
```

Ainda não suportado. A coleção é somente leitura. Sempre lança NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Determina se a coleção contém um valor específico.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Obtém o elemento CharInfo no índice especificado 1..n.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | Índice dentro da coleção. |

**Returns:**
Objeto CharInfo.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtém um objeto que pode ser usado para sincronizar o acesso à coleção.

**Returns:**
Objeto para sincronização

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtém um valor que indica se a coleção é somente leitura

**Returns:**
valor booleano

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtém um valor que indica se o acesso à coleção está sincronizado (thread safe).

**Returns:**
valor booleano

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Retorna um enumerador para toda a coleção.

**Returns:**
Objeto enumerador.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Retorna um enumerador para toda a coleção.

**Returns:**
Objeto enumerador.

### remove {#remove-com.aspose.pdf.CharInfo-}
Ainda não suportado. A coleção é somente leitura, lança exceção.

### size {#size--}
```
public int size()
```

Obtém o número de elementos de objeto {@code CharInfo} realmente contidos na coleção.

**Returns:**
valor int
