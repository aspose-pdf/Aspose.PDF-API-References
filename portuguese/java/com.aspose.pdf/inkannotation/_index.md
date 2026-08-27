---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um \\\"rabisco\\\" à mão livre composto por um ou mais caminhos desconexos."
type: docs
weight: 2430
url: /pt/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Representa um \"rabisco\" à mão livre composto por um ou mais caminhos desconexos.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Construtor para anotação Ink para Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Cria uma nova anotação Ink na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita um objeto visitante para processar a anotação. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Atualiza os pontos em InkList, de acordo com a transformação da matriz. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getCapStyle](#getCapStyle--) | obter estilo das extremidades de linha da anotação Ink. |
| [getInkList](#getInkList--) | <p> Obtém lista de gestos que são linhas independentes representadas por arrays Point[]. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Defina o estilo das terminações de linha da anotação de tinta. |
| [setInkList](#setInkList-java.util.List-) | Define a lista de gestos que são linhas independentes representadas por arrays Point[]. |
| [updateAppearance](#updateAppearance--) | Atualiza a Aparência, após o texto ter sido alterado/movido. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Construtor para anotação Ink para Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Cria uma nova anotação Ink na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita um objeto visitante para processar a anotação.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Atualiza os pontos em InkList, de acordo com a transformação da matriz.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

obter estilo das extremidades de linha da anotação Ink.

**Returns:**
Elemento CapStyle @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Obtém lista de gestos que são linhas independentes representadas por arrays Point[]. </p>

**Returns:**
{@code List<Point[]>} objeto

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Defina o estilo das terminações de linha da anotação de tinta.

### setInkList {#setInkList-java.util.List-}
Define a lista de gestos que são linhas independentes representadas por arrays Point[].

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Atualiza a Aparência, após o texto ter sido alterado/movido.
