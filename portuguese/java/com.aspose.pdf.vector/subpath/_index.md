---
title: "SubPath"
linktitle: "SubPath"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa um objeto de gráficos vetoriais na página. Basicamente, objetos de gráficos vetoriais são representados por dois grupos de SubPaths. Um deles é representado por um conjunto de linhas e."
type: docs
weight: 60
url: /pt/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Representa um objeto de gráficos vetoriais na página. Basicamente, os objetos de gráficos vetoriais são representados por dois grupos de SubPaths. Um deles é representado por um conjunto de linhas e curvas. Outros são apresentados como retângulos e às vezes podem ser confundidos. Normalmente é uma área retangular que tem uma cor, mas muito frequentemente esse retângulo é colocado no início da página e define todo o espaço da página em branco. Assim, você obtém o SubPath, mas visualmente vê apenas o texto na página.

## Métodos

| Método | Descrição |
| --- | --- |
| [getRectangle](#getRectangle--) | Obtém o retângulo delimitador do GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtém o retângulo delimitador do GraphicElement.

**Returns:**
Instância de Rectangle
