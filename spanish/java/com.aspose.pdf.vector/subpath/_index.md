---
title: "SubPath"
linktitle: "SubPath"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un objeto de gráficos vectoriales en la página. Básicamente, los objetos de gráficos vectoriales se representan mediante dos grupos de SubPaths. Uno de ellos se representa mediante un conjunto de líneas y."
type: docs
weight: 60
url: /es/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Representa un objeto de gráficos vectoriales en la página. Básicamente, los objetos de gráficos vectoriales se representan mediante dos grupos de SubPaths. Uno de ellos está representado por un conjunto de líneas y curvas. Los demás se presentan como rectángulos y a veces pueden confundirse. Normalmente es un área rectangular que tiene un color, pero con frecuencia este rectángulo se coloca al inicio de la página y define todo el espacio de la página en blanco. Así que obtienes el SubPath, pero visualmente solo ves el texto en la página.

## Métodos

| Método | Descripción |
| --- | --- |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo delimitador del GraphicElement. |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo delimitador del GraphicElement.

**Returns:**
Instancia de Rectangle
