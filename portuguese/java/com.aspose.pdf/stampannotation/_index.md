---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "<p> Representa a anotação de carimbo de borracha. Este tipo de anotação exibe texto ou gráficos que parecem ter sido carimbados na página com um carimbo de borracha. </p> <hr>."
type: docs
weight: 4630
url: /pt/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Representa anotação de carimbo de borracha. Este tipo de anotação exibe texto ou gráficos que parecem ter sido carimbados na página com um carimbo de borracha. </p> <hr> <pre> O próximo trecho de código demonstra como adicionar 2 carimbos na primeira página do documento PDF. O documento de entrada vem de inFile e as alterações são salvas em outFile. O primeiro carimbo tem o ícone NotForPublicRelease e o segundo vem com a imagem de rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Construtores

| Construtor | Descrição |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Construtor |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Cria uma nova anotação de carimbo na página especificada. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita o visitante {@code AnnotationSelector} ao percorrer a coleção de anotações. |
| [clear](#clear--) | Limpar instâncias estáticas |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. |
| [getIcon](#getIcon--) | Obtém ícone para carimbo de borracha. |
| [getImage](#getImage--) | Obtém imagem da anotação. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Define imagem SVG da anotação em string Base64. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Define ícone para carimbo de borracha. |
| [setImage](#setImage-java.io.InputStream-) | Define imagem da anotação. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Construtor

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Cria uma nova anotação de carimbo na página especificada.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita o visitante {@code AnnotationSelector} ao percorrer a coleção de anotações.

### clear {#clear--}
```
public static void clear()
```

Limpar instâncias estáticas

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Obtém ícone para carimbo de borracha.

**Returns:**
valor StampIcon

### getImage {#getImage--}
```
public InputStream getImage()
```

Obtém imagem da anotação.

**Returns:**
objeto InputStream

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Define imagem SVG da anotação em string Base64.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Define ícone para carimbo de borracha.

### setImage {#setImage-java.io.InputStream-}
Define imagem da anotação.
