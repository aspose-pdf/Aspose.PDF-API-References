---
title: "Fonte"
linktitle: "Fonte"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa um objeto de fonte. </p> <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e alterar a fonte da primeira ocorrência encontrada. // Open document Document doc."
type: docs
weight: 1650
url: /pt/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> Representa objeto de fonte. </p> <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e alterar a fonte da primeira ocorrência encontrada. // Abrir documento Document doc = new Document("input.pdf"); // Criar objeto TextFragmentAbsorber para encontrar todas as ocorrências de texto "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Aceitar o absorvedor na primeira página doc.getPages().get_Item(1).accept(absorber); // Criar fonte e marcá-la para incorporação Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Alterar a fonte da primeira ocorrência de texto absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Salvar documento doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## Métodos

| Método | Descrição |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | Determina se a fonte contém caracteres especificados |
| [getActualFontName](#getActualFontName--) | <p> Obtém o nome real da fonte do objeto {@code Font} se ele estiver inicializado. Mesmo quando a fonte é substituída ou tem um nome interno para pdf. Ou string vazia se a fonte não estiver inicializada. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | Mede o ponto máximo de ascensão. |
| [getBaseFont](#getBaseFont--) | Obtém o valor BaseFont do objeto de fonte PDF. Também conhecido como nome PostScript da fonte. |
| [getDecodedFontName](#getDecodedFontName--) | Às vezes, fontes PDF (geralmente fontes chinesas/japonesas/coreanas) podem ter um nome de fonte específico. Esse nome é o valor da propriedade "BaseFont" da fonte PDF e, às vezes, essa propriedade pode ser representada em forma hexadecimal. Se ler esse nome diretamente, ele pode aparecer em um formato não legível. Para obter uma forma legível, é necessário decodificar o nome da fonte segundo regras específicas para essa fonte. Essa propriedade devolve o nome da fonte decodificado, portanto use-a nos casos em que você encontrar um {@code FontName} não legível. Se a propriedade {@code FontName} já estiver em forma legível, esta propriedade será a mesma que {@code FontName}, então você pode usar esta propriedade em qualquer caso em que precisar obter o nome da fonte em forma legível. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | Mede o ponto máximo de descida. |
| [getFontName](#getFontName--) | <p> Obtém o nome da fonte do objeto {@code Font}. </p> |
| [getFontOptions](#getFontOptions--) | Propriedades úteis para ajustar o comportamento da fonte |
| [getIFont](#getIFont--) | <p> Objeto de fonte do sistema. </p> <hr> <p> Apenas para uso interno </p> |
| [getIPdfFont](#getIPdfFont--) | <p> Objeto de fonte PDF. </p> <hr> <p> Apenas para uso interno </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | Um objetivo deste método - retornar a descrição do erro se uma tentativa de incorporar a fonte falhar. Se não houver casos de erro, ele retorna uma string vazia. |
| [getType](#getType--) | Nome do tipo da fonte |
| [isAccessible](#isAccessible--) | <p> Obtém indicando se a fonte está presente (instalada) no sistema. </p> |
| [isEmbedded](#isEmbedded--) | <p> Obtém um valor que indica se a fonte está incorporada. Fonte baseada em IFont será automaticamente subconjunto e incorporada </p> <hr> <pre> O exemplo a seguir demonstra como encontrar uma fonte, marcá-la como incorporada, pesquisar texto na página do documento e substituir a fonte do texto. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> Obtém um valor que indica se a fonte é um subconjunto. Fonte baseada em IFont será automaticamente subconjunto e incorporada </p> <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e obter o valor que indica se a fonte é um subconjunto. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | Mede a cadeia de caracteres. |
| [save](#save-java.io.OutputStream-) | Salva a fonte no stream. Observe que a fonte é salva em formato TTF intermediário destinado a ser usado apenas em uma cópia convertida do documento original. O arquivo de fonte não deve ser usado fora do contexto do documento original. |
| [setEmbedded](#setEmbedded-boolean-) | Define um valor que indica se a fonte está incorporada. Fonte baseada em IFont será automaticamente subconjunto e incorporada |
| [setSubset](#setSubset-boolean-) | Define um valor que indica se a fonte é um subconjunto. Fonte baseada em IFont será automaticamente subconjunto e incorporada |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
Determina se a fonte contém caracteres especificados

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> Obtém o nome real da fonte do objeto {@code Font} se ele estiver inicializado. Mesmo quando a fonte é substituída ou tem um nome interno para pdf. Ou string vazia se a fonte não estiver inicializada. </p>

**Returns:**
Valor da string <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e visualizar o nome real da fonte da primeira ocorrência de texto. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
Mede o ponto máximo de ascensão.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

Obtém o valor BaseFont do objeto de fonte PDF. Também conhecido como nome PostScript da fonte.

**Returns:**
valor String

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

Às vezes, fontes PDF (geralmente fontes chinesas/japonesas/coreanas) podem ter um nome de fonte específico. Esse nome é o valor da propriedade "BaseFont" da fonte PDF e, às vezes, essa propriedade pode ser representada em forma hexadecimal. Se ler esse nome diretamente, ele pode aparecer em um formato não legível. Para obter uma forma legível, é necessário decodificar o nome da fonte segundo regras específicas para essa fonte. Essa propriedade devolve o nome da fonte decodificado, portanto use-a nos casos em que você encontrar um {@code FontName} não legível. Se a propriedade {@code FontName} já estiver em forma legível, esta propriedade será a mesma que {@code FontName}, então você pode usar esta propriedade em qualquer caso em que precisar obter o nome da fonte em forma legível.

**Returns:**
valor String

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
Mede o ponto máximo de descida.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> Obtém o nome da fonte do objeto {@code Font}. </p>

**Returns:**
Valor da string <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e visualizar o nome da fonte da primeira ocorrência de texto. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

Propriedades úteis para ajustar o comportamento da fonte

**Returns:**
Objeto IFontOptions

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> Objeto de fonte do sistema. </p> <hr> <p> Apenas para uso interno </p>

**Returns:**
Objeto IFont

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> Objeto de fonte PDF. </p> <hr> <p> Apenas para uso interno </p>

**Returns:**
Objeto IPdfFont

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

Um objetivo deste método - retornar a descrição do erro se uma tentativa de incorporar a fonte falhar. Se não houver casos de erro, ele retorna uma string vazia.

**Returns:**
Descrição do erro

### getType {#getType--}
```
public String getType()
```

Nome do tipo da fonte

**Returns:**
Objeto String

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> Obtém indicando se a fonte está presente (instalada) no sistema. </p>

**Returns:**
Valor booleano <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e obter o valor que indica se a fonte está instalada no sistema. // Open document Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println(\"the font is installed in the system\"); </pre> <hr> <p> Algumas operações não estão disponíveis para fontes que não foram encontradas no sistema. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> Obtém um valor que indica se a fonte está incorporada. Fonte baseada em IFont será automaticamente subconjunto e incorporada </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Arial\"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document(\"D:\\Tests\\input.pdf\"); // create TextFragmentAbsorber object to find all \"hello world\" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber(\"hello world\"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save(\"D:\\Tests\\output.pdf\"); </pre>

**Returns:**
Valor booleano @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> Obtém um valor que indica se a fonte é um subconjunto. Fonte baseada em IFont será automaticamente subconjunto e incorporada </p> <hr> <pre> O exemplo demonstra como pesquisar texto na primeira página e obter o valor que indica se a fonte é um subconjunto. // Open document Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println(\"the font is a subset\"); </pre>

**Returns:**
Valor booleano @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
Mede a cadeia de caracteres.

### save {#save-java.io.OutputStream-}
Salva a fonte no stream. Observe que a fonte é salva em formato TTF intermediário destinado a ser usado apenas em uma cópia convertida do documento original. O arquivo de fonte não deve ser usado fora do contexto do documento original.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

Define um valor que indica se a fonte está incorporada. Fonte baseada em IFont será automaticamente subconjunto e incorporada

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

Define um valor que indica se a fonte é um subconjunto. Fonte baseada em IFont será automaticamente subconjunto e incorporada

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
