---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe PDF3DAnnotation. Esta classe não pode ser herdada. @see Annotation"
type: docs
weight: 3560
url: /pt/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Classe PDF3DAnnotation. Esta classe não pode ser herdada. @see Annotation

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Inicializa uma nova instância da classe {@code PDF3DAnnotation}. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Inicializa uma nova instância da classe {@code PDF3DAnnotation}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Aceita visitante para processamento de anotações. |
| [clearImagePreview](#clearImagePreview--) | Limpa a visualização da imagem. |
| [getAnnotationType](#getAnnotationType--) | Obtém o tipo da anotação. Valor: O tipo da anotação. |
| [getContent](#getContent--) | Obtém ou define o conteúdo. Valor: O conteúdo. |
| [getImagePreview](#getImagePreview--) | Obtém a visualização da imagem. |
| [getLightingScheme](#getLightingScheme--) | Obtém o esquema de iluminação. Valor: O esquema de iluminação. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Obtém a Arte 3D. Valor: A arte PDF3 d. |
| [getRenderMode](#getRenderMode--) | Obtém o modo de renderização. Valor: O modo de renderização. |
| [getViewArray](#getViewArray--) | Obtém o array de visualização. Valor: O array de visualização. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Obtém ou define o conteúdo. Valor: O conteúdo. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Define o índice da visualização padrão. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Define a visualização da imagem. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Define a visualização da imagem. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Inicializa uma nova instância da classe {@code PDF3DAnnotation}.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Inicializa uma nova instância da classe {@code PDF3DAnnotation}.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Aceita visitante para processamento de anotações.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Limpa a visualização da imagem.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtém o tipo da anotação. Valor: O tipo da anotação.

**Returns:**
valor int

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Obtém ou define o conteúdo. Valor: O conteúdo.

**Returns:**
objeto PDF3DContent

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Obtém a visualização da imagem.

**Returns:**
Visualização da imagem como fluxo.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Obtém o esquema de iluminação. Valor: O esquema de iluminação.

**Returns:**
objeto PDF3DLightingScheme

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Obtém a Arte 3D. Valor: A arte PDF3 d.

**Returns:**
objeto PDF3DArtwork

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Obtém o modo de renderização. Valor: O modo de renderização.

**Returns:**
objeto PDF3DRenderMode

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Obtém o array de visualização. Valor: O array de visualização.

**Returns:**
objeto PDF3DViewArray

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Obtém ou define o conteúdo. Valor: O conteúdo.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Define o índice da visualização padrão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index |  | O índice de visualização padrão. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Define a visualização da imagem.

### setImagePreview {#setImagePreview-java.lang.String-}
Define a visualização da imagem.
