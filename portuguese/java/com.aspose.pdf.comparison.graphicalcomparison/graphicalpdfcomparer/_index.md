---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para comparar documentos PDF graficamente. Deve ser usada para buscar pequenas alterações, principalmente de natureza gráfica. Para comparar alterações no conteúdo de texto, use outra."
type: docs
weight: 10
url: /pt/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Representa uma classe para comparar graficamente documentos PDF. Deve ser usada para buscar pequenas alterações, principalmente de natureza gráfica. Para comparar alterações no conteúdo de texto, use outras classes de comparação de PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Cria uma instância da classe {@link GraphicalPdfComparer}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Compara documentos graficamente. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Compara documentos graficamente. O resultado da comparação é colocado em um documento PDF. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compara páginas graficamente. O resultado da comparação é colocado em uma imagem. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF. |
| [getColor](#getColor--) | Obtém e define a cor da bandeira de alteração. A cor padrão é vermelha. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Obtém diferenças entre imagens de páginas. O resultado contém uma imagem da primeira página comparada e um array de diferenças. |
| [getResolution](#getResolution--) | Obtém e define a resolução das imagens resultantes. O valor padrão é 150 dpi. |
| [getThreshold](#getThreshold--) | Obtém e define o valor de limiar em porcentagem. Este valor permite ignorar pequenas alterações se elas não forem significativas para você. O valor padrão é 0%. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Obtém e define a cor da bandeira de alteração. A cor padrão é vermelha. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Obtém e define a resolução das imagens resultantes. O valor padrão é 150 dpi. |
| [setThreshold](#setThreshold-double-) | Obtém e define o valor de limiar em porcentagem. Este valor permite ignorar pequenas alterações se elas não forem significativas para você. O valor padrão é 0%. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Cria uma instância da classe {@link GraphicalPdfComparer}.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Compara documentos graficamente.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Compara documentos graficamente. O resultado da comparação é colocado em um documento PDF.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compara páginas graficamente. O resultado da comparação é colocado em uma imagem.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Compara páginas graficamente. O resultado da comparação é colocado em um documento PDF.

### getColor {#getColor--}
```
public final Color getColor()
```

Obtém e define a cor da bandeira de alteração. A cor padrão é vermelha.

**Returns:**
Instância de Color

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Obtém diferenças entre imagens de páginas. O resultado contém uma imagem da primeira página comparada e um array de diferenças.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Obtém e define a resolução das imagens resultantes. O valor padrão é 150 dpi.

**Returns:**
Instância de Resolution

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Obtém e define o valor de limiar em porcentagem. Este valor permite ignorar pequenas alterações se elas não forem significativas para você. O valor padrão é 0%.

**Returns:**
valor double

### setColor {#setColor-com.aspose.pdf.Color-}
Obtém e define a cor da bandeira de alteração. A cor padrão é vermelha.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Obtém e define a resolução das imagens resultantes. O valor padrão é 150 dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Obtém e define o valor de limiar em porcentagem. Este valor permite ignorar pequenas alterações se elas não forem significativas para você. O valor padrão é 0%.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor double |
