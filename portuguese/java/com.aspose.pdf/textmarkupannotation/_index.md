---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe base abstrata para anotações de marcação de texto."
type: docs
weight: 5180
url: /pt/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Classe base abstrata para anotações de marcação de texto.

## Métodos

| Método | Descrição |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Atualiza os QuadPoints, de acordo com a transformação da matriz. |
| [getMarkedText](#getMarkedText--) | Obtém o texto sob a anotação de marcação como string. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Obtém o texto sob a anotação de marcação como {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Obtém um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Define um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Atualiza os QuadPoints, de acordo com a transformação da matriz.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Obtém o texto sob a anotação de marcação como string.

**Returns:**
String contendo o texto que está sob a anotação de marcação.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Obtém o texto sob a anotação de marcação como {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} contendo {@code TextFragment}s que estão sob a anotação de marcação.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Obtém um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação.

**Returns:**
array de valores Point

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Define um array de pontos que especifica as coordenadas de n quadriláteros. Cada quadrilátero abrange uma palavra ou um grupo de palavras contíguas no texto subjacente à anotação.
